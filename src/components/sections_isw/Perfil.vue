<template>
  <div class="my-2">
    <InfoPerfil class="mt-5" id="perfil"/>
    <History class="mb-5" />
    <Galeria class="mb-5" id="Galeria" />
  </div>
</template>

<script>
import InfoPerfil from '@/components/sections_isw/perfil_isw/infoperfil.vue'
import History from '@/components/sections_isw/perfil_isw/history.vue'
import Galeria from '@/components/sections_isw/perfil_isw/galeria.vue'

export default {
  components: {
    InfoPerfil,
    History,
    Galeria
  }
}
</script>

<style>

</style>