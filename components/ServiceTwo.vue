<template>
  <section class="service_two">
    <div class="container">
      <div class="block-title text-center">
        <p>What we do</p>
        <h3>Services We Offer</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-12">
          <ul class="service_2_top list-unstyled">
            <li class="service_2_single wow fadeInUp">
              <div class="service_2_image">
                <img src="/assets/images/service/service-2-img-1.png" alt="Service-2 Image">
              </div>
              <h3><nuxt-link to="/service-detail">fresh<br>vegetables</nuxt-link></h3>
            </li>
            <li class="service_2_single wow fadeInUp" data-wow-delay="300ms">
              <div class="service_2_image">
                <img src="/assets/images/service/service-2-img-2.png" alt="Service-2 Image">
              </div>
              <h3><nuxt-link to="/service-detail">Agriculture<br>products</nuxt-link></h3>
            </li>
            <li class="service_2_single wow fadeInUp" data-wow-delay="600ms">
              <div class="service_2_image">
                <img src="/assets/images/service/service-2-img-3.png" alt="Service-2 Image">
              </div>
              <h3><nuxt-link to="/service-detail">organic<br>products</nuxt-link></h3>
            </li>
            <li class="service_2_single wow fadeInUp" data-wow-delay="900ms">
              <div class="service_2_image">
                <img src="/assets/images/service/service-2-img-4.png" alt="Service-2 Image">
              </div>
              <h3><nuxt-link to="/service-detail">dairy<br>products</nuxt-link></h3>
            </li>
          </ul>
        </div>
      </div>
      <hr>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ServiceTwo"
    }
</script>

<style scoped>

</style>
