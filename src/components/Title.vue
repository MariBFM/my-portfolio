<script setup>

</script>

<template>

  <div class="h-screen flex flex-col justify-center ">
    <!-- Añadir animación de abajo hacia arriba -->
    <div class="divbg relative">
      <h1 class="font-bold">Mari Flores</h1>
      <h2>Desarrolladora Web Junior</h2>
    </div>
    <!-- Agregar animación de aparecer -->
    <div class="text-white font-thin">
      <p>Apasionada de la tecnología y del desarrollo Front-End, espacios en los que siempre me he encontrado
      cómoda. Tengo el deseo de aprender y saber más, e intento profundizar en los conocimientos.
      Me gusta verificar antes de actuar, intentando pensar en los diferentes factores que afectan a cada
      situación. Ante cualquier conflicto intento resolverlo reparando lo que no funciona y aportando
      soluciones.
      </p>
      <ul>
        <li><a href="https://www.linkedin.com/in/marignacia-flores-munoz/"><i class="fab fa-linkedin"></i> MarignaciaFloresMuñoz</a></li>
        <li><a href="https://github.com/MariBFM"><i class="fab fa-github"></i> MariBFM</a></li>
        <li><a href="mailto:marignacia.flores@gmail.com"><i class="fas fa-at"></i> marignacia.flores@gmail.com</a></li>
      </ul>
    </div>

  </div>
  
</template>

<style scoped>
  .divbg{
    background: linear-gradient(180deg, rgba(250,68,140,1) 0%, rgba(254,200,89,1) 33%, rgba(67,181,160,1) 67%, rgba(73,29,136,1) 100%) fixed;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    color: white;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }
  h1{
    font-size: 6rem; 
    text-shadow: 2px  #ffffff;
  }
  h2{
    font-size: 3rem;
  }
</style>
