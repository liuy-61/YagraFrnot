<template>
  <nav>
    <router-link to="/">主页</router-link> |
    <router-link to="/register">注册</router-link> |
    <router-link to="/login">登录</router-link> |
    <router-link to="/logout">登出</router-link> |
    <router-link to="/upload">上传头像</router-link>
  </nav>
  <router-view/>
</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
