<template>
  <div id="app">
      <div id="login">
          <signup></signup>
      </div>
  </div>
</template>

<script>
    import login from "./components/login.vue";
    import signup from "./components/signup.vue";
export default {
  name: 'app',
  data () {
    return {
    }
  },
    components:{
        signup
    }
}
</script>

<style>
    #app {
      font-family: 'Avenir', Helvetica, Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      margin-top: 30px;
    }
    #login{
        text-align:center;
    }
    #app{
        text-align:center;
    }
</style>
