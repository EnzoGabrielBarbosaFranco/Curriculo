<template>
  <div class="home">
    <EscopoRetangulo />
  </div>
</template>

<script>
import EscopoRetangulo from "@/components/EscopoRetangulo.vue";


export default {
  name: 'App',
  components: {
    EscopoRetangulo,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
