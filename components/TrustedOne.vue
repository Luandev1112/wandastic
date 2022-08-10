<template>
  <section class="trusted_one" style="background-image: url(/assets/images/resources/trusted_one_bg.jpg)" v-observe-visibility="onVisibilityChange">
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6">
          <div class="trusted_one_text">
            <h2>Our agrikol trusted by<br>more than<span class="counter"><countTo :startVal='0' :endVal='startCounter ? 98750 : 0' :duration='3000'></countTo></span> <br>clients</h2>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6">
          <ul class="trusted_one_counter_box list-unstyled wow fadeInRight" data-wow-delay="100ms">
            <li class="trusted_one_couter_single">
              <div class="trusted_one_couter_icon">
                <i class="icon-watering"></i>
              </div>
              <h3><span class="counter"><countTo :startVal='0' :endVal='startCounter ? 5493 : 0' :duration='3000'></countTo></span></h3>
              <p>Projects</p>
            </li>
            <li class="trusted_one_couter_single">
              <div class="trusted_one_couter_icon">
                <i class="icon-wheelbarrow"></i>
              </div>
              <h3><span class="counter"><countTo :startVal='0' :endVal='startCounter ? 1750 : 0' :duration='3000'></countTo></span></h3>
              <p>products</p>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  import countTo from 'vue-count-to';
  import { ObserveVisibility } from 'vue-observe-visibility'
  export default {
    name: "TrustedOne",
    components: { countTo },
    directives: {
      ObserveVisibility
    },
    data() {
      return{
        startCounter: false
      }
    },
    methods: {
      onVisibilityChange (isVisible) {
        if (isVisible){
          this.startCounter = true;
        }

      },
    }
  }
</script>


<style scoped>

</style>
