<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <barraLateral />

    </div>
    <div class="column is-three-quarter">
      <Formulario_Principal />
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import barraLateral from './components/barraLateral.vue';
import Formulario_Principal from './components/Formulario_Principal.vue';



export default defineComponent({
  name: 'App',
  components: {
    barraLateral,
    Formulario_Principal
  }

});
</script>

<style>

</style>
