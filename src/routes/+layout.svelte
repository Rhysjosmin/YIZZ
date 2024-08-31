<script>
	import '../app.css';
	import Nav from '../components/nav.svelte';
</script>

<body class="text-white bg-stone-950 font-rubik ">
	<main class="h-screen">
    <Nav/>
	<slot />
	</main>
</body>
