<template>
  <header class="container">
      <figure>
          <img src="@/assets/img/dc-logo.png" alt="">
      </figure>
      <nav>
          <ul>
              <li v-for="(voice, index) in navVoices" :key="index"><a :href="voice.url">{{voice.text}}</a></li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {
    name:'Header',
    data(){
        return{
            navVoices:[
  {
    text: 'Characters',
    url: '#',
    current: false,
  },
  {
    text: 'Comics',
    url: '#',
    current: true,
  },
  {
    text: 'Movies',
    url: '#',
    current: false,
  },
  {
    text: 'TV',
    url: '#',
    current: false,
  },
  {
    text: 'Games',
    url: '#',
    current: false,
  },
  {
    text: 'Collectibles',
    url: '#',
    current: false,
  },
  {
    text: 'Videos',
    url: '#',
    current: false,
  },
  {
    text: 'Fans',
    url: '#',
    current: false,
  },
  {
    text: 'News',
    url: '#',
    current: false,
  },
  {
    text: 'Shop',
    url: '#',
    current: false,
  },
]
        }
    }

}
</script>

<style scoped lang="scss">
@import '@/assets/scss/_mixins.scss';
@import '@/assets/scss/_vars.scss';
    
    header{
        @include justify-spacing('between');
    }

    figure{
        padding: 20px 0
    }

    nav ul{
        @include justify-spacing('end');
        li{
            a{
                display: inline-block;
                line-height:150px;
                padding: 0 10px;
                color: black;
                &:hover{
                    margin-bottom: -5px;
                    border-bottom: 5px solid $main-color;
                    
                }
            }
        }
    }
    
</style>