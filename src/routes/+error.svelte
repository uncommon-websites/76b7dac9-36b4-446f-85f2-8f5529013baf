<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="min-h-screen w-full bg-black text-white flex items-center justify-center">
	<div class="text-center px-4">
		<h1 class="text-6xl md:text-9xl font-bold uppercase mb-4">Error {page.status}</h1>
		<p class="text-xl md:text-2xl text-gray-400 mb-8">{page.error?.message ?? "Something went wrong."}</p>
		<a href="/" class="inline-block bg-white text-black px-8 py-4 font-bold uppercase hover:bg-primary-500 hover:text-white transition-colors">Go back home</a>
	</div>
</main>
