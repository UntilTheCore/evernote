<template>
  <div id="app">
    <div id="nav">
      <router-link to="/login">前往登录页面</router-link>
      <br/>
      <router-link to="/notebooks">前往文章列表页面</router-link>
      <br/>
      <router-link to="/note/3">查看id为3的文章</router-link>
      <br/>
      <router-link to="/trash/2">查看id为2且被删除的文章</router-link>
      <br/>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
