<template>
  <div class="game-view">
    GAME VIEW {{vTitle}} 
  </div>
</template>

<script>

import { computed } from '@vue/composition-api';

export default {
  props: {
    msg: String
  },
  setup(props,context) {
    const vTitle = computed(() => '-' + props.msg + '-');

    return {
      vTitle,
    };
  }
};
</script>

<style scoped lang="scss">

</style>
