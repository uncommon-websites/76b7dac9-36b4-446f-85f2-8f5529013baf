<script>
  import Image from './Image.svelte';
</script>

<section class="w-full bg-black text-white py-20">
  <div class="container mx-auto px-4">
    <div class="grid grid-cols-1 md:grid-cols-12 gap-8">
      <!-- Title -->
      <div class="md:col-span-3">
        <h3 class="text-xl font-bold uppercase tracking-widest sticky top-10">Our Approach</h3>
      </div>

      <!-- Gallery -->
      <div class="md:col-span-9 grid grid-cols-1 md:grid-cols-2 gap-4 md:gap-8">
        <!-- Item 1 -->
        <div class="relative aspect-[4/5] group overflow-hidden">
          <Image src="https://images.unsplash.com/photo-1551650975-87deedd944c3?q=80&w=1000" alt="Speed" />
          <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Ship in 4 Weeks</p>
            <p class="text-xs text-gray-400">01</p>
          </div>
        </div>

        <!-- Item 2 -->
        <div class="relative aspect-[4/5] group overflow-hidden mt-12 md:mt-24">
          <Image src="https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?q=80&w=1000" alt="Global" />
          <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Global by Design</p>
            <p class="text-xs text-gray-400">02</p>
          </div>
        </div>

        <!-- Item 3 -->
        <div class="relative aspect-[4/5] group overflow-hidden">
           <Image src="https://images.unsplash.com/photo-1513542789411-b6a5d4f31634?q=80&w=1000" alt="Taste" />
           <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Taste-Led Craft</p>
            <p class="text-xs text-gray-400">03</p>
          </div>
        </div>

        <!-- Item 4 -->
        <div class="relative aspect-[4/5] group overflow-hidden mt-12 md:mt-24">
           <Image src="https://images.unsplash.com/photo-1511988617509-a57c8a288659?q=80&w=1000" alt="Joy" />
           <div class="absolute bottom-4 left-4">
            <p class="text-sm font-bold uppercase">Joyful by Nature</p>
            <p class="text-xs text-gray-400">04</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
