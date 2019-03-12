<template>
  <div id="app">
    <globalHeader/>
    <router-view/>
    <globalFooter/>
  </div>
</template>

<script>
// @ is an alias to /src
import globalHeader from '@/components/globalHeader.vue'
import globalFooter from '@/components/globalFooter.vue'

export default {
  components: {
    globalHeader,
    globalFooter
  }
}
</script>

<style lang="scss">
// @import '@/scss/vendor/bootstrap-4.3.1/css/bootstrap-reboot.min.css';
// @import '@/scss/vendor/bootstrap-4.3.1/css/bootstrap-grid.min.css';
// @import '@/scss/vendor/bootstrap-4.3.1/css/bootstrap.min.css';
@import '@/scss/wilson/wilson.scss';
@import '@/scss/project/main.scss';
</style>
