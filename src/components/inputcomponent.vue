<template>
<div class="cont">
    inputComponent
  </div>
</template>

<script>
export default {
  name: "inputcomponent",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.cont {
  color: black;
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

