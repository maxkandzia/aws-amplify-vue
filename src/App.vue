<template>
  <div>
    <HeroSection></HeroSection>
    <AboutMe></AboutMe>
    <badges-section></badges-section>
    <FeatureSection></FeatureSection>
  </div>
</template>

<script>
import HeroSection from "./components/HeroSection.vue";
import FeatureSection from "./components/FeatureSections.vue";
import AboutMe from "./components/AboutMe.vue";
import BadgesSection from "./components/BadgesSection.vue";

export default {
  name: "App",
  components: {
    HeroSection,
    AboutMe,
    FeatureSection,
    BadgesSection,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
