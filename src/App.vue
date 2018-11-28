<template>
  <div id="app">
    <mainpage></mainpage>
  </div>
</template>

<script>
import mainpage from "./components/mainpage.vue";

export default {
  metaInfo: {
    title: "Vet2Vet",
    meta: [
      { "http-equiv": "Content-Type", content: "text/html; charset=utf-8" },
      { name: "viewport", content: "width=device-width, initial-scale=1" }
    ]
  },
  name: "app",
  components: {
    mainpage
  }
};
</script>

<style>
</style>
