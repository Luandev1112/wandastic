<template>
  <section class="contact-one">
    <div class="container">
      <div class="row">
        <div class="col-xl-7">
          <div class="contact-one__form__wrap">
            <div class="block-title text-left">
              <p>contact with us</p>
              <h3>write us a message</h3>
              <div class="leaf">
                <img src="/assets/images/resources/leaf.png" alt="">
              </div>
            </div>
            <form action="#" class="contact-one__form">
              <div class="row low-gutters">
                <div class="col-md-6">
                  <div class="input-group">
                    <input type="text" name="name" placeholder="Your Name">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-group">
                    <input type="text" name="email" placeholder="Email Address">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-group">
                    <input type="text" name="phone" placeholder="Phone Number">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-group">
                    <input type="text" name="subject" placeholder="Subject">
                  </div>
                </div>
                <div class="col-md-12">
                  <div class="input-group">
                    <textarea name="message" placeholder="Write Message"></textarea>
                  </div>
                </div>
                <div class="col-md-12">
                  <div class="input-group contact__btn">
                    <button type="submit" class="thm-btn contact-one__btn">Send message</button>
                  </div>
                </div>
              </div>
            </form>
          </div>
        </div>
        <div class="col-xl-5">
          <div class="have_questions">
            <div class="image_box">
              <img src="/assets/images/resources/contact_img.jpg" alt="">
            </div>
            <div class="block-title text-center">
              <p>get in touch with us</p>
              <h3>Have question?</h3>
              <div class="leaf">
                <img src="/assets/images/resources/leaf.png" alt="">
              </div>
            </div>
            <div class="have_questions_text">
              <p>There are many variations of passages available but the majority have suffered
                alteration in some form by inject humour or donec vel erat sollicitudin, dapibus dui
                at, porttitor sem.</p>
            </div>
            <div class="have_questions_btn">
              <a href="#" class="thm-btn">Learn More</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ContactTwo"
    }
</script>

<style scoped>

</style>
