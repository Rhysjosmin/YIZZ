<script>
	import '../app.css';
	import Nav from '../components/nav.svelte';
</script>

<body class="bg-stone-950 min-h-screen text-white font-rubik ">
	<main class=" relative  ">
    <Nav/>
	<slot />
	</main>
</body>
