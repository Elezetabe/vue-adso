<template>
  <div class="login">
    <h1>¡Bienvenido!</h1>
    <h4>Correo Electrónico</h4>
    <input type="email" name="E-mail" id="email" />
    <h4>Contraseña</h4>
    <input type="password" name="Contraseña" id="" />
    <br />
    <br />
    <button>Iniciar sesión</button>
    <br />
    <router-link to="/reset-password">¿Olvidaste la contraseña?</router-link>
    <br />
    <router-link to="/register">¿No estás registrado? Regístrate.</router-link>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
