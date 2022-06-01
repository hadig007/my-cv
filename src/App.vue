<template>
  <Home_ui />
  <Nav_ui />
</template>

<script>
import Home_ui from './components/home/home_ui.vue';
import Nav_ui from './components/nav_ui.vue';
export default {
  components: { Home_ui, Nav_ui },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Jost:wght@300&display=swap');
body {
  font-family: 'Jost', sans-serif;
  background-color: #7DE0FF;
}
</style>
