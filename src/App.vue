<template>
  <div id="app"  :style="{'background-image': 'url(' + require('../src/assets/img/background.png') + ')'}">
    <MyHeader></MyHeader>
  </div>
</template>

<script>
import MyHeader  from './components/header/index'
export default {
  name: 'app',
  components: {
    MyHeader 
  }
}
</script>

<style>
#app {

}
</style>
