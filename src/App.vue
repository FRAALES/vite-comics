<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  }
}
</script>

<template>
  <HelloWorld msg="Vite + Vue" />
</template>

<style lang="scss">
@use './styles/partials/variables';
@use './styles/general.scss' as *;
</style>

