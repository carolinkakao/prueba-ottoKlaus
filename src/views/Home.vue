<template>
  <div class="container">
    <div class="home">
        <h1  class="title home_title has-text-centered "> Sistema de Inventario Juguetería</h1>      
        <div class="home__image">
          <img class="logo" alt="logo" src="../assets/logo.png">
        </div>

        <div class="notification is-danger my-5">
          <p>Primero debes iniciar sesión como administrador para ver el contenido en inventario.</p> 
        </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home',
}
</script>
<style lang="scss">
.home{
   padding: 80px 0;
   width: 80%;
   margin: 0 auto;
   &__image{
      width: 50%;
      margin: 0 auto;
      img {
        -webkit-filter: drop-shadow(5px 5px 5px rgba(0,0,0,0.2));
        filter: drop-shadow(5px 15px 15px rgba(0,0,0,0.2));
      }
   }
}


  
</style>
