<template>
  <div id="app">
    <Navbar />
    <Hero />
    <Education />
    <Experience />
    <Projects />
    <Contact />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
import Hero from "@/components/Hero";
import Education from "@/components/Education";
import Experience from "@/components/Experience";
import Projects from "@/components/Projects";
import Contact from "@/components/Contact";

export default {
  name: "Amfolio",
  components: {
    Navbar,Hero,Education,Experience,Projects,Contact
  }
};
</script>

<style lang="scss">
  body{
    padding:0;
    margin:0;
  }
</style>
