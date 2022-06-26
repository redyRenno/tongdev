<script>
import { RouterLink, RouterView } from 'vue-router'
import LandingPage from "./views/LandingPage.vue"

export default {
  components: {
    LandingPage
  }
}

</script>

<template>

  <LandingPage></LandingPage>

</template>

<style>
@import 'bootstrap/dist/css/bootstrap.min.css';
@import url('./assets/style.css');
@import url('https://fonts.googleapis.com/css2?family=Fredoka+One&family=Poppins:wght@500&display=swap');
</style>
