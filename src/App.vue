<template>
  <div>
    <div class="intro-section">
      <NavBar/>
      <IntroSection/>
    </div>
    <div class="welcome-section">
      <WelcomeSection/>
      <ArtSection/>
    </div>
    <div class="services-section">
      <ServicesSection/>
    </div>
    <div class="feature-section">
      <FeatureSection/>
    </div>
    <div class="project-section">
      <ProjectSection/>
    </div>
    <footer>
      <div class="footer-section">
        <FooterSection/>
      </div>
      <div class="social-section">
        <SocialFooter/>
      </div>
    </footer>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import IntroSection from './components/IntroSection.vue';
import WelcomeSection from './components/WelcomeSection.vue';
import ArtSection from './components/ArtSection.vue';
import ServicesSection from './components/ServicesSection.vue';
import FeatureSection from './components/FeatureSection.vue';
import ProjectSection from './components/ProjectSection.vue';
import FooterSection from './components/FooterSection.vue';
import SocialFooter from './components/SocialFooter.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    IntroSection,
    WelcomeSection,
    ArtSection,
    ServicesSection,
    FeatureSection,
    ProjectSection,
    FooterSection,
    SocialFooter
}
}
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  overflow: hidden;
}
.intro-section{
  background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)), 
	url("./assets/alex-knight-958bi4L1N9s-unsplash.webp");
  background-repeat: no-repeat;
  background-size: cover;
}
.feature-section{
  background: linear-gradient(rgba(0, 0, 0, 0.4),rgba(0, 0, 0, 0.4),rgba(0, 0, 0, 0.4)), 
	url("./assets/highway-1jpg.webp");
  background-repeat: no-repeat;
  background-size: cover;
}
.footer-section{
  background:  linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)), url("./assets/william-thomas--C8ig94AFBE-unsplash.webp");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
</style>
