<template>

  <NavBar />
  <category />
  <PiePagina />
</template>

<script setup>

import NavBar from '@/components/LayoutComponents/NavBar.vue';
import category from '@/components/LayoutComponents/CatalogoProductos.vue';
import PiePagina from '@/components/LayoutComponents/PieDePagina.vue';
</script>


<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
  
}

.navbar {

  width: 90vw;

}
.category {

width: 60vw;

}
</style>