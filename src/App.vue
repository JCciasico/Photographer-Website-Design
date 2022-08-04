<template>
  <div>
    <div class="intro-section">
      <NavBar/>
      <IntroSection/>
    </div>
    <div class="welcome-section">
      <WelcomeSection/>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import IntroSection from './components/IntroSection.vue';
import WelcomeSection from './components/WelcomeSection.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    IntroSection,
    WelcomeSection
}
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.intro-section{
  background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)), 
	url("./assets/alex-knight-958bi4L1N9s-unsplash.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
