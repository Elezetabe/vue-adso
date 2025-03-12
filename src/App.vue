<script setup lang="ts">
import { RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue';
import NavbarLayout from './components/layouts/NavbarLayout.vue';
</script>

<template>
  <NavbarLayout />
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="¡Bienvenido a Softly!" />

    </div>
  </header>
  <RouterView />
</template>

<style>
  .wrapper {
    display: flex;
    color: white;
  }
</style>
