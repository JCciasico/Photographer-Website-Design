<template>
  <div>
    <div class="intro-section">
      <NavBar/>
      <IntroSection/>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import IntroSection from './components/IntroSection.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    IntroSection
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
  background: linear-gradient(rgba(0, 0, 0, 0.7),rgba(0, 0, 0, 0.75),rgba(0, 0, 0, 0.7)), 
	url("./assets/james-donovan-kFHz9Xh3PPU-unsplash.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
