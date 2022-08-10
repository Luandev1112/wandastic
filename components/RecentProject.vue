<template>
  <section class="recent-project">
    <div class="container">
      <div class="block-title text-center">
        <p>explore projects</p>
        <h3>our Recent projects</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single wow fadeInUp" data-wow-delay="300ms">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-1.jpg" alt="Recent Project Img">
              <div class="project_content">
                <h3>organic<br>solutions</h3>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single wow fadeInUp" data-wow-delay="600ms">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-2.jpg" alt="Recent Project Img">
              <div class="project_content">
                <h3>Harvest<br>Innovations</h3>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4 wow fadeInUp" data-wow-delay="900ms">
          <div class="recent_project_single">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-3.jpg" alt="Recent Project Img">
              <div class="project_content">
                <h3>Agriculture<br>farming</h3>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
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
        name: "RecentProject"
    }
</script>

<style scoped>

</style>
