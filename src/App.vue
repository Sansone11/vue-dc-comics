<template>
  <div id="app">
    <MainHeader />
    <MainContentJumbo />
    <MainContent />
    <MainFooter />
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue';
import MainContentJumbo from './components/MainContentJumbo.vue';
import MainContent from './components/MainContent.vue';
import MainFooter from './components/MainFooter.vue';
export default {
  name: 'App',
  components: {
    MainHeader: MainHeader,
    MainContentJumbo: MainContentJumbo,
    MainContent: MainContent,
    MainFooter: MainFooter,
}
}
</script>

<style lang="scss">
  @import './components/Style/index.scss';
</style>
