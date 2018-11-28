<template>
  <div>
    <form>
      <md-card id="card">
        <md-card-header>
          <div class="md-title">Contact Us</div>
          <md-field class="input half left">
            <label>First Name</label>
            <md-input></md-input>
            <span class="md-helper-text">Name</span>
          </md-field>
          <md-field class="input half right">
            <label>First Name</label>
            <md-input></md-input>
            <span class="md-helper-text">Name</span>
          </md-field>
        </md-card-header>
      </md-card>
    </form>
  </div>
</template>

<script>
export default {
  name: "mainpage",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
#card {
  width: 50vw;
  max-width: 600px;
  margin: 10vh auto;
}
.input.half {
  width: 40%;
  display: inline-block;
}
.input.half.right {
  margin-left: 5%;
  margin-right: 5%;
}
.input.half.left {
  margin-right: 5%;
  margin-left: 5%;
}
</style>
