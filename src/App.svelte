<script>
  import Router from "svelte-spa-router";
  import Beranda from "./Beranda.svelte";
  import About from "./About.svelte";
  const routes = {
    "/": Beranda,
    "/about": About,
  };
</script>

<Router {routes} />
