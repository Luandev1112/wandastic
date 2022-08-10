<template>
  <section class="recent_project_three">
    <div class="container-fullwidth">
      <div class="block-title text-center">
        <p>explore projects</p>
        <h3>our Recent projects</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="recent_project_three_carousel owl-theme owl-carousel">
        <no-ssr> <!-- important to add no-ssr-->
          <carousel :autoplay="true" :margin="5" :responsive="{0: {items: 1},640: {items: 2},992: {items: 3},1024: {items: 4}}">

          <!--Item-->
        <div class="project_three_single wow fadeInUp" data-wow-delay="300ms">
          <div class="project_three_image">
            <img src="/assets/images/project/project-3-img-1.jpg" alt="">
            <div class="project_three_content">
              <h2>organic<br>solutions</h2>
            </div>
            <div class="project_three_hover_box">
              <h2>Harvest<br>Innovations</h2>
              <p>There are many new variations of available<br>but majority is simple free text.</p>
              <div class="project_three_btn">
                <a href="/projects_detail" class="thm-btn project_three_btn_hover">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!--Item-->
        <div class="project_three_single wow fadeInUp" data-wow-delay="600ms">
          <div class="project_three_image">
            <img src="/assets/images/project/project-3-img-2.jpg" alt="">
            <div class="project_three_content">
              <h2>organic<br>solutions</h2>
            </div>
            <div class="project_three_hover_box">
              <h2>Harvest<br>Innovations</h2>
              <p>There are many new variations of available<br>but majority is simple free text.</p>
              <div class="project_three_btn">
                <a href="/projects_detail" class="thm-btn project_three_btn_hover">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!--Item-->
        <div class="project_three_single wow fadeInUp" data-wow-delay="900ms">
          <div class="project_three_image">
            <img src="/assets/images/project/project-3-img-3.jpg" alt="">
            <div class="project_three_content">
              <h2>organic<br>solutions</h2>
            </div>
            <div class="project_three_hover_box">
              <h2>Harvest<br>Innovations</h2>
              <p>There are many new variations of available<br>but majority is simple free text.</p>
              <div class="project_three_btn">
                <a href="/projects_detail" class="thm-btn project_three_btn_hover">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!--Item-->
        <div class="project_three_single wow fadeInUp" data-wow-delay="1200ms">
          <div class="project_three_image">
            <img src="/assets/images/project/project-3-img-4.jpg" alt="">
            <div class="project_three_content">
              <h2>organic<br>solutions</h2>
            </div>
            <div class="project_three_hover_box">
              <h2>Harvest<br>Innovations</h2>
              <p>There are many new variations of available<br>but majority is simple free text.</p>
              <div class="project_three_btn">
                <a href="/projects_detail" class="thm-btn project_three_btn_hover">Read More</a>
              </div>
            </div>
          </div>
        </div>
          </carousel>
        </no-ssr>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "RecentProjectThree"
    }
</script>

<style scoped>

</style>
