<script setup>
import { RouterLink, RouterView } from "vue-router";
import PlayerInputVue from "./components/PlayerInput.vue";
</script>

<template>
  <!--  <RouterLink to="/">Home</RouterLink> -->

  <RouterView />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}

@media (hover: hover) {
  
}

@media (min-width: 1024px) {
  body {
    display: flex;
    place-items: center;
  }

  #app {
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding: 0 2rem;
  }
}
</style>
