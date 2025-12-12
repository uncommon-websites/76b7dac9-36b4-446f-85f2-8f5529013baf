<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import Button from '$lib/components/Button.svelte';
  import Strava from '$lib/components/icons/Strava.svelte';
  import TrophyIcon from '$lib/components/icons/TrophyIcon.svelte';
  import ChartIcon from '$lib/components/icons/ChartIcon.svelte';
  import RunnerIcon from '$lib/components/icons/RunnerIcon.svelte';
  import Laurel from '$lib/components/icons/Laurel.svelte';
  import PhoneUI from '$lib/components/PhoneUI.svelte';
</script>

<svelte:head>
  <title>Runscore - Transform Running Data into Competitive Ratings</title>
  <meta name="description" content="Runscore analyzes your running performance across six dimensions to create competitive ratings and global leaderboard rankings. Connect with Strava and get your shareable rating card." />
  <meta property="og:title" content="Runscore - Transform Running Data into Competitive Ratings" />
  <meta property="og:description" content="Multi-dimensional performance analysis for competitive runners. Transform your Strava data into meaningful benchmarks and global rankings." />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Runscore - Transform Running Data into Competitive Ratings" />
  <meta name="twitter:description" content="Multi-dimensional performance analysis for competitive runners. Transform your Strava data into meaningful benchmarks and global rankings." />
</svelte:head>

