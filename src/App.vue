<template>
  <v-main>
    <Navigation />
    <Intro />
    <About />
    <Projects />
    <Footer />
  </v-main>
</template>

<script>
import Navigation from "./components/Navigation";
import Intro from "./components/Intro";
import About from "./components/About";
import Projects from "./components/Projects";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    Navigation,
    Intro,
    About,
    Projects,
    Footer
  },

  data: () => ({
    //
  })
};
</script>

<style scoped>
</style>
