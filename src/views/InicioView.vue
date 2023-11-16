<template>
  <div>
    <div>
      <NavComp/>
    </div>
    <div class="pt-5">
      <h1>Catálogo Digital</h1>
      <p>Catálogo de Malhas do Sul de Minas</p>
    </div>
  </div>
</template>

<script>
// @ alias para /src
import InicioComp from '@/components/InicioComp.vue'
import NavComp from '@/components/NavComp.vue'

export default {
  name: 'InicioView',
  components: {
    InicioComp,
    NavComp,
  }
}
</script>
<!-- "scoped" CSS apenas para este compomente -->
<style scoped>
img{
  width: 200px;
}
</style>
