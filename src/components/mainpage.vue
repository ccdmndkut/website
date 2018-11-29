<template>
  <div class="card">
    <div class="cardtitle">title</div>
    <div class="cardbody">body</div>
  </div>
</template>

<script>
export default {
  name: "mainpage",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.card {
  display: grid;
  grid-template-rows: 10vh 40vh;
  width: 50vw;
  height: 50vh;
  color: black;
  background-color: white;
  margin: auto;
  text-align: center;
  font-size: 30px;
box-shadow: 0 3px 4px 0 rgba(0,0,0,0.14), 0 3px 3px -2px rgba(0,0,0,0.12), 0 1px 8px 0 rgba(0,0,0,0.20);
transition: box-shadow 300ms;
}
.card:hover {
box-shadow: 0 6px 10px 0 rgba(0,0,0,0.14), 0 1px 18px 0 rgba(0,0,0,0.12), 0 3px 5px -1px rgba(0,0,0,0.20);

}
.cardtitle {
  background-color: #d8883a;
  grid-row: 1;
  height: 100%;
line-height: 10vh;
}
 .cardbody {
  grid-row: 2;
  background-color: #edc8a4;
  height: 100%;
text-align: start;
padding-left: 20px;
}
</style>

