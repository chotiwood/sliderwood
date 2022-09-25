<template>
  <div id="app">
    <div class="swiper akmalSwiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide" v-for="(data,key) in dataArray" :key="key">
          <div class="background-img" :style="{ 'background-image': 'url(' + data.img + ')' }"></div>
          <div class="text">{{ data.nama }}</div>
        </div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
    
    <div class="swiper cotiSwiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide" v-for="(data,key) in dataArray" :key="key">
          <div class="background-img" :style="{ 'background-image': 'url(' + data.img + ')' }"></div>
          <div class="text">{{ data.nama }}</div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
  body {
    margin: 0;
  }
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    height: 100vh;
  }
  .background-img {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-size: cover;
  }
  .text {
    position: absolute;
    bottom: 20px;
    left: 20px;
    background-color: rgba(0,0,0,0.5);
    color: #fff;
    width: 400px;
    height: 160px;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transform: translateY(10%);
  }
  .swiper, .swiper-wrapper {
    height: 100%;
  }
  .swiper-slide {
    justify-content: center;
    align-items: center;
    display: flex;
    position: relative;
  }
  .akmalSwiper .swiper-slide.swiper-slide-active .background-img {
    animation: zoom-in-slow 10s linear;
    animation-fill-mode: forwards;
  }
  @keyframes zoom-in-slow {
    0% {
      transform: scale(1) translateX(0) rotate(0);
    }
    100% {
      transform: scale(2) translateX(10%) rotate(10deg);
    }
  }
  .akmalSwiper .swiper-slide.swiper-slide-active .text {
    opacity: 1;
    transform: translateY(0);
    transition: all 1s linear;
    transition-delay: 2s;
  }
  .cotiSwiper {
    width: 270px;
    height: 140px;
    position: fixed;
    right: 20px;
    top: 20px;
  }
  </style>
<script>
export default {
  name: 'App',
  data() {
    return {
      swiper1: null,
      swiper2: null,
      dataArray: [
        {
          nama: 'Akmal',
          img: 'https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/1200px-Image_created_with_a_mobile_phone.png',
        },
        {
          nama: 'Deny',
          img: 'https://en.kepoper.com/wp-content/uploads/2021/01/twice-mina-profile-1-wm-758x506.jpg',
        },
        {
          nama: 'Choti',
          img: 'https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__480.jpg',
        },
        {
          nama: 'Sasa',
          img: 'https://helpx.adobe.com/content/dam/help/en/photoshop/using/convert-color-image-black-white/jcr_content/main-pars/before_and_after/image-before/Landscape-Color.jpg',
        }
      ]
    }
  },
  methods: {
    createSwiper() {
      /* eslint-disable */
      this.swiper1 = new Swiper(".akmalSwiper", {
        direction: "vertical",
        slidesPerView: 1,
        spaceBetween: 0,
        mousewheel: true,
        pagination: {
          el: ".swiper-pagination",
          clickable: true,
        },
      });
      
      /* eslint-disable */
      this.swiper2 = new Swiper(".cotiSwiper", {
        effect: 'cube',
        direction: "horizontal",
        slidesPerView: 1,
        spaceBetween: 0
      });
    },
    swiperFlow() {
      this.swiper1.on('slideChangeTransitionStart', () => {
        this.swiper2.slideTo(this.swiper1.activeIndex)
      })
    }
  },
  mounted() {
    this.createSwiper()
    this.swiperFlow()
  }
}
</script>

