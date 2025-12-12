<div class="relative bg-black rounded-[3rem] p-3 w-full h-full shadow-2xl ring-1 ring-gray-900/5">
  <!-- Power Button -->
  <div class="absolute -right-[2px] top-24 w-[2px] h-12 bg-gray-800 rounded-r-md"></div>
  <!-- Volume Buttons -->
  <div class="absolute -left-[2px] top-24 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>
  <div class="absolute -left-[2px] top-36 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>

  <!-- Screen -->
  <div class="w-full h-full rounded-[2.5rem] overflow-hidden relative flex flex-col" style="background-color: #1A1A1A;">
    <!-- Status Bar / Notch Area -->
    <div class="h-12 w-full flex justify-center items-start pt-2 absolute top-0 left-0 z-20">
      <div class="w-28 h-7 bg-black rounded-full flex items-center justify-center gap-2 px-3">
        <!-- Dynamic Island Content Simulation -->
        <div class="w-full h-full flex items-center justify-between opacity-0">
           <!-- Hidden content just to keep size -->
        </div>
      </div>
    </div>

    <!-- App Content - Runscore Rating Card -->
    <div class="flex-1 overflow-y-auto pt-16 px-6 pb-6 text-white select-none scrollbar-hide">
      <!-- Header -->
      <div class="flex justify-between items-center mb-8">
        <div class="text-gray-500 text-[10px] uppercase tracking-wider font-semibold">
          December 2024
        </div>
        <div class="text-gray-500 text-[10px] uppercase tracking-wider font-semibold flex items-center gap-1">
          <span>Powered by</span>
          <span class="text-orange-500 font-bold">STRAVA</span>
        </div>
      </div>

      <!-- Rating Card -->
      <div class="bg-[#222] rounded-2xl p-6 mb-6 border border-gray-800">
        <!-- Tier Badge -->
        <div class="flex justify-between items-start mb-6">
          <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full text-[10px] font-bold uppercase tracking-wider" style="background: linear-gradient(135deg, oklch(0.765 0.177 163.223), oklch(0.596 0.145 163.225));">
            <span>Rare</span>
            <span class="opacity-75">#127/500</span>
          </div>
        </div>

        <!-- Runner Info -->
        <div class="mb-6">
          <h2 class="text-2xl font-bold tracking-tight mb-1">Sarah Chen</h2>
          <div class="text-gray-400 text-xs font-medium">San Francisco, CA</div>
        </div>

        <!-- Main Score -->
        <div class="mb-8 pb-6 border-b border-gray-800">
          <div class="text-gray-500 text-[10px] uppercase tracking-wider font-semibold mb-2">Overall Rating</div>
          <div class="text-6xl font-bold tracking-tight" style="color: oklch(0.765 0.177 163.223);">87</div>
        </div>

        <!-- Performance Metrics Grid -->
        <div class="grid grid-cols-2 gap-4 mb-6">
          <div>
            <div class="text-gray-500 text-[9px] uppercase tracking-wider font-semibold mb-1.5">Pace</div>
            <div class="text-2xl font-bold">92</div>
          </div>
          <div>
            <div class="text-gray-500 text-[9px] uppercase tracking-wider font-semibold mb-1.5">Endurance</div>
            <div class="text-2xl font-bold">85</div>
          </div>
          <div>
            <div class="text-gray-500 text-[9px] uppercase tracking-wider font-semibold mb-1.5">Consistency</div>
            <div class="text-2xl font-bold">88</div>
          </div>
          <div>
            <div class="text-gray-500 text-[9px] uppercase tracking-wider font-semibold mb-1.5">Elevation</div>
            <div class="text-2xl font-bold">81</div>
          </div>
        </div>

        <!-- Stats -->
        <div class="pt-4 border-t border-gray-800 grid grid-cols-3 gap-3 text-center">
          <div>
            <div class="text-xs font-bold mb-0.5">247</div>
            <div class="text-gray-500 text-[9px] uppercase tracking-wider">Runs</div>
          </div>
          <div>
            <div class="text-xs font-bold mb-0.5">1,842km</div>
            <div class="text-gray-500 text-[9px] uppercase tracking-wider">Distance</div>
          </div>
          <div>
            <div class="text-xs font-bold mb-0.5">4:32/km</div>
            <div class="text-gray-500 text-[9px] uppercase tracking-wider">Avg Pace</div>
          </div>
        </div>
      </div>

      <!-- Runscore Branding -->
      <div class="text-center">
        <div class="text-gray-600 text-[10px] font-semibold tracking-wider">RUNSCORE</div>
      </div>
    </div>
    
    <!-- Home Indicator -->
    <div class="absolute bottom-1 left-1/2 -translate-x-1/2 w-32 h-1 bg-white rounded-full opacity-20"></div>
  </div>
</div>

