<template>
  <div id="app">
    <b-container class="bv-example-row">
      <b-row>
        <b-col class="screen" cols="10" offset="1">md="4"</b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

  .container {
    border: 1px dashed;

    .screen {
      background-color: gray;
    }
  }
}
</style>
