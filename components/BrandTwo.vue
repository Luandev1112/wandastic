<template>
  <div class="brand-one brand-two">
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <div class="brand-one-carousel owl-carousel">
            <no-ssr>
              <carousel :autoplay="true" :dots="false" :nav="false" :responsive="{0: {items: 1},640: {items: 2},992: {items: 3},1024: {items: 5}}">
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-1.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-2.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-3.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-4.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-5.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-1.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-2.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-3.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-4.png" alt="brand"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-2-5.png" alt="brand"></a>
            </div>
              </carousel>
            </no-ssr>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "BrandTwo"
    }
</script>

<style scoped>

</style>
