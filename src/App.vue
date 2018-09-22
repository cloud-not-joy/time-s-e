<template>
  <div class="page">
    <HeadInfo></HeadInfo>
  </div>
</template>

<script>
import HeadInfo from '@/components/HeadInfo.vue'
export default {
  name: 'App',
  components: {
    HeadInfo
  }
}
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
body {
  position: relative;
  max-width: 750px;
  margin: 0 auto;
}
.page {
  position: relative;
  max-width: 750px;
  margin: 0 auto;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
