<template>
  <div id='app'>
    <div id='top'>Coming Soon</div>
    <div id='pic' :style="{'background-image': 'url(' + require('./assets/eagle1.jpg') + ')'}"></div>
    <div id='bottt'>denvercombs@vaclaims.net
      <br>chriscombs@vaclaims.net
    </div>
    <!-- <input type='text'> -->
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
body {
  color: #999;
  font-family: "Raleway", "Helvetica Neue", Helvetica, Arial,
    sans-serif;
  font-style: normal;
  font-weight: 400;
  letter-spacing: 0;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -moz-font-feature-settings: "liga" on;
  max-width: 100vw;
  background-color: #000000;
  max-height: 100vh;
  overflow: hidden;
}
#top {
  font-size: 500%;
  text-align: center;
  padding-top: 25px;
  margin-bottom: -30px;
}
#pic {
  background-size: 170vh;
  background-position: top;
  background-repeat: no-repeat;
  background-position-y: -5vh;
  height: 100%;
}
#bottt {
  position: fixed;
  font-size: 3vh;
  text-align: center;
  bottom: 10px;
  width: 100%;
}
/* input {
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
} */
</style>
