<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="swiper mySwiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide slide1">
          <div class="page1">
            <img src="https://wallpaperset.com/w/full/1/e/3/42381.jpg">
            <p>
              Real Madrid Club de Fútbol
            </p>
          </div>
        </div>
        <div class="swiper-slide slide2">
          <!-- <img src="https://images.alphacoders.com/116/1163534.jpg">
          <p>Didirikan pada tahun 1902 sebagai Madrid Football Club, secara tradisional mengenakan kostum kandang putih. Kata Real ("dari kerajaan") Spanyol dan dianugerahkan ke klub oleh Raja Alfonso XIII pada tahun 1920 bersama-sama dengan mahkota kerajaan di lambang klub</p> -->
          <div class="page2">
            <div class="wrap">
              <div class="left">
                <img
                  src="https://upload.wikimedia.org/wikipedia/en/thumb/5/56/Real_Madrid_CF.svg/1200px-Real_Madrid_CF.svg.png">
              </div>
              <div class="right">
                <p>
                  Didirikan pada tahun 1902 sebagai Madrid Football Club, secara tradisional mengenakan kostum kandang
                  putih. Kata Real ("dari kerajaan") Spanyol dan dianugerahkan ke klub oleh Raja Alfonso XIII pada tahun
                  1920 bersama-sama dengan mahkota kerajaan di lambang klub.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="swiper-slide slide3">
          <img src="https://images2.alphacoders.com/117/1176443.jpg">
            <p>
                  Stadion Bernabéu Santiago (Spanyol : Estadio Santiago Bernabéu) adalah sebuah stadion sepak bola di
                  Madrid, Spanyol. Dengan kapasitas tempat duduk saat ini 81.044, telah menjadi stadion kandang Real
                  Madrid sejak selesai dibangun pada tahun 1947.
                </p>
          <div class="page3">
            <!-- <img src="https://images2.alphacoders.com/117/1176443.jpg">
            <p>
                  Stadion Bernabéu Santiago (Spanyol : Estadio Santiago Bernabéu) adalah sebuah stadion sepak bola di
                  Madrid, Spanyol. Dengan kapasitas tempat duduk saat ini 81.044, telah menjadi stadion kandang Real
                  Madrid sejak selesai dibangun pada tahun 1947.
                </p> -->

            <!-- <div class="wrap">
              <div class="left">
                <p>
                  Stadion Bernabéu Santiago (Spanyol : Estadio Santiago Bernabéu) adalah sebuah stadion sepak bola di
                  Madrid, Spanyol. Dengan kapasitas tempat duduk saat ini 81.044, telah menjadi stadion kandang Real
                  Madrid sejak selesai dibangun pada tahun 1947.
                </p>
              </div>
              <div class="right">
                <img src="https://images2.alphacoders.com/117/1176443.jpg">
              </div>
            </div> -->
          </div>
        </div>
        <div class="swiper-slide slide4">
          <img src="https://a4.espncdn.com/combiner/i?img=%2Fphoto%2F2021%2F0411%2Fr838949_1296x729_16%2D9.jpg">
          <div class="caption">
            <h1>Florentino Pérez</h1>
            <p>Presiden Real Madrid</p>
            <p>2000 - 2006</p>
            <p>2009 - saat ini</p>
          </div>
        </div>
        <div class="swiper-slide slide5">
          <div class="page page5">
            <div class="wrap">
              <div class="left">
                <img src="https://i.pinimg.com/originals/b0/22/3b/b0223bf171b93bf6e6da99b27b8f26d3.jpg">
              </div>
              <div class="right">
                <p>Real Madrid merupakan club paling sukses di Piala Eropa, memenangkan trofi untuk rekor empat belas kali. Real madrid adalah
                  pemenang edisi perdana turnamen dan tetap menjadi satu-satunya klub yang memenangkan trofi lima kali
                  berturut-turut (lima edisi pertama). Ini juga memiliki perbedaan menjadi satu-satunya klub yang
                  mempertahankan gelar di era Liga Champions, serta memenangkannya tiga kali berturut-turut.
                <ul>
                  <p v-for="(data,key) in ucl" :key="key">{{ data.tahun }}</p>
                </ul>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="swiper-slide slide6">
          <img src="https://assets.goal.com/v3/assets/bltcc7a7ffd2fbf71f5/blt15b0f973b61b51c6/60db6d192446e93b5b636cf2/64d1851271dee180d80752f97d9dcdca6fd120e2.jpg?auto=webp&format=jpg&quality=60&width=1280">
          <div class="caption">
            <p>Cristiano Ronaldo</p>
                <p>5 February 1985 (age 37)</p>
                <p>Funchal, Madeira, Portugal</p>
                <p>Penyerang</p>
                <p>450 goals</p>
          </div>
        </div>
        <div class="swiper-slide slide8">          
          <div class="page page8">
            <div class="wrap">
              <div class="left">
                <div class="auto">
                <p>Raúl González Blanco</p>
                <p>27 Juni 1977 (umur 45)</p>
                <p>San Mamez,Madrid, Spanyol</p>
                <p>Penyerang</p>
                <p>741  apps</p>
              </div>
              </div>
              <div class="right">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Ra%C3%BAl_Gonz%C3%A1lez_in_Real_Madrid_2009.jpg/800px-Ra%C3%BAl_Gonz%C3%A1lez_in_Real_Madrid_2009.jpg">
              </div>
            </div>
          </div></div>
        <div class="swiper-slide slide7">
          <div class="page page7">
            <div class="wrap">
              <div class="left">
                <img src="https://cdn1-production-images-kly.akamaized.net/5BedkyOMyjrnpGgYGFxsUbxKpo0=/1200x1200/smart/filters:quality(75):strip_icc():format(jpeg)/kly-media-production/medias/753232/original/003455500_1413776398-000_DV1625630.jpg">
              </div>
              <div class="right">
                <p>
                  Iker Casillas Fernández<br>
