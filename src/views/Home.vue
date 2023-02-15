<template>
  <div class="home">
    <index></index>
    <Carrusel></Carrusel>
  </div>
</template>

<script>
// @ is an alias to /src
import index from '@/components/index.vue'
import Carrusel from '../components/Carrusel'

export default {
  name: 'Home',
  components: {
    index, Carrusel
  }
}
</script>


