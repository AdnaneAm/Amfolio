<template>
  <div id="app">
    <Navbar />
    <Hero />
    <Education />
    <Divider type="concave" />
    <Experience />
    <Divider type="convex" />
    <Projects />
    <Divider type="concave" />
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
import Divider from "@/components/Divider";

export default {
  name: "Amfolio",
  components: {
    Navbar,
    Hero,
    Education,
    Experience,
    Projects,
    Contact,
    Divider
  }
};
</script>

<style lang="scss">
body {
  padding: 0;
  margin: 0;
  overflow-x: hidden;
}
</style>
