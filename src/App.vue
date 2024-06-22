<template>
  <div id="app">
    <HeaderTop />
    <router-view />
  </div>
</template>

<script>
import HeaderTop from './components/layout/Header.vue'

export default {
  name: 'App',
  components: {
    HeaderTop
  }
}
</script>

<style></style>
