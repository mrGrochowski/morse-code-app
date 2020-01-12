<template>
  <div class="home">
    <LandingPage />
    <router-link to="/game-view">Zagraj</router-link>
  </div>
</template>

<script>
// @ is an alias to /src
import LandingPage from '@/components/LandingPage.vue'

export default {
  name: 'home',
  components: {
    LandingPage
  }
}
</script>
