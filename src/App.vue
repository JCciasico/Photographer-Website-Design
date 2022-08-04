<template>
  <div>
    <div class="intro-section">
      <NavBar/>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';

export default {
  name: 'App',
  components: {
    NavBar
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
  background: url("./assets/manuel-cosentino-n--CMLApjfI-unsplash.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
