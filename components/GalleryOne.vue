<template>
  <section class="gallery_one">
    <div class="container-fullwidth">
      <div class="block-title text-center">
        <p>our gallery</p>
        <h3>checkout gallery</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="gallery_one_carousel owl-carousel">
        <no-ssr>
          <carousel :margin="30" :autoplay="true" :dots="false" :nav="false" :responsive="{0: {items: 1},640: {items: 2},992: {items: 3},1024: {items: 5}}">
        <!--Gallery One Single-->
        <div class="gallery_one_single wow fadeInLeft" data-wow-delay="300ms">
          <div class="gallery_one_image">
            <img src="/assets/images/gallery/gallery-1-img-1.jpg" alt="">
          </div>
        </div>
        <!--Gallery One Single-->
        <div class="gallery_one_single wow fadeInLeft" data-wow-delay="600ms">
          <div class="gallery_one_image">
            <img src="/assets/images/gallery/gallery-1-img-2.jpg" alt="">
          </div>
        </div>
        <!--Gallery One Single-->
        <div class="gallery_one_single wow fadeInLeft" data-wow-delay="900ms">
          <div class="gallery_one_image">
            <img src="/assets/images/gallery/gallery-1-img-3.jpg" alt="">
          </div>
        </div>
        <!--Gallery One Single-->
        <div class="gallery_one_single wow fadeInLeft" data-wow-delay="1200ms">
          <div class="gallery_one_image">
            <img src="/assets/images/gallery/gallery-1-img-4.jpg" alt="">
          </div>
        </div>
        <!--Gallery One Single-->
        <div class="gallery_one_single wow fadeInLeft" data-wow-delay="1400ms">
          <div class="gallery_one_image">
            <img src="/assets/images/gallery/gallery-1-img-5.jpg" alt="">
          </div>
        </div>
          </carousel>
        </no-ssr>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
      name: "GalleryOne",
      mounted() {
        new GLightbox({
          selector: '.glightbox',
        });
      }
    }
</script>

<style scoped>

</style>
