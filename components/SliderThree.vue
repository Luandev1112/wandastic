<template>
  <section class="banner-section banner-three">

    <div class="banner-carousel-three owl-theme owl-carousel">
      <no-ssr>
        <carousel :items="1" :autoplay="true" :nav="false">
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v3_1.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <div class="big_text">
                  <h2>Agriculture Forming</h2>
                </div>
                <div class="sub-title">An qualisque constituam cum. Agam unum disputando ius et, mel
                  id<br>postea voluptua, et vel assum graece feugait.</div>
                <div class="link-box">
                  <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v3_2.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <div class="big_text">
                  <h2>Agriculture Forming</h2>
                </div>
                <div class="sub-title">An qualisque constituam cum. Agam unum disputando ius et, mel
                  id<br>postea voluptua, et vel assum graece feugait.</div>
                <div class="link-box">
                  <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
        </carousel>
      </no-ssr>
    </div>
  </section>
</template>

<script>

    export default {
      name: "SliderThree",
      data(){
          return {

          }
      }
    }
</script>

<style scoped>

</style>
