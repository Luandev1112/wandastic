<template>
  <section class="bx-testimonial">
    <div class="bx-testimonial_bg" style="background-image: url(/assets/images/testimonials/bx-testi-bg.png)">
    </div>
    <div class="container">
      <div class="block-title text-center">
        <p>our team members</p>
        <h3>meet the farmers</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-12">
          <div class="bx_testimonial_slider">
            <div class="slider-pager">
              <ul class="thumb-box list-unstyled text-center">
                <li>
                  <a class="active" data-slide-index="0" href="#">
                    <div class="img-holder">
                      <img src="/assets/images/testimonials/bx-testi-1.png" alt="">
                      <div class="quote_testimonial">
                        <img src="/assets/images/icon/quote_1.png" alt="">
                      </div>
                    </div>
                  </a>
                </li>
                <li>
                  <a data-slide-index="1" href="#">
                    <div class="img-holder">
                      <img src="/assets/images/testimonials/bx-testi-2.png" alt="">
                      <div class="quote_testimonial">
                        <img src="/assets/images/icon/quote_1.png" alt="">
                      </div>
                    </div>
                  </a>
                </li>
                <li>
                  <a data-slide-index="2" href="#">
                    <div class="img-holder">
                      <img src="/assets/images/testimonials/bx-testi-3.png" alt="">
                      <div class="quote_testimonial">
                        <img src="/assets/images/icon/quote_1.png" alt="">
                      </div>
                    </div>
                  </a>
                </li>
              </ul>
            </div>

            <ul class="slider-content clearfix bxslider list-unstyled text-center">
              <no-ssr>
                <carousel :items="1" :autoplay="true" :nav="false" :dots="false">
              <li>
                <div class="bx_testimonial_single clearfix">
                  <div class="bx_testimonial_text">
                    <p>This is due to their excellent service, competitive pricing and customer
                      support. It’s throughly refresing to get such a personal touch.</p>
                    <h3>christine rose</h3>
                    <h6>Customer</h6>
                  </div>
                </div>
              </li>
              <li>
                <div class="bx_testimonial_single clearfix">
                  <div class="bx_testimonial_text">
                    <p>This is due to their excellent service, competitive pricing and customer
                      support. It’s throughly refresing to get such a personal touch.</p>
                    <h3>christine rose</h3>
                    <h6>Customer</h6>
                  </div>
                </div>
              </li>
              <li>
                <div class="bx_testimonial_single clearfix">
                  <div class="bx_testimonial_text">
                    <p>This is due to their excellent service, competitive pricing and customer
                      support. It’s throughly refresing to get such a personal touch.</p>
                    <h3>christine rose</h3>
                    <h6>Customer</h6>
                  </div>
                </div>
              </li>
                </carousel>
              </no-ssr>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "TestimonialFour"
    }
</script>

<style scoped>

</style>
