<template>
  <Head/>
  <router-view></router-view>
</template>

<script>
import Head from './components/head.vue'
export default {
  components: {
    Head
  },
  setup () {
    return {
      title: 'Hello'
    }
  }
}
</script>


<style lang="scss">
#app {
  font-family: 'Nunito', sans-serif;
  min-height: 100vh;
  background-color: #faa;
  img{
    width: 100%;
    vertical-align: middle;
  }
}
</style>
