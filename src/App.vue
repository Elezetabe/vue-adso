<script lang="ts">
import NavbarLayout from "@/components/NavbarLayout.vue";

export default {
  components: {
    NavbarLayout, // Importamos el Navbar para que sea fijo
  },
};
</script>


<template>
  <v-app>
    <NavbarLayout />  <!-- El Navbar será fijo en toda la app -->
    <v-main>
      <router-view />  <!-- Aquí se cargarán las páginas dinámicamente -->
    </v-main>
  </v-app>
</template>
