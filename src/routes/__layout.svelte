<svelte:head>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<meta property="og:type" content="article">
	<meta name="theme-color" content="#ffffff" />
	<meta property="og:url" content="https://petergriffingang.github.io">
	<link href="https://cdn.jsdelivr.net/npm/@mdi/font@5.9.55/css/materialdesignicons.min.css" rel="stylesheet">

	<link rel="icon" type="image/jpg" href="/favicon.png"/>

	<meta property="og:title" content="PGBR: Official Webpage">
	<meta name="description" content="PGBR: Official Webpage">
	<meta name="author" content="PGBR Members">
</svelte:head>

<script>
	import "../app.postcss";
	import Header from "$lib/Header.svelte";
	import Footer from "$lib/Footer.svelte";
</script>

<Header />
<slot/>
<Footer />