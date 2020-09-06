<template>
  <div id="app">
    <AppHeader />
    <router-view/>
    <AppFooter />
  </div>
</template>

<script>
  import AppHeader from '@/components/AppHeader'
  import AppFooter from '@/components/AppFooter'

  export default {
    components: {
      AppHeader,
      AppFooter
    }
  }
</script>

<style lang="less">
@import "../node_modules/uikit/src/less/uikit.less";

a {
  color: #008000;
}

.my-container {
  margin-left: 2rem;
  margin-right: 2rem;
}

</style>
