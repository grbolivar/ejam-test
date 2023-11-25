<script setup lang="ts">
import Header from './components/Header.vue'
import Header2 from './components/Header2.vue'
import Footer from './components/Footer.vue'
import OrderPage from './pages/Order/index.vue'

Header
Header2
Footer
OrderPage
</script>

<template lang="pug">
Header
.canvas
  Header2
  OrderPage
Footer
</template>


<style lang="scss" scoped>
.canvas {
  max-width: 1280px;
  margin: 0 auto;
}
</style>
