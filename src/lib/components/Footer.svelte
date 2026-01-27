<script>
  import Image from './Image.svelte';
</script>

<footer class="w-full bg-black text-white pt-20 pb-10">
  <div class="container mx-auto px-4">
    <!-- Call to Action -->
    <div class="mb-20">
      <h2 class="text-3xl md:text-5xl font-bold uppercase leading-tight mb-10 max-w-3xl">
        Building the next cultural toy. Want to join the experiment?
      </h2>
      
      <button class="bg-white text-black w-40 h-40 flex flex-col items-center justify-center hover:bg-primary-500 hover:text-white transition-colors">
        <span class="text-sm font-bold uppercase mb-2">Let's</span>
        <span class="text-2xl font-bold uppercase">Build</span>
      </button>
    </div>

    <!-- Journal Section -->
    <div class="border-t border-gray-800 pt-10 mb-20">
      <div class="flex justify-between items-end mb-8">
        <h3 class="text-xl font-bold uppercase">Insights</h3>
        <a href="#" class="text-sm underline">View All</a>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="https://images.unsplash.com/photo-1552664730-d307ca884978?q=80&w=800" alt="Culture Tech" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">Culture-Tech Convergence</h4>
        </div>
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?q=80&w=800" alt="Speed" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">The 4-Week Sprint</h4>
        </div>
        <div class="group cursor-pointer">
          <div class="aspect-[4/3] overflow-hidden mb-4">
            <Image src="https://images.unsplash.com/photo-1484480974693-6ca0a78fb36b?q=80&w=800" alt="Global Design" className="group-hover:scale-105 transition-transform duration-500" />
          </div>
          <h4 class="font-bold uppercase text-sm">Designing for Everyone</h4>
        </div>
      </div>
    </div>

    <!-- Footer Links -->
    <div class="flex flex-col md:flex-row justify-between items-center text-xs text-gray-500 uppercase tracking-widest border-t border-gray-800 pt-10">
      <div class="mb-4 md:mb-0 flex items-center gap-3">
        <div class="w-6 h-auto">
          {@html `<svg width="111" height="132" viewBox="0 0 111 132" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-full h-auto">
<path d="M55.363 13.7842V65.7772L43.5135 59.006C22.4745 46.9146 9.41574 24.4246 9.41574 0H0.709961V59.4896C0.709961 78.8359 11.834 96.7311 29.4875 105.195L55.6049 117.77V65.7772L67.4544 72.5483C88.4934 84.6397 101.552 107.13 101.552 131.554H110.258V72.0646C110.258 52.7184 99.1339 34.8232 81.4804 26.3592L55.363 13.7842Z" fill="white"/>
</svg>`}
        </div>
        <span>&copy; 2024 Relay</span>
      </div>
      <div class="flex gap-8">
        <a href="#" class="hover:text-white">Privacy</a>
        <a href="#" class="hover:text-white">Terms</a>
        <a href="#" class="hover:text-white">Contact</a>
      </div>
    </div>
  </div>
</footer>
