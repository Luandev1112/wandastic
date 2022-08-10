<template>
  <section class="welcome_one">
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6">
          <div class="block-title text-left">
            <p>Welcome to agrikol</p>
            <h3>We’re leading organic & agriculture company in Canada</h3>
            <div class="leaf">
              <img src="/assets/images/resources/leaf.png" alt="">
            </div>
          </div>
          <div class="growing_box">
            <div class="growing_icon_box">
              <span class="icon-harvest"></span>
            </div>
            <div class="growing_text">
              <p>We’re growing the best Fruits and Vegetables</p>
            </div>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6">
          <div class="welcome_text">
            <p>There are many variations of passages of Lorem Ipsum available, but the majority have
              suffered alteration in some form, by injected humour, or randomised words which don't
              look even slightly believable.</p>
          </div>
          <div class="welcome_video_box"
               style="background-image:url(/assets/images/resources/welcome_video_bg.jpg)">
            <a href="https://www.youtube.com/watch?v=i9E_Blai8vk"
               class="welcome_video_btn videoTwo"><i class="fa fa-play"></i></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
      name: "WelcomeOne",
      mounted() {
        new GLightbox({
          selector: '.videoTwo',
          touchNavigation: true,
          loop: true,
          autoplayVideos: true
        });
      }
    }
</script>

<style scoped>

</style>
