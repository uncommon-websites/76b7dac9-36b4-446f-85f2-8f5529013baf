<script>
  import Image from './Image.svelte';
</script>

<section class="relative w-full bg-primary-200">
  <!-- Background Image - Sticky or Fixed feel -->
  <div class="sticky top-0 h-screen w-full overflow-hidden">
     <Image 
      src="https://images.unsplash.com/photo-1557672172-298e090bd0f1?q=80&w=2000" 
      alt="Abstract background" 
      className="object-cover"
    />
    <div class="absolute inset-0 bg-primary-200/30 mix-blend-multiply"></div>
  </div>

  <!-- Content Overlay -->
  <div class="relative z-10 -mt-[100vh] min-h-screen w-full">
    <div class="container mx-auto px-4 py-20">
      <h2 class="text-4xl md:text-6xl font-bold uppercase text-white mb-20 max-w-xl mix-blend-overlay">
        Products that speak to global culture
      </h2>

      <!-- Grid of White Cards -->
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4 md:gap-8 pb-40">
        
        <!-- Card 1: Mobile Right, Desktop Col 2 -->
        <div class="col-start-2 md:col-start-2 bg-white p-6 aspect-square flex flex-col justify-between hover:scale-105 transition-transform duration-500">
          <span class="text-xs font-bold uppercase text-gray-400">01</span>
          <h4 class="text-xl font-bold uppercase">Running & Competition</h4>
        </div>

        <!-- Card 2: Mobile Left, Desktop Col 4 -->
        <div class="col-start-1 md:col-start-4 mt-12 md:mt-0 bg-white p-6 aspect-square flex flex-col justify-between hover:scale-105 transition-transform duration-500">
          <span class="text-xs font-bold uppercase text-gray-400">02</span>
          <h4 class="text-xl font-bold uppercase">Art & Daily Ritual</h4>
        </div>

        <!-- Card 3: Mobile Right, Desktop Col 1 (Row 2) -->
        <div class="col-start-2 md:col-start-1 mt-12 md:mt-24 bg-white p-6 aspect-square flex flex-col justify-between hover:scale-105 transition-transform duration-500">
          <span class="text-xs font-bold uppercase text-gray-400">03</span>
          <h4 class="text-xl font-bold uppercase">Connection & Serendipity</h4>
        </div>
        
         <!-- Card 4: Mobile Left, Desktop Col 3 (Row 2) -->
        <div class="col-start-1 md:col-start-3 mt-12 md:mt-24 bg-white p-6 aspect-square flex flex-col justify-between hover:scale-105 transition-transform duration-500">
          <span class="text-xs font-bold uppercase text-gray-400">04</span>
          <h4 class="text-xl font-bold uppercase">Culture & Tech</h4>
        </div>
      </div>
    </div>
  </div>
</section>
