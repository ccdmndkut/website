<template>
  <div
    id='app'
    class="bluebg"
  >
   <inputcomponent></inputcomponent>
  </div>
</template>

<script>
import mainpage from "./components/mainpage.vue";
import inputcomponent from "./components/inputcomponent.vue";

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
    mainpage,
    inputcomponent
  }
};
</script>

<style>
#app {
  height: 100vh;
}
.bg {
  background-color: #f0f0df;
}


</style>
