<template>
  <section class="news_detail">
    <div class="container">
      <div class="row">
        <div class="col-xl-8 col-lg-7">
          <div class="news_detail_left">
            <div class="news_detail_image_box">
              <img src="/assets/images/blog/news-detail-img-1.jpg" alt="">
              <div class="news_detail_date_box">
                <p>30 Oct, 2019</p>
              </div>
            </div>
            <ul class="list-unstyled news_detail__meta">
              <li><nuxt-link to="/news_detail"><i class="far fa-user-circle"></i> Admin</nuxt-link></li>
              <li><nuxt-link to="/news_detail"><i class="far fa-comments"></i> 2 Comments</nuxt-link></li>
            </ul>
            <div class="news_detail_content">
              <h2>Amount of Freak Bread or Other Fruits</h2>
              <p class="news_detail_one_text">There are many variations of passages of Lorem Ipsum
                available, but the majority have suffered alteration in some injected or words which
                don't look even slightly believable. If you are going to use a passage of Lorem
                Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of
                text. All the Lorem Ipsum generators on the Internet tend to repeat predefined
                chunks as necessary, making this the first true generator on the Internet. It uses a
                dictionary of over 200 Latin words, combined with a handful of model sentence
                structures, to generate Lorem Ipsum which looks reasonable.</p>
              <p class="news_detail_two_text">Lorem Ipsum has been the industry's standard dummy text
                ever since the 1500s, when an unknown printer took a galley of type and scrambled it
                to make a type specimen book. It has survived not only five centuries, but also the
                leap into electronic typesetting.</p>
              <p class="news_detail_three_text">Lorem Ipsum is simply dummy text of the printing and
                typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever
                since the 1500s, when an unknown printer took a galley of type and scrambled it to
                make a type specimen book. It has survived not only five centuries.</p>
            </div>
            <div class="news_detail__bottom">
              <p class="news_detail__tags">
                <span>Tags:</span>
                <a href="#">Agriculture,</a>
                <a href="#">Food,</a>
                <a href="#">Economy</a>
              </p>
              <div class="news_detail__social-list">
                <a href="#"><i class="fab fa-facebook-square"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-dribbble"></i></a>
              </div>
            </div>
            <div class="author-one">
              <div class="author-one__image">
                <img src="/assets/images/blog/author-1-1.jpg" alt="">
              </div>
              <div class="author-one__content">
                <h3>Christine Eve</h3>
                <p>It has survived not only five centuries, but also the leap into electronic
                  typesetting,
                  remaining unchanged. It was popularised in the sheets containing.</p>
              </div>
            </div>
            <div class="comment-one">
              <h3 class="comment-one__title">2 Comments</h3>
              <div class="comment-one__single">
                <div class="comment-one__image">
                  <img src="/assets/images/blog/comment-1-1.png" alt="">
                </div>
                <div class="comment-one__content">
                  <h3>Sarah albert</h3>
                  <p>It has survived not only five centuries, but also the leap into electronic
                    typesetting unchanged. It was popularised in the sheets containing lorem
                    ipsum is simply free text available in the martket to use now.</p>
                  <a href="#" class="thm-btn comment-one__btn">Reply</a>
                </div>
              </div>
              <div class="comment-one__single">
                <div class="comment-one__image">
                  <img src="/assets/images/blog/comment-1-2.png" alt="">
                </div>
                <div class="comment-one__content">
                  <h3>Kevin Martin</h3>
                  <p>It has survived not only five centuries, but also the leap into electronic
                    typesetting
                    unchanged. It was popularised in the sheets containing lorem ipsum is simply
                    free text
                    available in the martket to use now.</p>
                  <a href="#" class="thm-btn comment-one__btn">Reply</a>
                </div>
              </div>
            </div>
            <div class="comment-form">
              <h3 class="comment-form__title">Leave a Comment</h3>
              <form action="#" class="comment-one__form">
                <div class="row">
                  <div class="col-xl-6">
                    <div class="comment_input_box">
                      <input type="text" placeholder="Full name" name="name">
                    </div>
                  </div>
                  <div class="col-xl-6">
                    <div class="comment_input_box">
                      <input type="text" placeholder="Email address" name="email">
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-xl-12">
                    <div class="comment_input_box">
                      <textarea name="message" placeholder="Write message"></textarea>
                    </div>
                    <button type="submit" class="thm-btn comment-form__btn">Submit
                      Comment</button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-5">
          <div class="sidebar">
            <div class="sidebar__single sidebar__search">
              <form action="#" class="sidebar__search-form">
                <input type="search" placeholder="Search">
                <button type="submit"><i class="icon-magnifying-glass"></i></button>
              </form>
            </div>
            <div class="sidebar__single sidebar__post">
              <h3 class="sidebar__title">Latest Posts</h3>
              <ul class="sidebar__post-list list-unstyled">
                <li>
                  <div class="sidebar__post-image">
                    <img src="/assets/images/blog/lp-1-1.jpg" alt="">
                  </div>
                  <div class="sidebar__post-content">
                    <h3>
                      <a href="#" class="sidebar__post-content_meta"><i class="far fa-user-circle"></i> Admin</a>
                      <nuxt-link to="/news_detail">Agriculture Miracle you Don't Know About</nuxt-link>
                    </h3>
                  </div>
                </li>
                <li>
                  <div class="sidebar__post-image">
                    <img src="/assets/images/blog/lp-1-2.jpg" alt="">
                  </div>
                  <div class="sidebar__post-content">
                    <h3>
                      <a href="#" class="sidebar__post-content_meta"><i class="far fa-user-circle"></i> Admin</a>
                      <nuxt-link to="/news_detail">Agriculture Miracle you Don't Know About</nuxt-link>
                    </h3>
                  </div>
                </li>
                <li>
                  <div class="sidebar__post-image">
                    <img src="assets/images/blog/lp-1-3.jpg" alt="">
                  </div>
                  <div class="sidebar__post-content">
                    <h3>
                      <a href="#" class="sidebar__post-content_meta"><i class="far fa-user-circle"></i> Admin</a>
                      <nuxt-link to="/news_detail">Agriculture Miracle you Don't Know About</nuxt-link>
                    </h3>
                  </div>
                </li>
              </ul>
            </div>
            <div class="sidebar__single sidebar__category">
              <h3 class="sidebar__title">All Categories</h3>
              <ul class="sidebar__category-list list-unstyled">
                <li><a href="#">Agriculture</a></li>
                <li><a href="#">Organic Food</a></li>
                <li><a href="#">Dairy Farm</a></li>
                <li><a href="#">Economy Solution</a></li>
                <li><a href="#">Harvests Innovations</a></li>
              </ul>
            </div>
            <div class="sidebar__single sidebar__tags">
              <h3 class="sidebar__title">Popular Tags</h3>
              <div class="sidebar__tags-list">
                <a href="#">Agriculture,</a>
                <a href="#">Food,</a>
                <a href="#">Healthy,</a>
                <a href="#">Economy,</a>
                <a href="#">Organic,</a>
                <a href="#">Farm,</a>
                <a href="#">Dairy,</a>
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
        name: "BlogSingle"
    }
</script>

<style scoped>

</style>
