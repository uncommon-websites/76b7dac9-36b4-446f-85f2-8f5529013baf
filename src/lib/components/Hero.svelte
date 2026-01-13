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
    <h1 class="font-display text-5xl md:text-7xl lg:text-9xl font-bold uppercase tracking-tighter text-center px-4">
      Toy Company
    </h1>
  </div>
  
  <!-- Blurry foreground element simulation -->
  <div class="absolute -bottom-20 -left-20 w-1/2 h-1/2 bg-primary-500/10 blur-3xl rounded-full pointer-events-none"></div>
</section>
