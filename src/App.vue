<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <login></login>
  <!-- <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" /> -->

</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from './pages/HelloWorld.vue'
import Login from './pages/Login.vue'

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld,
    Login
  }
})
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
