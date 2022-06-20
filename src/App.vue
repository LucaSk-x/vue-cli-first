<template>
  <div id="app">
    <TitlePage></TitlePage>
    <HeroPage></HeroPage>
  </div>
</template>

<script>
import TitlePage from './components/Title.vue'
import HeroPage from './components/Hero.vue'


export default {
  name: 'App',
  components: {
    TitlePage, HeroPage,
  }
}
</script>

<style lang="scss">

</style>
