<template>
  <section>
      <div class="container">
      <h1> {{content}} </h1>
      </div>
  </section>
</template>

<script>
export default {
    name:'MainContent',
    data(){
        return{
            content:'<-- Content goes Here -->'
        }
    }

}
</script>

<style scoped lang="scss">
section{
    padding: 50px 0;
    background-color: #1c1c1c;
}
</style>