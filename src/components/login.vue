<template>
  <div class="login">
  用户名：<input type="text">
  密码：<input type="password">
  <input type="submit" value="提交">
<h class="p1">欢迎</h>
  </div>
</template>
<script>

  export default {
    name: 'login'
  }


</script>




<style scoped>
  @import "../icheck.css";
  @import "../icommon.css";
.p1{
  background: url("../assets/logo.png");
  color: red;
}
</style>
