<template>
  <section class="bx-testimonial bx-testimonial2">
    <div class="container">

      <div class="row">
        <div class="col-xl-12">
          <div class="bx_testimonial_slider">
            <div class="bx-testimonial_title">Testimonials</div>
            <div class="slider-pager">
              <ul class="thumb-box list-unstyled text-center">
                <no-ssr>
                  <carousel :items="1" :autoplay="true" :nav="false" :dots="false">
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
                  </carousel>
                </no-ssr>
              </ul>
            </div>

            <ul class="slider-content clearfix bxslider list-unstyled text-center">
              <no-ssr>
                <carousel :items="1" :autoplay="true" :nav="false">
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
        name: "TestimonialTwo"
    }
</script>

<style scoped>

</style>