20 May 1981 (age 41)<br>
Madrid, Spain<br>
Position(s)	Goalkeeper<br>
725 apps
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="swiper-slide slide9">
          <img src="https://preview.redd.it/2ltktyjrxtj41.jpg?auto=webp&s=75a374f71e923388327e3d2abdbf473ad1149407">
          <p>FIFA Club of the Century was an award presented by FIFA to decide the best football club of the 20th century.[1][2] Real Madrid was the winner of the award with 42.35% of the vote, announced at the annual FIFA World gala, held in Rome on 11 December 2000. Madrid was the most successful club in international football at the time, having amassed eight European Cups and two Intercontinental Cups.</p>
        </div>
        <div class="swiper-slide slide10">
          <img src="https://images2.minutemediacdn.com/image/fetch/w_2000,h_2000,c_fit/https%3A%2F%2Ftherealchamps.com%2Fwp-content%2Fuploads%2Fgetty-images%2F2017%2F07%2F1386763948.jpeg">
          <div class="caption">
          <h1>Carlo Ancelotti</h1>
          <h4>Coach</h4>
          <p>Italy</p>
        </div>
        </div>
        <div class="swiper-slide slide11">
          <div class="page page7">
            <div class="wrap">
              <div class="left">
                <img src="https://www.roiblog.jp/wp-content/uploads/2021/09/realmadrid22-23formation_summer_en.png">
              </div>
              <div class="right">
                <p>
                  line up 2022/2023
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="swiper-slide slide12">
          <div class="wrap">
            <div class="l1">
              <img src="https://s.hs-data.com/bilder/spieler/gross/38680.jpg?fallback=png">
            </div>
            <div class="l2">
              <img src="https://s.hs-data.com/bilder/spieler/gross/84724.jpg?fallback=png">
            </div>
            <div class="m">
              <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/408fd07f-2369-407d-a6db-724beb218ddc/df5kc5t-6ab3432c-6156-4213-9f77-3b6daa692acf.jpg/v1/fill/w_1024,h_1280,q_75,strp/thibaut_courtois_real_madrid_wallpaper_by_jafarjeef_df5kc5t-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MTI4MCIsInBhdGgiOiJcL2ZcLzQwOGZkMDdmLTIzNjktNDA3ZC1hNmRiLTcyNGJlYjIxOGRkY1wvZGY1a2M1dC02YWIzNDMyYy02MTU2LTQyMTMtOWY3Ny0zYjZkYWE2OTJhY2YuanBnIiwid2lkdGgiOiI8PTEwMjQifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.ca6MhIjDGx81UN7ZDTM2QjyJjeQha7QH0NSXC05AqRY">
            </div>
            <div class="r1">
              <img src="https://cdn.vox-cdn.com/thumbor/PtdtQ5A5msr2hKgMtfnOxn9MZSo=/0x0:3211x4282/1200x800/filters:focal(929x652:1441x1164)/cdn.vox-cdn.com/uploads/chorus_image/image/71377994/1243234699.0.jpg">
            </div>
            <div class="r2">
              <img src="https://pbs.twimg.com/media/Fb-QOE-XgAAo9mX?format=jpg&name=large">
            </div>
          </div>
        </div>
      </div>
      <div class="swiper-pagination"></div>
    </div>

    <!-- <div class="swiper Swiper2nd">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="https://www.realmadrid.com/StaticFiles/RealMadridResponsive/images/RM-amp-news-logo.png"></div>
        <div class="swiper-slide"><img src="https://images2.alphacoders.com/117/1176443.jpg"></div>
        <div class="swiper-slide"><img src="https://images4.alphacoders.com/127/1271042.jpg"></div>
        <div class="swiper-slide"><img src="https://a4.espncdn.com/combiner/i?img=%2Fphoto%2F2021%2F0411%2Fr838949_1296x729_16%2D9.jpg"></div>
        <div class="swiper-slide"><img src="https://www.statista.com/graphic/1/780306/real-madrid-number-of-trophies.jpg" alt="Statistic: Number of trophies won by Real Madrid Football Club as of August 2022, by championship | Statista" style="width: 100%; height: auto !important; max-width:1000px;-ms-interpolation-mode: bicubic;"/></div>
        <div class="swiper-slide">Slide 6</div>
        <div class="swiper-slide">Slide 7</div>
        <div class="swiper-slide">Slide 8</div>
        <div class="swiper-slide">Slide 9</div>
      </div>
      <div class="swiper-pagination"></div>
    </div> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  },
  data() {
    return {
      swiper1: null,
      swiper2: null,
      ucl: [
        {
        tahun:'1956'
        },
        {
        tahun:'1957'
        },
        {
        tahun:'1958'
        },
        {
        tahun:'1959'
        },
        {
        tahun:'1960'
        },
        {
        tahun:'1966'
        },
        {
        tahun:'1998'
        },
        {
        tahun:'2000'
        },
        {
        tahun:'2002'
        },
        {
        tahun:'2014'
        },
        {
        tahun:'2016'
        },
        {
        tahun:'2017'
        },
        {
        tahun:'2018'
        },
        {
        tahun:'2022'
        },
      ]
    }
  },
  methods: {
    createSwiper() {
      /*eslint-disable*/
      this.swiper1 = new Swiper(".mySwiper", {
        direction: "vertical",
        slidesPerView: 1,
        spaceBetween: 0,
        mousewheel: true,
        pagination: {
          el: ".swiper-pagination",
          clickable: true,
        },
      });
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
  }
}
</script>

