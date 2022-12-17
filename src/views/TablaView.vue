<template>
    <div class="home">

      <EjercicioComponentVue/>
      
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import EjercicioComponentVue from '@/components/EjercicioComponent.vue'
  
  export default {
    name: 'TablaView.vue',
    components: {
      EjercicioComponentVue,
   
    }
  }
  </script>