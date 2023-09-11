<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})


</script>

<template>
  <small>{{ msg }}</small>

  <!-- <body class="light"> -->
  <div class="light">
    <header class="header">
      <div class="contained header__contained flex">


        <!-- Fin del Sidebar -->


        <div class="grow-1 grid">
          <div class="bg--accent jc-spaced">
            <span class="nowrap">Practice webpage heavily inspired in <a href="https://georgia.travel/" target="_blank" rel="noopener noreferrer">georgia.travel</a> and <a href="https://www.visitmalta.com/" target="_blank" rel="noopener noreferrer">visitmalta.com</a>
            </span>
            <button aria-label="Close this message? (is not implemented yet)" class="close close--small">
              <span class="close__line"></span>
              <span class="close__line"></span>
            </button>
            <!-- </div> -->
          </div>
          <div class="flex jc-spaced">
            <a class="logo">
              georgia.
            </a>
            <button type="button" class="btn-theme mx-auto" hidden>
              <div class="visible-on-dark">
                <ion-icon name="moon-outline"></ion-icon>
                <!-- <span>Dark Mode</span> -->
              </div>
              <div class="visible-on-light">
                <ion-icon name="sunny-outline"></ion-icon>
                <!-- <span>Light Mode</span> -->
              </div>
            </button>
            <!-- </div> -->
            <!-- </div> -->
            <button aria-label="Open the navigation" class="header__burger burger">
              <span class="burger__line"></span>
              <span class="burger__line"></span>
              <span class="burger__line"></span>
            </button>
          </div>
        </div>
      </div>
    </header>


    <!-- Sidebar -->
    <div class="menu" inert="" aria-hidden="true">
      <div class="menu-contents">
        <div class="menu-header">
          <!-- <a class="logo block " href="#">
          georgia
        </a> -->
          <span class="logo block ">georgia</span>
          <button id="btnCloseMenu" aria-label="Close the navigation" class="close">
            <span class="close__line"></span>
            <span class="close__line"></span>
          </button>
        </div>
        <nav class="">
          <ul class="menu__ul ">
            <li class="">
              <a class="" href="#">Why Georgia</a>
            </li>
            <li class="">
              <a class="" href="#">Destinations</a>
            </li>
            <li class="">
              <a class="" href="#">Things To Do</a>
            </li>
            <li class="">
              <a class="" href="#">Nature & Adventure</a>
            </li>
            <li class="">
              <a class="" href="#">Useful Info</a>
            </li>
            <li class="">
              <a class="" href="#">More</a>
            </li>
          </ul>
          <ul class="absolute-bottom socials">
            <li class="">
              <a class="" href="#">Facebook</a>
            </li>
            <li class="">
              <a class="" href="#">Instagram</a>
            </li>
            <li class="">
              <a class="" href="#">Twitter</a>
            </li>
            <li class="">
              <a class="" href="#">Youtube</a>
            </li>
          </ul>
          <!-- </div> -->
        </nav>

      </div>
    </div>


    <main class="main">
      <section class="hero" id="hero">

        <div class="swiper swiper--a">
          <div class="swiper-wrapper swiper-no-swiping">
            <div class="swiper-slide">
              <video class="video hero__video" loop muted playsinline src="rojas.mp4"></video>
            </div>
            <!-- <div class="swiper-slide">
            <video class="video hero__video" loop muted playsinline src="pexels-김-대정-12315341 (720p).mp4"></video>
          </div> -->

            <div class="swiper-slide">
              <video class="video hero__video" loop muted playsinline src="pexels-김-대정-16903067 (720p).mp4"></video>
            </div>
            <!-- <div class="swiper-slide">
            <video class="video hero__video" loop muted playsinline src="pexels-김-대정-6208343 (720p).mp4"></video>
          </div> -->
            <div class="swiper-slide">
              <video class="video hero__video" loop muted playsinline src="pexels_videos_2734348 (720p).mp4"></video>
            </div>

          </div>


        </div>

        <div class="contained mt-auto pb-7">
          <!-- <div class="absolute-with-bg "> -->
          <div class="superior flow">
            <!-- <div class="absolute-0 grid-center superior flow"> -->
            <span class="eyebrow">#visitgeorgia</span>
            <h1 class="heading ">
              Discover Unique Georgia
            </h1>
            <p class="hero__desc ">
              A country of ancient culture, where the breathtaking beauty of nature provides the perfect backdrop for infinite adventures and memorable experiences that will stay with you forever.
            </p>

            <div class="flex gap-1 pt-1">
              <a href="" class="btn btn--primary">Let's start planning →</a>
              <a href="" class="btn btn--ghost">Tell me more →</a>
            </div>
          </div>

          <div class="hero__video-controller video-controller flex mb-1">
            <button aria-label="Play the video" class="video-controller--play video-controller__btn">
              <ion-icon name="play"></ion-icon>
            </button>
            <button aria-label="Pause the video" class="video-controller--pause video-controller__btn">
              <ion-icon name="pause"></ion-icon>
            </button>
            <!-- is a spacer like the one in vuetify -->
            <div class="grow-1"></div>
            <button class="swiper-button-prev" aria-label="previous">
              <ion-icon name="play-skip-back"></ion-icon>
            </button>
            <button class="swiper-button-next">
              <ion-icon name="play-skip-forward"></ion-icon>
            </button>
          </div>

          <div class="video-controller__bar bar bar--extended">
            <span class="bar__line"></span>
          </div>
        </div>

      </section>


      <section class="pt-3">
        <h2 class="lead--large">Sea, mountains, resorts and culture, all in one place.<br> <b class="text-bold"> We’ve got you covered</b></h2>
      </section>


      <section id="top-attractions" class="pt-3">
        <div class="mb-1">
          <h2 class="contained section-title">Explore Top Attractions <a class="text-accent text-small" href="#">View all</a></h2>
        </div>

        <div class="">
          <div class="swiper swiper--b text-bold aaa">
            <div class="swiper-wrapper ">
              <div class="swiper-slide">
                <img src="uno.webp" alt="">
                <div class="bottom-text">
                  <p>ABUDELAURI LAKES</p>
                  <p>Natural Wonders</p>
                </div>
              </div>
              <div class="swiper-slide">
                <img src="dos.webp" alt="">
                <div class="bottom-text">
                  <p>PROMETHEUS CAVE</p>
                  <p>Natural Wonders</p>
                </div>
              </div>
              <div class="swiper-slide">
                <img src="tres.webp" alt="">
                <div class="bottom-text">
                  <p>TSALKA CANYON</p>
                  <p>Natural Wonders</p>
                </div>
              </div>
              <div class="swiper-slide">
                <img src="cuatro.webp" alt="">
                <div class="bottom-text">
                  <p>KORULDI LAKES</p>
                  <p>Natural Wonders</p>
                </div>
              </div>
              <div class="swiper-slide">
                <img src="seis.webp" alt="">
                <div class="bottom-text">
                  <p>SVETITSKHOVELI</p>
                  <p>Cultural Monuments</p>
                </div>
              </div>

            </div>
            <!-- <div class="swiper-pagination"></div> -->
          </div>
        </div>
      </section>





      <div class="none">
        <button id="find-me">Show my location</button><br />
        <p id="status"></p>
        <p id="map-link">
        </p>

      </div>




      <section id="explore-by-interest" class="contained pt-5">
        <h2 class="section-title mb-1">Explore by interest</h2>




        <ul class="interests ">
          <li class="interest">
            <div>
              <img alt="" class="" src="https://source.unsplash.com/500x500/?church,arquitecture">
              <a class="interest-link">Culture</a>
            </div>
          </li>
          <li class="interest">
            <div>
              <img alt="" class="" src="https://source.unsplash.com/500x500/?nature">
              <a class="interest-link">Relaxation</a>
            </div>
          </li>
          <li class="interest">
            <div>
              <img alt="" class="" src="https://source.unsplash.com/500x500/?food,drink">
              <a class="interest-link">Food & Drink</a>
            </div>
          </li>

          <li class="interest">
            <div>
              <img alt="" class="" src="https://source.unsplash.com/500x500/?art">
              <a class="interest-link">Art</a>
            </div>
          </li>
          <li class="interest">
            <div>
              <img alt="" class="" src="https://source.unsplash.com/500x500/?shopping">
              <a class="interest-link">Shopping</a>
            </div>
          </li>

          <li class="interest">
            <div>
              <img alt="" class="" src="https://source.unsplash.com/500x500/?adventure,mountain">
              <a class="interest-link">Adventure</a>
            </div>
          </li>
        </ul>

      </section>



      <section id="ig-section" class="contained pt-5 pb-5">
        <h2 class="section-title mb-1">Share your moments with us on Instagram! </h2>
        <ul class="image-gallery">
          <li>
            <img src="https://source.unsplash.com/500x500/?nature,water" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/500x400/?nature,water" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/400x400/?nature,mountain" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/300x300/?nature,sky" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/300x400/?nature,bugs" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/300x300/?nature,scenery" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/400x300/?nature,leaf" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/300x300/?nature,bird" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/300x300/?nature,trees" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/400x300/?nature,town" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li>
            <img src="https://source.unsplash.com/300x300/?nature,sunny" alt="">
            <div class="overlay"><ion-icon name="logo-instagram"></ion-icon></div>
          </li>
          <li aria-label="Visit Georgia">
          </li>
        </ul>

      </section>

      <!-- https://unsplash.com/es/fotos/-G3rw6Y02D0 -->
      <section class="contained  has-bg-image">
        <div class="mx grid-4-6">
          <div class="mb-1">
            <h2 class="section-title">All we are missing <b>is you</b></h2>
            <p class="">Choose from a wide range of places to stay and tours to enjoy for the ultimate Georgian travel experience.</p>
          </div>

          <form id="bookingForm" class="grid gap-1 grid--form">
            <div class="bg-gray tablet-grid-center">
              <label for="where">Where are you going</label>
              <input type="text" id="where" placeholder="anyplace in Georgia is fine">
            </div>

            <div class="bg-gray grid">
              <label for="depart">depart:</label>
              <input type="date" id="depart" name="depart">
              <label for="return">return:</label>
              <input type="date" id="return" name="return">
            </div>
            <div class="bg-gray grid">

              <div class="grid-7-3">
                <label for="number_adults">Number of Adults (16+ years):</label>

                <div class="date-container">
                  <input type="number" id="number_adults" name="number_adults" step="1" value="1" min="1">
                </div>
              </div>

              <div class="grid-7-3">
                <label for="number_children">Number of Children (0-15 years):</label>

                <div class="date-container">
                  <input type="number" id="number_children" name="number_children" step="1" value="0" min="0">
                </div>
              </div>

              <div class="grid-7-3">
                <label for="number_rooms">Number of rooms (0-30):</label>

                <div class="date-container">
                  <input type="number" id="number_rooms" name="number_rooms" step="1" value="1" max="30" min="1">
                </div>
              </div>
            </div>

            <button class="btn btn--primary" type="button" onclick="generateLink()">Georgia, here I go</button>
          </form>
        </div>

      </section>




    </main>






    <footer class="py-3 border-top mt-2">

      <ul class="autogrid contained">
        <li class="">
          <h3 class="text-large">
            THINGS TO DO
          </h3>
          <ul>
            <li><a href="#">Culture</a></li>
            <li><a href="#">Relaxation</a></li>
            <li><a href="#">Food & Drink</a></li>
            <li><a href="#">Art</a></li>
            <li><a href="#">Shopping</a></li>
            <li><a href="#">Adventure</a></li>
            <li><a href="#">Thermalism</a></li>
            <li><a href="#">Festivals</a></li>
          </ul>
        </li>
        <li class="">
          <h3 class="text-large">
            USEFUL INFO
          </h3>
          <ul>
            <li><a href="#">Coming to Georgia</a></li>
            <li><a href="#">Regions</a></li>
            <li><a href="#">Georgia Map</a></li>
            <li><a href="#">Press & Media</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Popular Trips</a></li>
            <li><a href="#">FAQ</a></li>
          </ul>
        </li>
        <li class="">
          <h3 class="">

            CONTACT
          </h3>
          <address>
            <span>Dirección: 123 Sanapiro Street. 0123</span>
            <a href="tel:+">0 999 999 999</a>
            <a href="mailto:">0123@notgeorgia.travel</a>
          </address>
        </li>
        <li class="">
          <h3 class="">

            SOCIAL MEDIA
          </h3>
          <ul>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Instagram</a></li>
            <li><a href="#">Youtube</a></li>
          </ul>
        </li>
      </ul>



      <div class="contained py-3 text-center">
        <span class="lead--large">Thanks for visiting our website</span>
        <p>We hope to see you soon</p>
      </div>


      <div class="contained py-3 autogrid ">
        <div class="pb-1">
          <h2 class="section-title">Get your Georgia full guide </h2>
          <p>We are releasing the full guide to Georgia in n days</p>
          <p>If you would like to know all from this to that about Georgia, leave your email here:</p>
        </div>

        <div class="grid align-content-center">
          <div class="input-and-btn outlined rounded">
            <input type="email" name="" id="" placeholder="Your best email">
            <button type="button" class="btn btn--ghost">+ waiting list</button>
          </div>
          <!-- <label for="receiveOtherEmails"></label>
        <input type="checkbox" name="receiveOtherEmails" id="receiveOtherEmails"> -->
        </div>
      </div>



    </footer>

  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>

<!-- 

  ionicons vue
 -->
