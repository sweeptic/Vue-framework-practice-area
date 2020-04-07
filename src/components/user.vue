<template>
  <div id="user">
    <h3>the user</h3>
    <p>my username is {{username}}</p>
    <app-info></app-info>
  </div>
</template>

<script>
import info from "./info.vue";
export default {
  data: function() {
    return {
      username: "max"
    };
  },
  components: {
    "app-info": info
  }
};
</script>

<style scoped >
p {
  font-style: italic;
}
</style>