<template>
<div>
  <div>
    <p>账号<input type="text" placeholder="请输入账号"></p>
  </div>
  <div>
    <p>密码<input type="text" placeholder="请输入密码"></p>
  </div>
  <button size="mini" type="primary" @click="buttonClick">登录</button>
  </div> 
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'


export default {
  data () {

  },

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
