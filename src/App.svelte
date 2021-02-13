<!-- App.svelte -->
<script>
  import { Router } from '@roxi/routify';
  import { routes } from "./.routify/routes";
</script>

<svelte:head>
	<link rel="stylesheet" href="./dist/main.css">
</svelte:head>

<Router {routes} />