<style>
body {
  margin: 0 !important;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
  height: 100vh;
}

.Swiper2nd .swiper-slide img {
  object-fit: contain;
}

.wrap {
  display: flex;
  height: 100%;
  width: 100%;
}
.page{
  height: 100%;
  width: 100%;
}
.mySwiper .swiper-slide.swiper-slide-active .page1 p {
  font-size: 50px;
  width: 500px;
  height: 250px;
  position: absolute;
  left: 20px;
  bottom: 50px;
  z-index: 100;
  animation: right 3s linear;
  animation-fill-mode: both;

}

.mySwiper .swiper-slide.swiper-slide-active .page2 p {
  margin: auto;
  font-size: 20px;
  width: 500px;
  z-index: 100;
  animation: left 3s linear;
  animation-fill-mode: both;
  border-radius: 10px;
  background-color: wheat;
  padding: 15px;
}
.auto{
  margin: auto;
}

.left {
  width: 50%;
}

.right {
  width: 50%;
}
.l1,.l2,.m,.r1,.r2{
  width: 20%;
  height: 100%;
  overflow: hidden;
}

.mySwiper .swiper-slide.swiper-slide-active .page1 img {
  animation: zoom-in-slow 10s linear;
  animation-fill-mode: forwards;
}
.slide2{
 background-color: antiquewhite !important;
}
.page2 .right {
  margin: auto;
}

.page2 .left img {
  width: 45%;
  margin: auto;
  animation: updownup 2s infinite;
  animation-fill-mode: both;
  animation-timing-function: linear;
}

.swiper-slide .page3 img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.mySwiper .slide3 p{
  padding: 25px;
  width: 50%;
  position: absolute;
  left: 25%;
  top: 50%;
  font-size: 36px;
  background-color: rgba(192,192,192,0.8);
  border-radius: 10px;
}
.mySwiper .swiper-slide.slide3.swiper-slide-active  p{
  animation: up .7s linear;
  animation-fill-mode: both;
}

.slide3 img{
  width: 100%;
  height: 100%;
}
.mySwiper .swiper-slide.slide3.swiper-slide-active img{
  width: 100%;
  height: 100%;
  animation: zoom-in-slow 10s linear;
  animation-fill-mode: forwards;
}

