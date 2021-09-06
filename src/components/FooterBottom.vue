<template>
  <section>
      <div class="container">

        <div><a id="sign-up" href="#">SIGN-UP NOW!</a></div>
        <div class="links">
            <span>FOLLOW US</span>
            <a href="#"><img src="@/assets/img/footer-facebook.png" alt=""></a>
            <a href="#"><img src="@/assets/img/footer-twitter.png" alt=""></a>
            <a href="#"><img src="@/assets/img/footer-youtube.png" alt=""></a>
            <a href="#"><img src="@/assets/img/footer-pinterest.png" alt=""></a>
            <a href="#"><img src="@/assets/img/footer-periscope.png" alt=""></a>
        </div>
      </div>
  </section>
</template>

<script>
export default {
name:'FooterBottom'
}
</script>

<style scoped lang="scss">
@import '@/assets/scss/_mixins.scss';
@import '@/assets/scss/_vars.scss';

    section{
        background-color: #303030;
        padding: 30px;
    }

    .container{
        font-weight: bold;
        @include justify-spacing('between');
        #sign-up{
            display: inline-block;
            padding: 10px;
            border: 2px solid $main-color;
            border-radius: 5px;
        }
        .links{
            color: $main-color;
            @include justify-spacing('end');
            span, a{
                margin-left: 20px;
            }
        }
    }
</style>