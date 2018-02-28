<template>
  <div id="app">
   <Mheader></Mheader>
    <Tab></Tab>
    <router-view></router-view>
  </div>
</template>

<script type="text/ecmascript-6">
import Mheader from './components/m-header/m-header'
import Tab from './components/tab/tab'
import router from './router/index.js'

export default {
  router,
  components: {
    Mheader,
    Tab
  }
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
</style>
