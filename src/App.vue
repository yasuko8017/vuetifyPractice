<template>
  <div id="app">
    <v-app id="inspire">
      <ToolBar/>
      <v-content>
      </v-content>
    </v-app>
  </div>
</template>

<script>
import ToolBar from "./components/ToolBar.vue";

export default {
  name: "App",
  components: {
    ToolBar,
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
