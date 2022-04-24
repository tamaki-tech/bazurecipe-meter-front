<template>
  <v-app>
    <v-app-bar color="primary" dark>
      <v-app-bar-nav-icon />
      <v-toolbar-title>BazuRecipe-Meter</v-toolbar-title>
    </v-app-bar>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "App",

  data: () => ({
    //
  }),
});
</script>
