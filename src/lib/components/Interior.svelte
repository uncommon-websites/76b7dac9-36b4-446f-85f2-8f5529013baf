<script>
  import Image from './Image.svelte';
</script>

<section class="w-full relative min-h-screen flex items-center">
  <div class="absolute inset-0">
    <Image 
      src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?q=80&w=2000" 
      alt="Team collaboration" 
    />
    <div class="absolute inset-0 bg-black/30"></div>
  </div>

  <div class="container mx-auto px-4 relative z-10">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div class="hidden md:block"></div>
      <div class="bg-white p-8 md:p-12 max-w-lg">
        <h3 class="text-2xl font-bold uppercase mb-4">Hit-Driven Studio Model</h3>
        <p class="text-gray-600 leading-relaxed mb-6">
          We ship a first version within four weeks, rigorously test traction, and kill what fails without sentimentality. Each app is a potential cultural object that users pick up because they genuinely want to, not out of obligation.
        </p>
        <p class="text-gray-600 leading-relaxed">
          Operating from Singapore, Jakarta, and Tokyo, we build for a worldwide audience. Great taste and intuitive design are universally understood—no localization layers needed.
        </p>
      </div>
    </div>
  </div>
</section>
