<script setup lang="ts">
import NavBar from './components/NavBar.vue';
import Flyout from './components/Flyout.vue';
import Cart from './components/Cart.vue';
</script>

<template>
  <NavBar />

  <div class="container">
    <RouterView />
  </div>

  <Flyout>
    <Cart />
  </Flyout>
</template>

<style scoped></style>
