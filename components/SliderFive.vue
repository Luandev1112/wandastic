<template>
  <section class="banner-section banner-five">
    <div class="round_1">
      <img src="/assets/images/main-slider/round_1.png" alt="">
    </div>
    <div class="round_2">
      <img src="/assets/images/main-slider/round_2.png" alt="">
    </div>
    <div class="certified_logo">
      <img src="/assets/images/main-slider/certified_logo.png" alt="">
    </div>
    <div class="banner-carousel five owl-theme owl-carousel">
      <no-ssr>
        <carousel :items="1" :autoplay="true" :nav="false">
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="banner_five_bg"
             style="background-image: url(/assets/images/main-slider/banner-five-bg.jpg)"></div>
        <div class="container">
          <div class="row content-box">
            <div class="col-xl-5 content">
              <div class="inner">
                <div class="large-title">organic &<br> agriculture<br> Forming</div>
                <p>An qualisque constituam cum. Agam unum disputando ius et, mel id postea voluptua,
                  et vel assum graece feugait.</p>
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
        <div class="banner_five_bg"
             style="background-image: url(/assets/images/main-slider/banner-five-bg.jpg)"></div>
        <div class="container">
          <div class="row content-box">
            <div class="col-xl-5 content">
              <div class="inner">
                <div class="large-title">organic &<br> agriculture<br> Forming</div>
                <p>An qualisque constituam cum. Agam unum disputando ius et, mel id postea voluptua,
                  et vel assum graece feugait.</p>
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
        <div class="banner_five_bg"
             style="background-image: url(/assets/images/main-slider/banner-five-bg.jpg)"></div>
        <div class="container">
          <div class="row content-box">
            <div class="col-xl-5 content">
              <div class="inner">
                <div class="large-title">organic &<br> agriculture<br> Forming</div>
                <p>An qualisque constituam cum. Agam unum disputando ius et, mel id postea voluptua,
                  et vel assum graece feugait.</p>
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
        name: "SliderFive"
    }
</script>

<style scoped>

</style>
