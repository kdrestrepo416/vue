<template>
    <div class="home">
     
      <EjemploVue/>
      <AcademicoVue/>
  
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import EjemploVue from '@/components/Ejemplo.vue'
  import AcademicoVue from '@/components/Academico.vue';

  export default {
    name: 'VistaView',
    components: {
      EjemploVue,
      AcademicoVue,
       
    }
  }


  
  </script>
  