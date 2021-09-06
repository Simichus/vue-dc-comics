<template>
  <section>
      <ul>
          <li>
              <a href="#">
              <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
              <span>Digital comics</span>
              </a>
          </li>
          <li>
              <a href="#">
              <img src="@/assets/img/buy-comics-merchandise.png" alt="">
              <span>DC Merchandise</span>
              </a>
          </li>
          <li>
              <a href="">
                <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
                <span>Subscription</span>
              </a>
          </li>
          <li>
              <a href="#">
                <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
                <span>Comic Shop Locator</span>
              </a>
          </li>
          <li>
              <a href="#">
                <img src="@/assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC Power Visa</span>
              </a>
          </li>
      </ul>
  </section>
</template>

<script>
export default {
name:'MainLinks',
}
</script>

<style scoped lang="scss">
@import '@/assets/scss/_mixins.scss';
@import '@/assets/scss/_vars.scss';

section{
    background-color: $main-color;
    padding: 60px 0
}
ul{
    @include justify-spacing(center);

    li{
        a{

            margin: 0 20px;
            @include justify-spacing(center);
            img{
                height: 60px;
                margin-right: 10px;
            }
        }
    }
}
</style>