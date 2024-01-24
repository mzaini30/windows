<script>
  import Router from "svelte-spa-router";
  import Gerbang from "./kunci/src/Gerbang.svelte";

  const routes = {};
</script>

<Gerbang namaAplikasi="">
  <Router {routes} />
</Gerbang>
