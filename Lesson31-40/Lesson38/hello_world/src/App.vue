<template>
  <div id="app">
    <h1>Hello World</h1>
    <my-button :msg="msg" >
    </my-button>
  </div>
</template>

<script>
import MyButton from './components/MyButton.vue'

export default {
  name: 'app',
  data:function(){
    return {
      msg:"Jimmy"
    }
  },
  components: {
    MyButton
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
