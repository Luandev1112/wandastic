<template>
  <section class="blog-one">
    <div class="container">
      <div class="block-title text-center">
        <p>from the blog</p>
        <h3>News & Articles</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-4 col-lg-4">
          <div class="blog_one_single wow fadeInUp" data-wow-delay="300ms">
            <div class="blog_one_image">
              <div class="blog_image">
                <img src="/assets/images/blog/blog-1-img-1.jpg" alt="Blog One Image">
                <div class="blog_one_date_box">
                  <p>30 Oct, 2019</p>
                </div>
              </div>
              <div class="blog-one__content">
                <ul class="list-unstyled blog-one__meta">
                  <li><nuxt-link to="/news_detail"><i class="far fa-user-circle"></i> Admin</nuxt-link></li>
                  <li><nuxt-link to="/news_detail"><i class="far fa-comments"></i> 2 Comments</nuxt-link>
                  </li>
                </ul>
                <h3><nuxt-link to="/news_detail">Agriculture Miracle you<br>Don't Know About</nuxt-link></h3>
                <div class="blog_one_text">
                  <p>There are lorem ipsum is simply free many variations of ipsum the majority
                    suffered.</p>
                </div>
                <div class="read_more_btn">
                  <nuxt-link to="/news_detail"><i class="fa fa-angle-right"></i>Read More</nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="blog_one_single wow fadeInUp" data-wow-delay="600ms">
            <div class="blog_one_image">
              <div class="blog_image">
                <img src="/assets/images/blog/blog-1-img-2.jpg" alt="Blog One Image">
                <div class="blog_one_date_box">
                  <p>30 Oct, 2019</p>
                </div>
              </div>
              <div class="blog-one__content">
                <ul class="list-unstyled blog-one__meta">
                  <li><nuxt-link to="/news_detail"><i class="far fa-user-circle"></i> Admin</nuxt-link></li>
                  <li><nuxt-link to="/news_detail"><i class="far fa-comments"></i> 2 Comments</nuxt-link>
                  </li>
                </ul>
                <h3><nuxt-link to="news_detail.html">Amount of Freak Bread<br>or Other Fruits</nuxt-link></h3>
                <div class="blog_one_text">
                  <p>There are lorem ipsum is simply free many variations of ipsum the majority
                    suffered.</p>
                </div>
                <div class="read_more_btn">
                  <nuxt-link to="/news_detail"><i class="fa fa-angle-right"></i>Read More</nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="blog_one_single wow fadeInUp" data-wow-delay="900ms">
            <div class="blog_one_image">
              <div class="blog_image">
                <img src="/assets/images/blog/blog-1-img-3.jpg" alt="Blog One Image">
                <div class="blog_one_date_box">
                  <p>30 Oct, 2019</p>
                </div>
              </div>
              <div class="blog-one__content">
                <ul class="list-unstyled blog-one__meta">
                  <li><nuxt-link to="/news_detail"><i class="far fa-user-circle"></i> Admin</nuxt-link></li>
                  <li><nuxt-link to="/news_detail"><i class="far fa-comments"></i> 2 Comments</nuxt-link>
                  </li>
                </ul>
                <h3><nuxt-link to="/news_detail">Winter Wheat Harvest<br>Gathering Momentum</nuxt-link></h3>
                <div class="blog_one_text">
                  <p>There are lorem ipsum is simply free many variations of ipsum the majority
                    suffered.</p>
                </div>
                <div class="read_more_btn">
                  <nuxt-link to="/news_detail"><i class="fa fa-angle-right"></i>Read More</nuxt-link>
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
        name: "BlogOne"
    }
</script>

<style scoped>

</style>
