<template>
  <section class="banner_four_section">

    <div class="banner-carousel-four owl-theme owl-carousel">
      <no-ssr>
        <carousel :items="1" :autoplay="true" :nav="false">
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v4_1.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content text-right">
              <div class="inner">
                <h1><span>Organic</span> farming<br> is better for the<br> environment</h1>
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
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v4_2.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content text-right">
              <div class="inner">
                <h1><span>Organic</span> farming<br> is better for the<br> environment</h1>
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
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v4_1.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content text-right">
              <div class="inner">
                <h1><span>Organic</span> farming<br> is better for the<br> environment</h1>
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
      name: "SliderFour"
    }
</script>

<style scoped>

</style>
