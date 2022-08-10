<template>
  <section class="get_quote">
    <div class="container">
      <div class="inner-container">
        <div class="row no-gutters">
          <div class="col-xl-8">
            <form action="#" class="get_quote_one__form">
              <div class="get_quote_one_form_inner">
                <h3>Get a Free Quote</h3>
                <div class="row">
                  <div class="col-md-6">
                    <div class="input_box">
                      <input type="text" name="name" placeholder="Full name">
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="input_box">
                      <input type="text" name="email" placeholder="Email Address">
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="input_box">
                      <input type="text" name="phone" placeholder="Phone">
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="input_box">
                      <input type="text" name="subject" placeholder="Subject">
                    </div>
                  </div>
                  <div class="col-md-12">
                    <div class="input_box">
                      <textarea name="message" placeholder="Write Message"></textarea>
                    </div>
                  </div>
                  <div class="col-md-12">
                    <div class="input_box">
                      <button type="submit" class="thm-btn get_quote__btn">Send a
                        Request</button>
                    </div>
                  </div>
                </div>
              </div>
            </form>
          </div>
          <div class="col-xl-4">
            <div class="get_quote_right"
                 style="background-image: url(/assets/images/resources/get_quote_bg.jpg)">
              <h3>Looking<br> for agriculture,<br> organic & eco<br> Services</h3>
            </div>
          </div>
        </div>
      </div><!-- /.inner-container -->

    </div>
  </section>
</template>

<script>
    export default {
        name: "GetQuote"
    }
</script>

<style scoped>

</style>
