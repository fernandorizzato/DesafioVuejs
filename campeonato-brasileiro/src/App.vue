<template>
  <v-app>
    <v-main>
      <tabelaBrasileiro/>
    </v-main>
  </v-app>
</template>

<script>
import tabelaBrasileiro from './components/tabelaBrasileiro.vue';

export default {
  name: 'App',

  components: {
    tabelaBrasileiro
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>

</style>
