<template>
  <section class="faq_one">
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6">
          <div class="faq_one_left">
            <div class="block-title text-left">
              <p>frequently asked questions</p>
              <h3>have any question?</h3>
              <div class="leaf">
                <img src="/assets/images/resources/leaf.png" alt="">
              </div>
            </div>
            <div class="faq_one_image"
                 style="background-image: url(/assets/images/resources/faq_one_img-1.jpg)">
              <div class="phone_number">
                <p>If you have emergency call nows<a href="tel:888-999-0000">666 888 0000</a></p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6">
          <div class="faq_one_right">
            <div class="accrodion-grp" data-grp-name="faq-one-accrodion">
              <div class="accordion-container-one">
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">Why are your tours so expensive?</h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">Suspendisse finibus urna mauris, vitae consequat quam vel. Vestibulum leo
                      ligula, molestie ullamcorper vulputate vitae sodales commodo nisl. Nulla
                      facilisi. Pellentesque est metus many of eration in some form.
                    </p>
                  </div>
                </div>

                <div class="ac accordion__content">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">Which payment methods are acceptable?</h2>
                  <div class="ac-a">
                    <p class="accordion__content-desc">Suspendisse finibus urna mauris, vitae consequat quam vel. Vestibulum leo
                      ligula, molestie ullamcorper vulputate vitae sodales commodo nisl. Nulla
                      facilisi. Pellentesque est metus many of eration in some form.
                    </p>
                  </div>
                </div>

                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">How to book the new tour for 2 persons?</h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">Suspendisse finibus urna mauris, vitae consequat quam vel. Vestibulum leo
                      ligula, molestie ullamcorper vulputate vitae sodales commodo nisl. Nulla
                      facilisi. Pellentesque est metus many of eration in some form.
                    </p>
                  </div>
                </div>

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
      name: "FaqOne",
      mounted() {
        new Accordion('.accordion-container-one');
      }
    }
</script>

<style scoped>
  .ac {
    margin-top: 10px;
    padding: 10px;
    background: #FFFFFF;
    box-sizing: border-box;
  }

  .ac>.ac-q {
    font-size: 20px;
    color: #444;
    padding: 10px 30px 10px 10px;
    margin: 0;
    text-decoration: none;
    display: block;
    cursor: pointer;
    position: relative;
    font-weight: 400;
    font-family: var(--heading-font);
  }

  .ac.is-active .ac-q {
    color: #5a8b50 !important;
  }
  .ac>.ac-q::after {
    content: '+';
    text-align: center;
    width: 15px;
    right: 10px;
    top: 50%;
    -webkit-transform: translate(0, -50%);
    transform: translate(0, -50%);
    position: absolute
  }

  .ac>.ac-a {
    overflow: hidden;
    -webkit-transition-property: all;
    transition-property: all;
    -webkit-transition-timing-function: ease;
    transition-timing-function: ease
  }

  .ac>.ac-a p {
    color: #878e9c;
    margin: 0;
    padding: 10px;
    font-size: 16px;
    font-weight: 400;
  }

  .ac.js-enabled>.ac-a {
    visibility: hidden
  }

  .ac.is-active>.ac-a {
    visibility: visible
  }

  .ac.is-active>.ac-q::after {
    content: '\2013';
    color: #5a8b50;
  }
</style>
