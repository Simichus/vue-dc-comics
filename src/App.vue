<template>
  <div id="app">
    <Header/>
    <main>
      <MainContent/>
      <MainLinks/>
    </main>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import MainContent from '@/components/MainContent.vue';
import MainLinks from '@/components/MainLinks.vue'

export default {
  name: 'App',
  components: {
    Header,
    MainContent,
    MainLinks
  }
}
</script>

<style lang="scss">
@import '@/assets/scss/style.scss'

</style>
