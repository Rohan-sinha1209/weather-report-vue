<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <weatherInfo msg="Weather report of different Places"/>
</template>

<script>
import weatherInfo from './components/weatherInfo.vue';
// import Vue from 'vue';
// window.axios=require('axios')
export default {
  name: 'App',
  components: {
    weatherInfo
  }
}
</script>


