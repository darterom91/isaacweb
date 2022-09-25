<template>
  <div class="section bg-dark">
    <Carrusel class="w-100" />
    <Perfil />
    <Contact />
  </div>
</template>

<script>

import Carrusel from '@/components/sections_isw/carrusel.vue'
import Perfil from '@/components/sections_isw/perfil.vue'
import Contact from '@/components/sections_isw/contact.vue'
export default {
  components: {
    Carrusel,
    Perfil,
    Contact
  }
};
</script>

<style scoped></style>