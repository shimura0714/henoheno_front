<template>
  <div id='app'>
    <img alt='Vue logo' src='./assets/logo.png'>
    <List />
  </div>
</template>

<script lang='ts'>
import Vue  from 'vue';
import List from './components/seo/list.vue';

export default Vue.extend({
  name: 'App',
  components: {
    List
  } 
});

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
