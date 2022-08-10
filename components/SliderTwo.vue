<template>
  <section class="banner-section banner-two">

    <div class="banner-carousel-two owl-theme owl-carousel">
      <no-ssr>
        <carousel :items="1" :autoplay="true" :nav="false">
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v2_1.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <div class="sub-title">Welcome to agriculture form</div>
                <div class="big_text">
                  <h2>agrikol products</h2>
                </div>
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
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v2_2.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <div class="sub-title">Welcome to agriculture form</div>
                <div class="big_text">
                  <h2>agrikol products</h2>
                </div>
                <div class="link-box">
                  <nuxt-link to="/product" class="thm-btn">Discover More</nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v2_1.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content">
              <div class="inner">
                <div class="sub-title">Welcome to agriculture form</div>
                <div class="big_text">
                  <h2>agrikol products</h2>
                </div>
                <div class="link-box">
                  <nuxt-link to="/product" class="thm-btn">Discover More</nuxt-link>
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
    name: "SliderTwo",
    data(){
      return {

      }
    }
  }
</script>

<style scoped>

</style>
