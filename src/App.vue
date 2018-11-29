<template>
  <div id='app' class="bluebg">
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
#app {
  height: 100vh;
 padding:  25vh 0px;

}
.bluebg {
  background-color: #3A8AD8;
}
input {
  all: unset;
  background-color: #f1f3f4;
  height: 30px;
  width: 30vw;
  -moz-border-radius: 15px;
  -webkit-border-radius: 15px;
  border-radius: 15px;
  padding: 15px;
  outline: 0;
  transition: 300ms;
}
input:hover {
  background-color: #e7e9ec;
}

input:focus {
  height: 30px;
  width: 30vw;
  background-color: white;
  border: 2px #ccdcfc solid;
  -moz-border-radius: 15px;
  -webkit-border-radius: 15px;
  border-radius: 15px;
  padding: 15px;
  box-sizing: border-box;
  outline: 0;
  transition: 0s;
}
</style>
