<script lang="ts">
	const e = Math.random() < 0.5;
</script>

{#if e}
<main class="relative h-dvh w-full overflow-hidden">
    <img
        class="absolute inset-0 block h-full max-h-dvh w-full object-cover object-[center_0%]"
        src="/Acknowledging_That_Pain_T_upscaled.jpeg"
        alt="an shiraishi"
    />

	<section
		class="absolute top-[calc(50%+0rem)] right-[clamp(1.5rem,5vw,5rem)] left-[clamp(1.5rem,5vw,5rem)] z-10 flex max-w-xl -translate-y-1/2 flex-col gap-3 text-black"
		aria-labelledby="hero-title"
	>
		<h1 id="hero-title" class="font-mono font-bold tracking-tighter text-4xl sm:text-6xl">technodot</h1>

		<p class="max-w-lg font-content text-sm leading-6 text-black sm:text-base">
			proud tsundere<br>
			if you couldn't tell I really like An Shiraishi
		</p>

		<div class="mt-2 flex flex-col gap-4 sm:flex-row">
			<a href="https://github.com/TechDudie" target="_blank" rel="noopener noreferrer"
				class="relative inline-flex cursor-pointer items-center justify-center overflow-hidden border border-black bg-black px-5 py-3 text-sm text-white after:pointer-events-none after:absolute after:inset-x-0 after:bottom-0 after:h-[1px] after:origin-left after:scale-x-0 after:bg-white after:transition-transform after:duration-300 after:ease-out after:content-[''] hover:after:scale-x-100 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-black focus-visible:after:scale-x-100 motion-reduce:after:transition-none"
			>
				view source
			</a>
			<a href="https://github.com/TechDudie" target="_blank" rel="noopener noreferrer"
				class="group relative inline-flex cursor-pointer items-center justify-center overflow-hidden border border-transparent px-5 py-3 text-sm text-black after:pointer-events-none after:absolute after:inset-x-0 after:bottom-0 after:h-[2px] after:origin-left after:scale-x-0 after:bg-black after:transition-transform after:duration-300 after:ease-out after:content-[''] hover:after:scale-x-100 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-black focus-visible:after:scale-x-100 motion-reduce:after:transition-none"
			>
				read some yap
			</a>
		</div>
	</section>
</main>
{:else}
<main class="relative h-dvh w-full overflow-hidden">
    <img
        class="absolute inset-0 block h-full max-h-dvh w-full object-cover object-[center_0%]"
        src="/BBQ_With_Everyone__T_upscaled.webp"
        alt="an shiraishi"
    />

	<section
		class="absolute top-[calc(50%+0rem)] right-[clamp(1.5rem,5vw,5rem)] left-[clamp(1.5rem,5vw,5rem)] z-10 flex max-w-xl -translate-y-1/2 flex-col gap-3 text-white"
		aria-labelledby="hero-title"
	>
		<h1 id="hero-title" class="font-mono font-bold tracking-tighter text-4xl sm:text-6xl">technodot</h1>

		<p class="max-w-lg font-content text-sm leading-6 text-white sm:text-base">
			proud tsundere<br>
			if you couldn't tell I really like An Shiraishi
		</p>

		<div class="mt-2 flex flex-col gap-4 sm:flex-row">
			<a href="https://github.com/TechDudie" target="_blank" rel="noopener noreferrer"
				class="relative inline-flex cursor-pointer items-center justify-center overflow-hidden border border-white bg-white px-5 py-3 text-sm text-black after:pointer-events-none after:absolute after:inset-x-0 after:bottom-0 after:h-[2px] after:origin-left after:scale-x-0 after:bg-black after:transition-transform after:duration-300 after:ease-out after:content-[''] hover:after:scale-x-100 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white focus-visible:after:scale-x-100 motion-reduce:after:transition-none"
			>
				view source
			</a>
			<a href="https://github.com/TechDudie" target="_blank" rel="noopener noreferrer"
				class="group relative inline-flex cursor-pointer items-center justify-center overflow-hidden border border-transparent px-5 py-3 text-sm text-white after:pointer-events-none after:absolute after:inset-x-0 after:bottom-0 after:h-[1px] after:origin-left after:scale-x-0 after:bg-white after:transition-transform after:duration-300 after:ease-out after:content-[''] hover:after:scale-x-100 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:after:scale-x-100 motion-reduce:after:transition-none"
			>
				read some yap
			</a>
		</div>
	</section>
</main>
{/if}
