<template>
  <div class="container">
    <div class="about">
      <h1 class="title">Desafío: Sistema de Inventario Otto Klaus</h1>
      <b-message type="is-success">
        <p>
          Sitio creado por <b>Carolina González</b> para módulo final curso de Desarrollo Front End de <b>Desafío Latam</b>.
        </p>
      </b-message>
      <b-message title="Datos de prueba" aria-close-label="Close message">
            <b>Usuario:</b> c.gonzalezcontrera@gmail.com | <b>Contraseña:</b> 123456
      </b-message>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'About',
}
</script>
<style lang="scss">
.about{
   padding: 80px 0;
   width: 80%;
   margin: 0 auto;
   &__image{
      width: 50%;
      margin: 0 auto;
   }
}
  
</style>