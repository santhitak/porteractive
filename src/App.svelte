<script lang="ts">
  import "./app.css";
  import "./assets/fonts/KyivType.css";
  import { Router, Route } from "svelte-routing";
  import Layout from "./lib/Layout.svelte";
  import Home from "./views/Home.svelte";
</script>

<Router>
  <Layout>
    <Route path="/">
      <Home />
    </Route>
  </Layout>
</Router>
