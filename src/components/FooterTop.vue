<template>
  <section>
      <div class="container">
          <div class="footer-links">
              <div id="dc-comics">
                  <h2>DC COMICS</h2>
                  <ul>
                      <li><a href="#">Character</a></li>
                      <li><a href="#">Comics</a></li>
                      <li><a href="#">Movies</a></li>
                      <li><a href="#">TV</a></li>
                      <li><a href="#">Games</a></li>
                      <li><a href="#">Videos</a></li>
                      <li><a href="#">News</a></li>
                  </ul>
              </div>
              <div id="shop">
                  <h2>SHOP</h2>
                  <ul>
                      <li><a href="#">Shop DC</a></li>
                      <li><a href="#">Shop DC Collectibles</a></li>
                  </ul>
              </div>
              <div id="dc">
                  <h2>DC</h2>
                  <ul>
                      <li><a href="#">Terms of Use</a></li>
                      <li><a href="#">Privacy Policy (New)</a></li>
                      <li><a href="#">Ad Choices</a></li>
                      <li><a href="#">Advertising</a></li>
                      <li><a href="#">Jobs</a></li>
                      <li><a href="#">Subscriptions</a></li>
                      <li><a href="#">Talent Workshops</a></li>
                      <li><a href="#">CPSC Certificates</a></li>
                      <li><a href="#">Ratings</a></li>
                      <li><a href="#">Shop Help</a></li>
                      <li><a href="#">Contact Us</a></li>
                  </ul>
              </div>
              <div id="sites">
                  <h2>SITES</h2>
                  <ul>
                      <li><a href="#">DC</a></li>
                      <li><a href="#">MAD Magazine</a></li>
                      <li><a href="#">DC Kids</a></li>
                      <li><a href="#">DC Universe</a></li>
                      <li><a href="#">DC Power Visa</a></li>
                  </ul>
              </div>
          </div>
          <figure>

          </figure>

      </div>

  </section>
</template>

<script>
export default {
    name:'FooterTop'

}
</script>

<style scoped lang="scss">
@import '@/assets/scss/_mixins.scss';
@import '@/assets/scss/_vars.scss';

section{
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
}

.container{
    height: 500px;
    @include justify-spacing('between');
}

figure{
    flex-basis: 50%;
    height: 100%;
    background-image: url('../assets/img/dc-logo-bg.png');
    background-size: cover;
    background-position: center;
}

.footer-links{
    max-height: 100%;
    padding: 10px 0;

    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    align-content: flex-start;
    justify-content: flex-start;

    div{
        margin-bottom: 20px;
        padding-right: 50px;
    }
}

ul{
    h2{
        font-size: 22px;
    }
    li{
        font-size: 16px;
        a{
            color: #8d8d8d;
            &:hover{
                color: white;
            }
        }
    }
}

</style>