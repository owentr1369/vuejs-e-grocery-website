<template>
  <v-app>
    <NavBar />
    <v-container fluid></v-container>
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
export default {
  name: "HomeView",
  components: {
    NavBar,
  },
};
</script>
