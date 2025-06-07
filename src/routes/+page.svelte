<script lang="ts">
	import type { Config } from '@sveltejs/adapter-vercel';

	export const config: Config = {
		runtime: 'edge'
	};
</script>

<svelte:head>
	<title>Ludvig Bartholdsson</title>
	<meta name="description" content="Learn more about Ludvig Bartholdsson" />
</svelte:head>

<div class="container mx-auto flex min-h-screen w-full flex-col items-center justify-center">
	<div class="flex w-full flex-col gap-3 lg:max-w-lg xl:max-w-3xl">
		<div class="w-full">
			<h1 class="scroll-m-20 text-left text-3xl font-extrabold tracking-tight">
				Ludvig Bartholdsson
			</h1>
		</div>
		<div class="flex w-full flex-col gap-6 border-2 border-[#2E2E2E] bg-[#FFFFFF0F] p-4">
			<div class="info">
				<h3 class="header">Links</h3>
				<div class="flex flex-row flex-wrap items-center gap-3">
					<a
						class="link"
						target="_blank"
						rel="noopener noreferrer"
						href="https://x.com/LudvigBarthold1">[X]</a
					>
					<a
						class="link"
						target="_blank"
						rel="noopener noreferrer"
						href="https://github.com/LudvigBartholdsson">[github]</a
					>
					<a
						class="link"
						target="_blank"
						rel="noopener noreferrer"
						href="https://www.linkedin.com/in/ludvigbartholdsson">[linkedin]</a
					>
					<a
						class="link"
						target="_blank"
						rel="noopener noreferrer"
						href="mailto:ludvig@telefonid.se">[email]</a
					>
				</div>
			</div>
			<div class="info">
				<h3 class="header">Interests</h3>
				<div class="flex flex-row flex-wrap items-center gap-3">
					<p class="text">Coding</p>
					<p class="text">Learning</p>
					<p class="text">Building stuff :)</p>
				</div>
			</div>
			<div class="info">
				<h3 class="header">Companies</h3>
				<div class="flex flex-row flex-wrap items-center gap-3">
					<a class="link" target="_blank" rel="noopener noreferrer" href="https://csmiddler.com"
						>[CSMiddler]</a
					>
					<a
						class="link !text-[#FFAF00]"
						target="_blank"
						rel="noopener noreferrer"
						href="https://telefonid.se">[TelefonID]</a
					>
				</div>
			</div>
		</div>
		<div class="flex w-full flex-col border-2 border-[#2E2E2E] bg-[#FFFFFF0F] p-4">
			<h3 class="header sm:!mb-4">News about me</h3>
			<div class="flex flex-col gap-6">
				<a
					class="link"
					target="_blank"
					rel="noopener noreferrer"
					href="https://www.di.se/debatt/sa-ateruppvacks-det-nordiska-techundret/"
					>“How the Nordic tech miracle is being revived.” (2025, Swedish)</a
				>
				<a
					class="link"
					target="_blank"
					rel="noopener noreferrer"
					href="https://www.di.se/digital/blev-blast-nu-rensar-han-marknaden-med-miljardaren/"
					>“Got swindled - now he's cleaning up the market with the billionaire.” (2024, Swedish)</a
				>
				<a
					class="link"
					target="_blank"
					rel="noopener noreferrer"
					href="https://www.breakit.se/artikel/39349/16-arige-ludvig-bartholdsson-blev-lurad-pa-pengar-startade-csmiddler-och-fick-tungviktare-att-investerare"
					>“16-year-old Ludvig Bartholdsson was scammed - now he starts CSMiddler and got
					heavyweight investors.” (2024, Swedish)</a
				>
			</div>
		</div>
		<div class="flex w-full flex-col border-2 border-[#2E2E2E] bg-[#FFFFFF0F] p-4">
			<h3 class="header sm:!mb-4">Blog posts</h3>
			<div>
				<p class="text">I'm trying to start writing...</p>
			</div>
		</div>
	</div>
</div>

<style lang="postcss">
	.header {
		@apply mb-2 text-xl font-semibold tracking-tight sm:mb-0;
	}

	.info {
		@apply flex w-full flex-col justify-between sm:flex-row sm:items-center;
	}

	.text {
		@apply text-[#7D7D7D];
	}

	.link {
		@apply text-[#7D7D7D] hover:underline;
	}
</style>
