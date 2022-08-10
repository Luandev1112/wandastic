<template>
  <section class="video-one" style="background-image:url(/assets/images/resources/video-bg-1.jpg);">
    <div class="container text-center">
      <a href="https://www.youtube.com/watch?v=i9E_Blai8vk" class="video-one__btn videoOne"><i
        class="fa fa-play"></i></a>
      <p>Modern agriculture types</p>
      <h3>Agriculture matters to the<br>future of development</h3>
    </div>
  </section>
</template>

<script>
    export default {
      name: "VideoOne",
      mounted() {
        new GLightbox({
          selector: '.videoOne',
          touchNavigation: true,
          loop: true,
          autoplayVideos: true
        });
      }

    }
</script>

<style scoped>

</style>
