<template>
  <div class="home">
    <Header> </Header>
    <Hero> </Hero>
    <WomenBanner> </WomenBanner>
    <Instagram> </Instagram>
    <Partner></Partner>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src

import Header from "../components/Header";
import Hero from "../components/Hero";
import WomenBanner from "../components/WomenBanner";
import Instagram from "../components/Instagram";
import Partner from "../components/Partner";
import Footer from "../components/Footer";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    WomenBanner,
    Instagram,
    Partner,
    Footer,
  },
};
</script>
