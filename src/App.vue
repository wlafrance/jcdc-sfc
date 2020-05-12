<template>
  <v-app id="app">
    <div id="app">
      <HelloWorld></HelloWorld>
    </div>
  </v-app>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/hello-world.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