.slide4 img{
  width: 100%;
  height: 100%;
}
.mySwiper .swiper-slide.slide4.swiper-slide-active .caption{
  animation: zoom-in-slow 2s linear;
  animation-fill-mode: forwards;
}
.caption{
  position: absolute;
  bottom: 8%;
  background-color: aliceblue;
  border-radius: 15px;
  padding: 5px;
  padding-left: 15px;
  padding-right: 15px;
}
.swiper-slide .page5 img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.page5 .wrap {
  background-color: midnightblue;
  color: antiquewhite;
}

.page5 .right {
  width: 40%;
  height: 100%;
  margin: auto;
  display: flex;
  font-size: 16px;
  /* background-color: wheat; */
}
.page5 p{
  margin: auto;
}

.mySwiper .swiper-slide.swiper-slide-active .page5 .right p {
  animation: bounce 2s ease 0s 1 normal forwards;
}

.slide6 img{
  width: 100%;
  height: 100%;
}
.mySwiper .swiper-slide.slide6.swiper-slide-active img {
  animation: zoom-in-slow 10s linear;
  animation-fill-mode: forwards;
}
.slide6 .caption{
  width: 100%;
  background-color: rgba(192,192,192,0.8);
  font-size: 15px;
}
.mySwiper .swiper-slide.slide6.swiper-slide-active .caption{
  animation: upo 3s linear;
}
.page7 .right{
  display: flex;
}
.page7 .right p{
  margin: auto;
}
.slide7 img{
  width: 100%;
  height: 100%;
}
.mySwiper .swiper-slide.swiper-slide-active .page7 .left img {
  animation: right1 2s forwards;
}
.mySwiper .swiper-slide.swiper-slide-active .page7 .right p {
  animation: opacity 3s forwards;
}

.page8 .left{
  display: flex;
}
.page8 .left p{
  margin: auto;
}
.slide8 img{
  width: 100%;
  height: 100%;
}
.mySwiper .swiper-slide.swiper-slide-active .page8 .right img {
  animation: left1 2s forwards;
}
.mySwiper .swiper-slide.swiper-slide-active .page8 .left p {
  animation: opacity 3s forwards;
}

.slide9 img{
  width: 100%;
  height: 100%;
}
.slide9 p{
  position: absolute;
  bottom: 10%;
  background-color: rgba(192,192,192,0.8);
  padding: 20px;
}
.mySwiper .swiper-slide.slide9.swiper-slide-active p{
  animation: upo 3s linear;
}
.slide10 img{
  height: 100%;
  width: 100%;
}
.slide10 .caption{
  animation: updownup 2s infinite;
}
.mySwiper .swiper-slide.slide10.swiper-slide-active img {
  animation: zoom-in-slow 10s linear;
  animation-fill-mode: forwards;
}
.slide11 img{
  height: 100%;
  width: 100%;
}

.slide12 img{
  height: 100%;
}
.mySwiper .swiper-slide.swiper-slide-active .l1{
  animation: upo 3s linear;
}
.mySwiper .swiper-slide.swiper-slide-active .l2{
  animation: downo 3s linear;
}
.mySwiper .swiper-slide.swiper-slide-active .m{
  animation: upo 3s linear;
}
.mySwiper .swiper-slide.swiper-slide-active .r1{
  animation: downo 3s linear;
}
.mySwiper .swiper-slide.swiper-slide-active .r2{
  animation: upo 3s linear;
}

@media(max-width: 500px) {
  body {
    background-color: lightblue;
  }
  .mySwiper .swiper-slide.swiper-slide-active .page1 p{
    font-size: 26px;
    width: 50%;
    left: 30px;
    animation: left1 3s linear;
  }
  .slide11 .left{
    width: 100%;
  }
  .slide11 .right{
    display: none;
  }
  .page2 .left{
    width: 100%;
  }
  .page2 .left img{
    width: 150%;
  }
  .mySwiper .swiper-slide.swiper-slide-active .page2 p{
    position: absolute;
    left: 0;
    bottom: 0;
    width: 95%;
    font-size: 12px;
    animation: upo 2s linear;
  }
  .mySwiper .slide3 p{
    font-size: 20px;
  }

  .page5 .left{
    width: 100%;
  }
  .page5 .right{
    position: absolute;
    left: 30%;
    top: 2%;
    background-color: rgba(192,192,192,0.8);
    padding-left: 15px;
    padding-right: 15px;
  }
  .page7 .left{
    width: 100%;
  }
  .page7 .right{
    width: 100%;
    position: absolute;
    background-color: rgba(192,192,192,0.6);
    bottom: 0;
  }
  .mySwiper .swiper-slide.swiper-slide-active .page7 .right p{
    animation: left1 2s linear;
  }
  .page8 .right{
    width: 100%;
  }
  .page8 .left{
    z-index: 100;
    width: 100%;
    position: absolute;
    background-color: rgba(192,192,192,0.6);
    bottom: 0;
  }
  .mySwiper .swiper-slide.swiper-slide-active .page8 .left p{
    animation: right1 2s linear;
  }
}