<div class="min-h-screen bg-white text-black font-sans selection:bg-gray-200">
  <Header />

  <main class="flex flex-col items-center w-full">
    <!-- Hero Section -->
    <section class="flex flex-col items-center text-center pt-10 pb-12 px-4 max-w-4xl mx-auto">
      <h2 class="text-sm font-semibold mb-6 uppercase tracking-wider text-gray-400">Performance Analytics</h2>
      
      <h1 class="text-5xl md:text-7xl font-bold tracking-tight leading-[1.1] mb-10">
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>Transform your</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-gray-100 rounded-2xl align-middle mx-1">
            <RunnerIcon className="w-6 h-6 md:w-8 md:h-8" />
          </span>
        </div>
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>running data into</span>
        </div>
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-gray-100 rounded-2xl align-middle mx-1">
            <ChartIcon className="w-6 h-6 md:w-8 md:h-8" />
          </span>
          <span>competitive</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-gray-100 rounded-2xl align-middle mx-1">
            <TrophyIcon className="w-6 h-6 md:w-8 md:h-8" />
          </span>
          <span>ratings</span>
        </div>
      </h1>

      <div class="mb-12">
        <Button>
          <Strava className="w-5 h-5" />
          <span class="text-base">Connect with Strava</span>
        </Button>
      </div>

      <!-- Awards/Featured -->
      <div class="flex flex-wrap justify-center gap-8 md:gap-16 text-gray-400 text-[10px] md:text-xs font-medium uppercase tracking-widest">
        <div class="flex items-center gap-2">
          <Laurel className="w-6 h-12 md:w-8 md:h-16 scale-x-[-1]" />
          <div class="flex flex-col items-center leading-tight">
            <span class="text-[8px] md:text-[10px] text-gray-300 mb-0.5">Multi-dimensional</span>
            <span class="font-bold text-gray-300">Performance Analysis</span>
          </div>
          <Laurel className="w-6 h-12 md:w-8 md:h-16" />
        </div>
        <div class="flex items-center gap-2">
          <Laurel className="w-6 h-12 md:w-8 md:h-16 scale-x-[-1]" />
          <div class="flex flex-col items-center leading-tight">
            <span class="text-[8px] md:text-[10px] text-gray-300 mb-0.5">Competitive</span>
            <span class="font-bold text-gray-300">Global Leaderboards</span>
          </div>
          <Laurel className="w-6 h-12 md:w-8 md:h-16" />
        </div>
      </div>
    </section>

    <!-- Phone Showcase -->
    <section class="w-full max-w-[1000px] px-4 mb-24 relative flex justify-center">
      <!-- Background glow/shadow simulation -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-gray-100/50 rounded-full blur-3xl -z-10"></div>
      
      <!-- Phone Container -->
      <!-- Since we don't have the hand image, we'll present the phone UI in a nice frame -->
      <div class="relative w-[300px] md:w-[340px] h-[680px] md:h-[720px] transition-transform hover:scale-[1.02] duration-500">
        <PhoneUI />
      </div>
    </section>

    <!-- Features Text -->
    <section class="max-w-4xl mx-auto px-6 pb-32 space-y-24 text-center">
      <div class="space-y-6">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Runscore analyzes six performance dimensions—pace, endurance, consistency, elevation gain, progress, and engagement—to create your competitive rating
        </h3>
      </div>

      <div class="space-y-6">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Seamlessly integrated with Strava, Runscore transforms your running data into shareable rating cards with tier rankings and global leaderboard positions
        </h3>
      </div>

      <div class="space-y-10">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          From weekend joggers to competitive athletes, Runscore provides meaningful benchmarks beyond personal records—status-driven ratings that inspire improvement
        </h3>
        
        <div class="pt-4">
          <Button>
            <Strava className="w-5 h-5" />
            <span class="text-base">Connect with Strava</span>
          </Button>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="w-full py-12 flex flex-col items-center gap-6 text-center border-t border-gray-100 mt-auto">
      <div class="flex items-center gap-2">
        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <mask
            id="mask0_footer"
            style="mask-type:luminance"
            maskUnits="userSpaceOnUse"
            x="3"
            y="1"
            width="18"
            height="22"
          >
            <path d="M3 1H20.7794V22.3353H3V1Z" fill="white" />
          </mask>
          <g mask="url(#mask0_footer)">
            <path
              d="M14.1516 3.24638L12.4034 2.77795L10.9302 8.27606L9.60014 3.31233L7.85194 3.78076L9.28896 9.14369L5.70969 5.56443L4.42993 6.84419L8.35594 10.7702L3.46671 9.46017L2.99829 11.2083L8.34038 12.6397C8.27922 12.3759 8.24687 12.1011 8.24687 11.8187C8.24687 9.81953 9.86746 8.19894 11.8666 8.19894C13.8657 8.19894 15.4863 9.81953 15.4863 11.8187C15.4863 12.0993 15.4544 12.3724 15.394 12.6347L20.2489 13.9356L20.7173 12.1874L15.354 10.7503L20.2436 9.44012L19.7751 7.69196L14.412 9.12898L17.9913 5.54972L16.7115 4.26998L12.84 8.14156L14.1516 3.24638Z"
              fill="currentColor"
            />
            <path
              d="M15.3888 12.655C15.2389 13.2887 14.9225 13.8579 14.4883 14.314L18.0056 17.8313L19.2853 16.5515L15.3888 12.655Z"
              fill="currentColor"
            />
            <path
              d="M14.4529 14.3508C14.0135 14.7996 13.4582 15.1345 12.8354 15.3071L14.1153 20.0836L15.8635 19.6151L14.4529 14.3508Z"
              fill="currentColor"
            />
            <path
              d="M12.7701 15.3246C12.4812 15.3989 12.1784 15.4384 11.8663 15.4384C11.5319 15.4384 11.2082 15.393 10.9008 15.3082L9.61981 20.089L11.368 20.5574L12.7701 15.3246Z"
              fill="currentColor"
            />
            <path
              d="M10.839 15.2905C10.2258 15.1093 9.68038 14.7702 9.24994 14.3201L5.72406 17.8459L7.00382 19.1257L10.839 15.2905Z"
              fill="currentColor"
            />
            <path
              d="M9.22084 14.2889C8.79778 13.836 8.48962 13.2743 8.34294 12.6505L3.47211 13.9556L3.94053 15.7038L9.22084 14.2889Z"
              fill="currentColor"
            />
          </g>
        </svg>
        <div class="font-bold text-xl tracking-tight text-gray-200">Runscore</div>
      </div>
      <div class="flex flex-wrap justify-center gap-4 text-xs text-gray-400 font-medium">
        <a href="https://www.strava.com" target="_blank" rel="noopener noreferrer" class="hover:text-black transition-colors">Strava Integration</a>
        <span>•</span>
        <a href="https://instagram.com/itstimwijaya" target="_blank" rel="noopener noreferrer" class="hover:text-black transition-colors">Instagram</a>
        <span>•</span>
        <a href="#" class="hover:text-black transition-colors">Contact</a>
        <span>•</span>
        <a href="#" class="hover:text-black transition-colors">Privacy Policy</a>
      </div>
      <div class="text-[10px] text-gray-300">
        Built with passion in Jakarta, Indonesia
      </div>
    </footer>
  </main>
</div>


