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
  font-family: 'Roboto Mono', monospace, 'openhuninn', 'Noto Sans TC', sans-serif;
  text-align: center;
}
.title{
  font-size: 30px;
  line-height: 1.9;
}
</style>
