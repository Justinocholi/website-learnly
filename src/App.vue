<template>
  <div id="app">
    <MainNavbar />
    <HeroSection />
    <FeaturesSection />
    <LearningPersonality />
    <UploadFile />
    <Footer />
  </div>
</template>

<script>
import MainNavbar from './components/MainNavbar.vue'
import HeroSection from './components/HeroSection.vue'
import FeaturesSection from './components/FeaturesSection.vue'
import LearningPersonality from './components/LearningPersonality.vue'
import UploadFile from './components/UploadFile.vue'
import Footer from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    MainNavbar,
    HeroSection,
    FeaturesSection,
    LearningPersonality,
    UploadFile,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>