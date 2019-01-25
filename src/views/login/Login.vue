<template>
  <div class="login-wrap">
    <div class="login-img">
      <img src="@/assets/images/login-header.jpg" alt>
    </div>
    <div class="login-main">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
    </div>
    <div class="login-foot">
        <span>
            <i></i>
            注册账号
        </span>
        <span>
            <i></i>
            忘记密码
        </span>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.login-wrap .login-img{
    width: 37.5rem;
    height: 20rem;
    border:1px solid red;    
}

</style>