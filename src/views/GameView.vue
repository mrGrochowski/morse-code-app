<template>
  <div class="home">
    <gameContainer :msg="'dobry'"/>
  </div>
</template>

<script>
// @ is an alias to /src
import gameContainer from '@/components/gameContainer.vue'

export default {
  name: 'home',
  components: {
    gameContainer
  }
}
</script>
