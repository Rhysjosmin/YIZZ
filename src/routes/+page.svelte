<script>
	import AlternateEmail from '../components/icons/alternate-email.svelte';
	import Github from '../components/icons/github.svelte';
	import XTwitter from '../components/icons/x-twitter.svelte';
</script>

<div class="relative z-10 p-8 md:p-12 md:pt-4 md:px-24">
	<h1 class="text-5xl font-bold lg:text-7xl lg:w-5/6">
		Elevate Your Brand with Stunning Animated Graphics
	</h1>
	<p class="mt-4 text-xl lg:w-1/2">
		Looking for top-tier animated visuals? Contact us today, and we'll craft the perfect graphics to
		enhance your brand's impact.
	</p>
</div>

<div class="fixed bottom-0 left-0 right-0 z-50 h-40 ">
	<div
		class="inset-x-0 bottom-0 z-20 flex-1 h-48 p-6 border-t shadow-xl bg-gradient-to-tr from-stone-950 to-neutral-900/60 backdrop-blur-3xl md:border-x border-neutral-500/20 px-7 md:inset-x-24 rounded-t-3xl"
	>
		<h1 class="text-3xl font-bold">About Me</h1>
		<p class="mt-1 md:w-1/2">
			Im a professional yizzlers out here just trying to make amazing graphics and having fun
		</p>
		<div class="absolute flex gap-4 text-2xl text-white/60 top-6 right-7">
			<a class="hover:text-white" href="https://github.com/Rhysjomdin">
				<Github />
			</a>
			<a class="hover:text-white" href="mailto:rod.rhys20031@gmail.com">
				<AlternateEmail />
			</a>
			<a class="hover:text-white" href="https://x.com/Rhysjomdin">
				<XTwitter />
			</a>
		</div>
	</div>
</div>

<img
	alt="background"
	class="absolute z-[1] inset-0 h-full w-full object-cover"
	src="/gradient.png"
/>
<video class="absolute inset-0 z-0 object-cover w-full h-full" src="/V1.mp4" muted autoplay loop />
