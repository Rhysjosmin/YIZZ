<script>
	import Close from './icons/close.svelte';
	import Menu from './icons/menu.svelte';
	import NavLinks from './nav-links.svelte';
	let menuOpen = false;
</script>

<div class="relative z-[100] flex items-center p-8 md:p-12 md:px-24 w-full">
	<h1 class="z-10 text-3xl font-black text-white font-rowdies">YIZZ</h1>
	<div class="flex-1 hidden gap-8 ml-12 text-white lg:flex font-rubik">
		<NavLinks />
	</div>
	<button
		class="hidden p-3 px-6 font-bold text-black bg-white rounded-full lg:flex font-rubik hover:bg-stone-100"
	>
		Contact Me
	</button>
	<button on:click={() => (menuOpen = !menuOpen)} class="z-10 ml-auto rounded-full group lg:hidden">
		{#if !menuOpen}
			<Menu class="text-3xl group-hover:text-white text-white/80" />
		{:else}
			<Close class="text-3xl group-hover:text-white text-white/80" />
		{/if}
	</button>

	<div
		class={`absolute inset-0  w-full h-screen overflow-hidden  z-[5] ${menuOpen ? 'backdrop-blur bg-neutral-950/80' : 'backdrop-blur-0 bg-neutral-950/0 pointer-events-none'} transition-all duration-500 `}
	>
		<div
			class={`${menuOpen ? 'size-[48rem] pt-72 pl-56 md:pl-72 md:pt-80 shadow-2xl ' : ' size-0 '} transition-all ease-in-out duration-300 lg:hidden bg-gradient-to-br from-neutral-950 to-neutral-900 border border-white/5 rounded-full  absolute -left-[12rem] -top-[12rem] `}
		>
			<div
				class={`flex z-20 flex-col gap-2 md:text-xl md:gap-4 ${menuOpen ? 'opacity-100' : 'opacity-0'} delay-300 duration-700 transition`}
			>
				<NavLinks />
			</div>
		</div>
	</div>
</div>
