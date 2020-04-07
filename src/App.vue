<template>
  <div id="app">
    <div>
      <router-link to="/">Home</router-link>
      <router-link to="/blog">Blog</router-link>
      <router-link to="/account">Account</router-link>
    </div>
    <router-view></router-view>
    <!-- <app-user></app-user> -->
    <p>this is a test</p>
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

<style>
</style>
