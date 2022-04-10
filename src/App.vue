<template>
  <h1>Hello Vue App</h1>
  <Registration />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Registration from "./components/Registration.vue"

export default defineComponent({
  name: "App",
  components: {
    Registration
  },
});
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
