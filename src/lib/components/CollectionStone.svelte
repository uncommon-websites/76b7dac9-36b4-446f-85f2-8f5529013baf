<script>
  import Image from './Image.svelte';
</script>

<section class="relative w-full bg-gray-100">
  <!-- Background Image -->
  <div class="sticky top-0 h-screen w-full overflow-hidden">
     <Image 
      src="https://images.unsplash.com/photo-1579546929518-9e396f3cc809?q=80&w=2000" 
      alt="Abstract Background" 
      className="object-cover"
    />
    <div class="absolute inset-0 bg-gray-100/30 mix-blend-multiply"></div>
  </div>

  <!-- Content Overlay -->
  <div class="relative z-10 -mt-[100vh] min-h-screen w-full">
    <div class="container mx-auto px-4 py-20">
      
      <!-- Grid of Black Cards -->
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4 md:gap-8 pb-40 pt-40">
        
        <!-- Card 1: Mobile Left, Desktop Col 1 -->
        <div class="col-start-1 md:col-start-1 bg-black text-white p-6 aspect-square flex flex-col justify-between hover:scale-105 transition-transform duration-500">
          <span class="text-xs font-bold uppercase text-gray-500">01</span>
          <h4 class="text-xl font-bold uppercase">Speed</h4>
        </div>

        <!-- Card 2: Mobile Right, Desktop Col 3 -->
        <div class="col-start-2 md:col-start-3 mt-12 md:mt-0 bg-black text-white p-6 aspect-square flex flex-col justify-between hover:scale-105 transition-transform duration-500">
          <span class="text-xs font-bold uppercase text-gray-500">02</span>
          <h4 class="text-xl font-bold uppercase">Taste</h4>
        </div>

        <!-- Card 3: Mobile Left, Desktop Col 2 (Row 2) -->
        <div class="col-start-1 md:col-start-2 mt-12 md:mt-24 bg-black text-white p-6 aspect-square flex flex-col justify-between hover:scale-105 transition-transform duration-500">
          <span class="text-xs font-bold uppercase text-gray-500">03</span>
          <h4 class="text-xl font-bold uppercase">Craft</h4>
        </div>
        
         <!-- Card 4: Mobile Right, Desktop Col 4 (Row 2) -->
        <div class="col-start-2 md:col-start-4 mt-12 md:mt-24 bg-black text-white p-6 aspect-square flex flex-col justify-between hover:scale-105 transition-transform duration-500">
          <span class="text-xs font-bold uppercase text-gray-500">04</span>
          <h4 class="text-xl font-bold uppercase">Global</h4>
        </div>
      </div>
    </div>
  </div>
</section>
