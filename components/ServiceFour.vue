<template>
  <section class="service_four">
    <div class="container">
      <div class="service_four_top"></div>
      <div class="block-title text-center">
        <p>What we do</p>
        <h3>Services We Offer</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-4 col-lg-4">
          <div class="service_four_single wow fadeInLeft" data-wow-delay="300ms">
            <div class="service_four_icon">
              <span class="icon-temperature"></span>
            </div>
            <div class="service_four_deatils">
              <h3><nuxt-link to="/service-detail" class="service_four_title">fresh vegetables</nuxt-link></h3>
              <p>There are many variations of passages of available, but the majority have suffered.
              </p>
            </div>
            <div class="service_four_read_more">
              <nuxt-link to="/service-detail"><span class="icon-left-arrow"></span></nuxt-link>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="service_four_single wow fadeInLeft" data-wow-delay="600ms">
            <div class="service_four_icon">
              <span class="icon-harvest"></span>
            </div>
            <div class="service_four_deatils">
              <h3><nuxt-link to="/service-detail" class="service_four_title">agriculture products</nuxt-link>
              </h3>
              <p>There are many variations of passages of available, but the majority have suffered.
              </p>
            </div>
            <div class="service_four_read_more">
              <nuxt-link to="/service-detail"><span class="icon-left-arrow"></span></nuxt-link>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="service_four_single wow fadeInLeft" data-wow-delay="900ms">
            <div class="service_four_icon">
              <span class="icon-growth"></span>
            </div>
            <div class="service_four_deatils">
              <h3><nuxt-link to="/service-detail" class="service_four_title">organic products</nuxt-link></h3>
              <p>There are many variations of passages of available, but the majority have suffered.
              </p>
            </div>
            <div class="service_four_read_more">
              <nuxt-link to="/service-detail"><span class="icon-left-arrow"></span></nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ServiceFour"
    }
</script>

<style scoped>

</style>
