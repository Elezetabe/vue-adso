<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
        <ul class="navbar-nav">
          <RouterLink to="/inicio">Inicio</RouterLink>
          <RouterLink to="/contact">Contact</RouterLink>
        </ul>
      </div>
  </nav>
</template>

<style>
  .container-fluid {
    display: flex;
    background-color: greenyellow;
    padding: 10px 15px;
  }
</style>
