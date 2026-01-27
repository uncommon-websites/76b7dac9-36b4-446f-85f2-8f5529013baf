<script>
  import Image from './Image.svelte';
</script>

<section class="relative h-screen w-full overflow-hidden bg-black text-white">
  <div class="absolute inset-0">
    <Image 
      src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?q=80&w=2548&auto=format&fit=crop" 
      alt="Creative workspace" 
      className="opacity-40"
    />
    <div class="absolute inset-0 bg-black/40"></div>
  </div>
  
  <div class="relative z-10 flex h-full items-center justify-center">
    <div class="w-32 md:w-48 lg:w-64">
      {@html `<svg width="111" height="132" viewBox="0 0 111 132" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-full h-auto">
<path d="M55.363 13.7842V65.7772L43.5135 59.006C22.4745 46.9146 9.41574 24.4246 9.41574 0H0.709961V59.4896C0.709961 78.8359 11.834 96.7311 29.4875 105.195L55.6049 117.77V65.7772L67.4544 72.5483C88.4934 84.6397 101.552 107.13 101.552 131.554H110.258V72.0646C110.258 52.7184 99.1339 34.8232 81.4804 26.3592L55.363 13.7842Z" fill="white"/>
</svg>`}
    </div>
  </div>
  
  <!-- Blurry foreground element simulation -->
  <div class="absolute -bottom-20 -left-20 w-1/2 h-1/2 bg-primary-500/10 blur-3xl rounded-full pointer-events-none"></div>
</section>
