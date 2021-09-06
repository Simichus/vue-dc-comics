<template>
  <div id="app">
    <Header/>
    <main>
      <MainContent/>
      <MainLinks/>
    </main>
    <footer>
      <FooterTop/>
    </footer>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import MainContent from '@/components/MainContent.vue';
import MainLinks from '@/components/MainLinks.vue'
import FooterTop from '@/components/FooterTop.vue'

export default {
  name: 'App',
  components: {
    Header,
    MainContent,
    MainLinks,
    FooterTop
  }
}
</script>

<style lang="scss">
@import '@/assets/scss/style.scss'

</style>
