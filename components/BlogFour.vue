<template>
  <section class="blog_four">
    <div class="container">
      <div class="row">
        <div class="col-xl-4 col-lg-4 wow fadeInUp" data-wow-delay="100ms">
          <div class="block-title text-left">
            <p>from the blog</p>
            <h3>blog posts And<br>articles Updated<br>Daily</h3>
            <div class="leaf">
              <img src="/assets/images/resources/leaf.png" alt="">
            </div>
          </div>
          <div class="blog-four_btn">
            <a href="" class="thm-btn">View All News</a>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="blog_four_single wow fadeInLeft" data-wow-delay="300ms">
            <div class="blog_four_image">
              <img src="/assets/images/blog/blog-4-img-1.jpg" alt="">
              <div class="blog_four_date_box">
                <p>30 Oct, 2019</p>
              </div>
            </div>
            <div class="blog-four_content">
              <ul class="list-unstyled blog-four_meta">
                <li><nuxt-link to="/news_detail"><i class="far fa-user-circle"></i> Admin</nuxt-link></li>
                <li><nuxt-link to="/news_detail"><i class="far fa-comments"></i> 2 Comments</nuxt-link></li>
              </ul>
              <h3><nuxt-link to="/news_detail" class="blog_four_title">Agriculture Miracle you<br>Don't
                Know About</nuxt-link></h3>
              <div class="blog_four_read_more_btn">
                <nuxt-link to="/news_detail"><i class="fa fa-angle-right"></i>Read More</nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="blog_four_single wow fadeInLeft" data-wow-delay="600ms">
            <div class="blog_four_image">
              <img src="/assets/images/blog/blog-4-img-2.jpg" alt="">
              <div class="blog_four_date_box">
                <p>30 Oct, 2019</p>
              </div>
            </div>
            <div class="blog-four_content">
              <ul class="list-unstyled blog-four_meta">
                <li><nuxt-link to="/news_detail"><i class="far fa-user-circle"></i> Admin</nuxt-link></li>
                <li><nuxt-link to="/news_detail"><i class="far fa-comments"></i> 2 Comments</nuxt-link></li>
              </ul>
              <h3><nuxt-link to="/news_detail" class="blog_four_title">Winter Wheat Harvest
                Gathering<br>Momentum</nuxt-link></h3>
              <div class="blog_four_read_more_btn">
                <nuxt-link to="/news_detail"><i class="fa fa-angle-right"></i>Read More</nuxt-link>
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
      name: "BlogFour"
    }
</script>

<style scoped>

</style>
