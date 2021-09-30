<template>
  <v-app>
    <AppTopBar />
    <v-main>
      <v-container></v-container>
      <Inicio />
    </v-main>
  </v-app>
</template>

<script>
import Inicio from "./views/Inicio.vue";
import AppTopBar from "./components/shared/AppTopBar.vue";

export default {
  name: "App",

  components: {
    Inicio,
    AppTopBar,
  },
};
</script>

<style>
</style>
