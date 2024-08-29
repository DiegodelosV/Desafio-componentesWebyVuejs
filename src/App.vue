<script>
import carnet from './components/carnet.vue'; //se importa el componente carnet
export default {
  name: 'app',
  components: {
    carnet
  }

}
</script>
<template>
<!-- muestra el contenido del componente carnet en el template -->
  <carnet /> 
</template>