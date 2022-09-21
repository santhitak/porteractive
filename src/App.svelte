<script lang="ts">
  import "./app.css";
  import "./assets/fonts/KyivType.css";
  import { Router, Route } from "svelte-routing";
  import Layout from "./lib/Layout.svelte";
  import Home from "./views/Home.svelte";
  import Project from "./views/Project.svelte";
  import About from "./views/About.svelte";
</script>

<Router>
  <Layout>
    <Route path="/">
      <Home />
    </Route>
    <Route path="/project">
      <Project />
    </Route>
    <Route path="/about">
      <About />
    </Route>
  </Layout>
</Router>