@keyframes jelly {
  0% {
    transform: scale3d(1, 1, 1);
  }

  30% {
    transform: scale3d(1.25, 0.75, 1);
  }

  40% {
    transform: scale3d(0.75, 1.25, 1);
  }

  50% {
    transform: scale3d(1.15, 0.85, 1);
  }

  65% {
    transform: scale3d(0.95, 1.05, 1);
  }

  75% {
    transform: scale3d(1.05, 0.95, 1);
  }

  100% {
    transform: scale3d(1, 1, 1);
  }
}

@keyframes bounce {
  0% {
    animation-timing-function: ease-in;
    opacity: 1;
    transform: translateY(-45px);
  }

  24% {
    opacity: 1;
  }

  40% {
    animation-timing-function: ease-in;
    transform: translateY(-24px);
  }

  65% {
    animation-timing-function: ease-in;
    transform: translateY(-12px);
  }

  82% {
    animation-timing-function: ease-in;
    transform: translateY(-6px);
  }

  93% {
    animation-timing-function: ease-in;
    transform: translateY(-4px);
  }

  25%,
  55%,
  75%,
  87% {
    animation-timing-function: ease-out;
    transform: translateY(0px);
  }

  100% {
    animation-timing-function: ease-out;
    opacity: 1;
    transform: translateY(0px);
  }
}

@keyframes shadow-drop-2-center {
  0% {
    transform: translateZ(0);
    box-shadow: 0 0 0 0 rgba(0, 0, 0, 0);
  }

  50% {
    transform: translateZ(50px);
    box-shadow: 0 0 30px 0px rgba(0, 0, 0, 0.5);
  }

  100% {
    transform: translateZ(0);
    box-shadow: 0 0 0 0 rgba(0, 0, 0, 0);
  }
}

@keyframes updownup {
  0% {
    transform: translateY(0px);
    animation-timing-function: ease-out;
  }
  50% {
    transform: translateY(10px);
    animation-timing-function: ease-out;
  }

  100% {
    transform: translateY(0px);
    animation-timing-function: ease-out;
  }
}

@keyframes right {
  0% {
    transform: translateX(0px);
    opacity: 0;
  }

  100% {
    transform: translateX(80px);
    opacity: 1;
  }
}
@keyframes opacity {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

@keyframes right1 {
  0% {
    transform: translateX(-80px);
    opacity: 0;
  }

  100% {
    transform: translateX(0px);
    opacity: 1;
  }
}

@keyframes left {
  0% {
    transform: translateX(0px);
    opacity: 0;
  }
  100% {
    transform: translateX(-80px);
    opacity: 1;
  }
}
@keyframes left1 {
  0% {
    transform: translateX(80px);
    opacity: 0;
  }
  100% {
    transform: translateX(0px);
    opacity: 1;
  }
}
@keyframes up {
  0% {
    transform: translateY(0px);
    opacity: 0;
  }
  100% {
    transform: translateY(-100px);
    opacity: 1;
  }
}
@keyframes upo {
  0% {
    transform: translateY(80px);
    opacity: 0;
  }
  100% {
    transform: translateY(0px);
    opacity: 1;
  }
}
@keyframes downo {
  0% {
    transform: translateY(-80px);
    opacity: 0;
  }
  100% {
    transform: translateY(0px);
    opacity: 1;
  }
}
@keyframes down {
  0% {
    transform: translateY(-80px);
    opacity: 0;
  }

  100% {
    transform: translateY(0px);
    opacity: 1;
  }
}

@keyframes zoom-in-slow {
  0% {
    transform: scale(1.1);
  }

  100% {
    transform: scale(1);
  }
}

/* .mySwiper .swiper-slide.swiper-slide-active .text {
    opacity: 1;
    transform: translateY(0);
    transition: all 1s linear;
    transition-delay: 2s;
  } */

.swiper {
  width: 100%;
  height: 100%;
}

.Swiper2nd {
  width: 500px;
  height: 250px;
  position: fixed;
  left: 20px;
  bottom: 20px;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #fff;
  height: 100%;
  width: 100%;

  /* Center slide text vertically */
  display: -webkit-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-justify-content: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  -webkit-align-items: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  object-fit: cover;
}
.swiper-wrapper {
  height: 100%;
  width: 100%;
}
</style>
