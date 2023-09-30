<script>
  import "../app.css";
  import Header from "../lib/Header.svelte";
  import Cards from "../lib/Cards.svelte";
  import Services from "../lib/Services.svelte";
  import Blogs from "../lib/Blogs.svelte";
  import Stats from "../lib/Stats.svelte";
  import Testimonals from "../lib/Testimonals.svelte";
  import Footer from "../lib/Footer.svelte";
</script>

<div class="app w-[100vw] bg-base-100" data-theme="light">
  <Header />
  <Cards />
  <Services />
  <Blogs />
  <Stats />
  <Testimonals />
  <Footer />
</div>
