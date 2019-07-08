<template>
  <div class="Index">
    <h1>this is Index page</h1>
      <button class="login">登录</button>
    <login></login>
  </div>
</template>

<script>
import Login from '../components/Login.vue'
export default {
  components:{"login":Login},
  data(){ return {}},
  mounted(){

  

  },
}
$(function(){
    $(".login").click(function(){
       alert("点我试试看")
       console.log(111)
     })
})
</script>
