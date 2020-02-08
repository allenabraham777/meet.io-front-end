<template>
  <div id="app">
    <Ui/>
    <router-view/>
  </div>
</template>

<script>
import Ui from '@/components/Ui'
export default {
  name: 'App',
  components: {
    Ui
  }
}
</script>

<style>
#app {
  padding: 0;
  margin: 0;
}
</style>
