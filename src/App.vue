<template>
  <div id="app">
    <HeaderTop />
    <!-- <SpinningIcon /> -->
    <router-view />
  </div>
</template>

<script>
import SpinningIcon from './components/icons/SpinningIcon.vue'
import HeaderTop from './components/layout/Header.vue'

export default {
  name: 'App',
  components: {
    HeaderTop,
    SpinningIcon
  }
}
</script>

<style></style>
