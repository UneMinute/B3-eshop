<template>
  v0.0.0
  <Profil />
  <router-view></router-view>
</template>

<script>

import HelloWorld from './components/HelloWorld.vue'
import Profil from "./components/Profil.vue";
export default {
  components : {HelloWorld, Profil},
  mounted() {
    this.$store.dispatch('loadProducts');
  }
}


// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
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
