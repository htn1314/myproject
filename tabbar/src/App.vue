<template>
  <div id="app">
    <main-tab-bar/>
    <router-view/>
  </div>
</template>

<script>
import MainTabBar from './components/tabbar/MainTabBar'
export default {
  name: 'App',
  components: {
    MainTabBar
  },
}
</script>

<style>
 @import "assets/css/base.css";
</style>
