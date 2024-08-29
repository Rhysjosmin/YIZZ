<script>
	import AlternateEmail from '../components/icons/alternate-email.svelte';
	import Github from '../components/icons/github.svelte';
	import XTwitter from '../components/icons/x-twitter.svelte';
</script>

<div class="relative z-10 md:p-12 md:pt-4 md:px-24 p-8 md:h-full">
	<h1 class="lg:text-7xl text-6xl lg:w-5/6 font-bold">
		Elevate Your Brand with Stunning Animated Graphics
	</h1>
	<p class="text-xl mt-4 lg:w-1/2">
		Looking for top-tier animated visuals? Contact us today, and we'll craft the perfect graphics to
		enhance your brand's impact.
	</p>
</div>

<div class="w-full  relative z-10 h-40  bottom-0">
	<div
		class="bg-gradient-to-tr from-stone-950 to-neutral-900/60 backdrop-blur-3xl shadow-xl border-t md:border-x border-neutral-500/20 p-6 px-7 z-20 h-48 md:inset-x-24 inset-x-0 flex-1 rounded-t-3xl  bottom-0"
	>
		<h1 class="text-3xl font-bold">About Me</h1>
		<p class="md:w-1/2 mt-1">
			Im a professional yizzlers out here just trying to make amazing graphics and having fun
		</p>
		<div class="flex gap-4 text-2xl text-white/60 absolute top-6 right-7">
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
<video class="absolute z-0 inset-0 h-full w-full object-cover" src="/V1.mp4" muted autoplay loop />
