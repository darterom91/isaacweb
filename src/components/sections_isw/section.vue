<template>
  <div class="section bg-dark">
    <Carrusel class="w-100" />
    <InfoPerfil />
    <Contact />
  </div>
</template>

<script>

import Carrusel from '@/components/sections_isw/carrusel.vue'
import InfoPerfil from '@/components/sections_isw/infoperfil.vue'
import Contact from '@/components/sections_isw/contact.vue'
export default {
  components: {
    Carrusel,
    InfoPerfil,
    Contact
  }
};
</script>

<style scoped></style>