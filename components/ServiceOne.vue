<template>
  <section class="service_one">
    <div class="container">
      <div class="block-title text-center">
        <p>What we do</p>
        <h3>Services We Offer</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-3 col-lg-3 col-md-6">
          <div class="service_1_single wow fadeInUp">
            <div class="content">
              <h3>Fresh<br>vegetables</h3>
              <p>Lorem ipsum is simply are many variations of pass of majority.</p>
            </div>
            <div class="service_1_img">
              <img src="/assets/images/service/service-1-img-1.jpg" alt="Service Image">
              <div class="hover_box">
                <nuxt-link to="/service-detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-3 col-md-6">
          <div class="service_1_single wow fadeInUp" data-wow-delay="300ms">
            <div class="content">
              <h3>Fresh<br>vegetables</h3>
              <p>Lorem ipsum is simply are many variations of pass of majority.</p>
            </div>
            <div class="service_1_img">
              <img src="/assets/images/service/service-1-img-2.jpg" alt="Service Image">
              <div class="hover_box">
                <nuxt-link to="/service-detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-3 col-md-6">
          <div class="service_1_single wow fadeInUp" data-wow-delay="600ms">
            <div class="content">
              <h3>Fresh<br>vegetables</h3>
              <p>Lorem ipsum is simply are many variations of pass of majority.</p>
            </div>
            <div class="service_1_img">
              <img src="/assets/images/service/service-1-img-3.jpg" alt="Service Image">
              <div class="hover_box">
                <nuxt-link to="/service-detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-3 col-md-6">
          <div class="service_1_single wow fadeInUp" data-wow-delay="900ms">
            <div class="content">
              <h3>Fresh<br>vegetables</h3>
              <p>Lorem ipsum is simply are many variations of pass of majority.</p>
            </div>
            <div class="service_1_img">
              <img src="/assets/images/service/service-1-img-4.jpg" alt="Service Image">
              <div class="hover_box">
                <nuxt-link to="/service-detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ServiceOne"
    }
</script>

<style scoped>

</style>
