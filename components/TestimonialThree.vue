<template>
  <section class="testimonials-three">
    <div class="container">
      <div class="block-title text-center">
        <p>testimonails</p>
        <h3>What people say</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="testimonials-three__carousel thm__owl-carousel light-dots owl-carousel">
        <no-ssr>
          <carousel :autoplay="true" :margin="30" :dots="false" :nav="false" :responsive="{0: {items: 1},640: {items: 2},992: {items: 3},1024: {items: 3}}">

          <div class="item">
          <div class="testimonials-three__single">
            <div class="testimonials-three__content">
              <div class="testimonials-three_icon">
                <img src="/assets/images/shapes/testi-qoute-3-1.png" alt="">
              </div>
              <p>There are many variations of passages of lorem ipsum but the majority have alteration
                in some form, by randomised words look.</p>
            </div>
            <div class="testimonials-three__info">
              <img src="/assets/images/testimonials/testimonial-3-img-1.png" alt="">
              <h3>Kevin Smith</h3>
              <p>founder</p>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="testimonials-three__single">
            <div class="testimonials-three__content">
              <div class="testimonials-three_icon">
                <img src="/assets/images/shapes/testi-qoute-3-1.png" alt="">
              </div>
              <p>There are many variations of passages of lorem ipsum but the majority have alteration
                in some form, by randomised words look.</p>
            </div>
            <div class="testimonials-three__info">
              <img src="/assets/images/testimonials/testimonial-3-img-2.png" alt="">
              <h3>jessica brown</h3>
              <p>founder</p>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="testimonials-three__single">
            <div class="testimonials-three__content">
              <div class="testimonials-three_icon">
                <img src="/assets/images/shapes/testi-qoute-3-1.png" alt="">
              </div>
              <p>There are many variations of passages of lorem ipsum but the majority have alteration
                in some form, by randomised words look.</p>
            </div>
            <div class="testimonials-three__info">
              <img src="/assets/images/testimonials/testimonial-3-img-1.png" alt="">
              <h3>Kevin Smith</h3>
              <p>founder</p>
            </div>
          </div>
        </div>
        <div class="item">
          <div class="testimonials-three__single">
            <div class="testimonials-three__content">
              <div class="testimonials-three_icon">
                <img src="/assets/images/shapes/testi-qoute-3-1.png" alt="">
              </div>
              <p>There are many variations of passages of lorem ipsum but the majority have alteration
                in some form, by randomised words look.</p>
            </div>
            <div class="testimonials-three__info">
              <img src="/assets/images/testimonials/testimonial-3-img-3.png" alt="">
              <h3>daniyal coper</h3>
              <p>founder</p>
            </div>
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
        name: "TestimonialThree"
    }
</script>

<style scoped>

</style>
