<template>
  <div id="app">
    <MainHeader />
    <MainContent />
    <MainFooter />
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue';
import MainContent from './components/MainContent.vue';
import MainFooter from './components/MainFooter.vue';
export default {
  name: 'App',
  components: {
    MainHeader: MainHeader,
    MainContent: MainContent,
    MainFooter: MainFooter,
}
}
</script>

<style lang="scss">

</style>
