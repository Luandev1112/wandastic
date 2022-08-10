<template>
  <section class="funfact_one" v-observe-visibility="onVisibilityChange">
    <div class="container">
        <ul class="counter_one_box list-unstyled">
            <li class="funfact_one_single wow fadeInLeft" data-wow-delay="300ms">
                <div class="funfact_one_icon">
                    <i class="icon-watering"></i>
                </div>
                <h3><span class="counter"><countTo :startVal='0' :endVal='startCounter ? 5493 : 0' :duration='3000'></countTo></span></h3>
                <p>Projects</p>
            </li>
            <li class="funfact_one_single wow fadeInLeft" data-wow-delay="600ms">
                <div class="funfact_one_icon">
                    <i class="icon-wheelbarrow"></i>
                </div>
                <h3><span class="counter"><countTo :startVal='0' :endVal='startCounter ? 1750 : 0' :duration='3000'></countTo></span></h3>
                <p>products</p>
            </li>
            <li class="funfact_one_single wow fadeInLeft" data-wow-delay="900ms">
                <div class="funfact_one_icon">
                    <i class="icon-customer-review"></i>
                </div>
                <h3><span class="counter"><countTo :startVal='0' :endVal='startCounter ? 2458 : 0' :duration='3000'></countTo></span></h3>
                <p>satisfied</p>
            </li>
            <li class="funfact_one_single wow fadeInLeft" data-wow-delay="1200ms">
                <div class="funfact_one_icon">
                    <i class="icon-meeting"></i>
                </div>
                <h3><span class="counter"><countTo :startVal='0' :endVal='startCounter ? 1670 : 0' :duration='3000'></countTo></span></h3>
                <p>community</p>
            </li>
        </ul>
    </div>
</section>
</template>

<script>
  import countTo from 'vue-count-to';
  import { ObserveVisibility } from 'vue-observe-visibility'
    export default {
      name: "FunfactOne",
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
