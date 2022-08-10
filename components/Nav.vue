<template>
  <div class="site-header__header-one-wrap">

    <div class="topbar-one">
      <div class="topbar_bg" style="background-image: url(/assets/images/shapes/header-bg.png)"></div>
      <div class="container">
        <div class="topbar-one__left">
          <a href="mailto:needhelp@tripo.com"><span class="icon-message"></span>needhelp@agrikol.com</a>
          <a href="tel:666-999-0000"><span class="icon-phone-call"></span>666 888 0000</a>
        </div>
        <div class="topbar-one__middle">
          <a href="/" class="main-nav__logo">
            <img src="/assets/images/resources/logo.png" class="main-logo" alt="Awesome Image" />
          </a>
        </div>
        <div class="topbar-one__right">
          <div class="topbar-one__social">
            <a href="#"><i class="fab fa-facebook-square"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-dribbble"></i></a>
          </div>
        </div>
      </div>
    </div>

    <header class="main-nav__header-one">
      <nav :class="`header-navigation stricky clearfix ${sticky ? 'stricked-menu stricky-fixed' : ''}`">
        <div class="container clearfix">
          <!-- Brand and toggle get grouped for better mobile display -->
          <div class="main-nav__left">
            <a href="#" class="main-nav__search search-popup__toggler"><i
              class="icon-magnifying-glass"></i></a>
            <a href="#" class="side-menu__toggler">
              <i @click="mobileToggle = !mobileToggle" class="fa fa-bars"></i>
            </a>
          </div>
          <div class="main-nav__main-navigation">
            <ul class=" main-nav__navigation-box">
              <li class="dropdown current">
                <nuxt-link to="/">Home</nuxt-link>
                <ul>
                  <li><nuxt-link to="/">Home 01</nuxt-link></li>
                  <li><nuxt-link to="/index2">Home 02</nuxt-link></li>
                  <li><nuxt-link to="/index3">Home 03</nuxt-link></li>
                  <li><nuxt-link to="/index4">Home 04</nuxt-link></li>
                  <li><nuxt-link to="/index5">Home 05</nuxt-link></li>
                  <li class="dropdown"><a href="#">Header Versions</a>
                    <ul>
                      <li><nuxt-link to="/index">Header 01</nuxt-link></li>
                      <li><nuxt-link to="/index2">Header 02</nuxt-link></li>
                      <li><nuxt-link to="/index3">Header 03</nuxt-link></li>
                      <li><nuxt-link to="/index4">Header 04</nuxt-link></li>
                      <li><nuxt-link to="/index5">Header 05</nuxt-link></li>
                    </ul><!-- /.sub-menu -->
                  </li>
                </ul><!-- /.sub-menu -->
              </li>
              <li class="dropdown">
                <nuxt-link to="/service">Services</nuxt-link>
                <ul>
                  <li><nuxt-link to="/service">Services</nuxt-link></li>
                  <li><nuxt-link to="/service-detail">Services Detail</nuxt-link></li>
                </ul><!-- /.sub-menu -->
              </li>
              <li class="dropdown">
                <nuxt-link to="/projects">Our Projects</nuxt-link>
                <ul>
                  <li><nuxt-link to="/projects">Projects</nuxt-link></li>
                  <li><nuxt-link to="/projects_detail">Projects Detail</nuxt-link></li>
                </ul><!-- /.sub-menu -->
              </li>
              <li class="dropdown">
                <nuxt-link to="#">Shop</nuxt-link>
                <ul>
                  <li><nuxt-link to="/product">Products</nuxt-link></li>
                  <li><nuxt-link to="/product-detail">Product Detail</nuxt-link></li>
                  <li><nuxt-link to="/cart">Cart</nuxt-link></li>
                  <li><nuxt-link to="/checkout">Checkout</nuxt-link></li>
                </ul><!-- /.sub-menu -->
              </li>
              <li class="dropdown">
                <nuxt-link to="#">Pages</nuxt-link>
                <ul>
                  <li><nuxt-link to="/about">About</nuxt-link></li>
                  <li><nuxt-link to="/why_choose_us">Why Choose Us</nuxt-link></li>
                  <li><nuxt-link to="/farmers">Farmers</nuxt-link></li>
                  <li><nuxt-link to="/gallery">Gallery</nuxt-link></li>
                </ul><!-- /.sub-menu -->
              </li>
              <li class="dropdown">
                <nuxt-link to="#">News</nuxt-link>
                <ul>
                  <li><nuxt-link to="/news">News</nuxt-link></li>
                  <li><nuxt-link to="/news_detail">News Details</nuxt-link></li>
                </ul><!-- /.sub-menu -->
              </li>
              <li>
                <nuxt-link to="/contact">Contact</nuxt-link>
              </li>
            </ul>
          </div><!-- /.navbar-collapse -->

          <div class="main-nav__right">
            <div class="icon_cart_box">
              <nuxt-link to="/cart">
                <span class="icon-shopping-cart"></span>
              </nuxt-link>
            </div>
          </div>
        </div>
      </nav>


        <nav class="mobile-nav__container" :style="`display: ${mobileToggle ? 'block' : 'none'}`">
          <!-- content is loading via js -->

          <ul class="main-nav__navigation-box">
            <li class="dropdown current">
              <div class="menu-holder">Home<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
              <ul>
                <li><nuxt-link to="/">Home 01</nuxt-link></li>
                <li><nuxt-link to="/index2">Home 02</nuxt-link></li>
                <li><nuxt-link to="/index3">Home 03</nuxt-link></li>
                <li><nuxt-link to="/index4">Home 04</nuxt-link></li>
                <li><nuxt-link to="/index5">Home 05</nuxt-link></li>
                <li class="dropdown">
                  <div class="menu-holder">Header Versions<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
                  <ul>
                    <li><nuxt-link to="/">Header 01</nuxt-link></li>
                    <li><nuxt-link to="/index2">Header 02</nuxt-link></li>
                    <li><nuxt-link to="/index3">Header 03</nuxt-link></li>
                    <li><nuxt-link to="/index4">Header 04</nuxt-link></li>
                    <li><nuxt-link to="/index5">Header 05</nuxt-link></li>
                  </ul><!-- /.sub-menu -->
                </li>
              </ul><!-- /.sub-menu -->
            </li>
            <li class="dropdown">
              <div class="menu-holder">Services<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
              <ul>
                <li><nuxt-link to="/service">Services</nuxt-link></li>
                <li><nuxt-link to="/service-detail">Services Detail</nuxt-link></li>
              </ul><!-- /.sub-menu -->
            </li>
            <li class="dropdown">
              <div class="menu-holder">Our Projects<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
              <ul>
                <li><nuxt-link to="/projects">Projects</nuxt-link></li>
                <li><nuxt-link to="/projects_detail">Projects Detail</nuxt-link></li>
              </ul><!-- /.sub-menu -->
            </li>
            <li class="dropdown">
              <div class="menu-holder">Shop<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
              <ul>
                <li><nuxt-link to="/product">Products</nuxt-link></li>
                <li><nuxt-link to="/product-detail">Product Detail</nuxt-link></li>
                <li><nuxt-link to="/cart">Cart</nuxt-link></li>
                <li><nuxt-link to="/checkout">Checkout</nuxt-link></li>
              </ul><!-- /.sub-menu -->
            </li>
            <li class="dropdown">
              <div class="menu-holder">Pages<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
              <ul>
                <li><nuxt-link to="/about">About</nuxt-link></li>
                <li><nuxt-link to="/why_choose_us">Why Choose Us</nuxt-link></li>
                <li><nuxt-link to="/farmers">Farmers</nuxt-link></li>
                <li><nuxt-link to="/gallery">Gallery</nuxt-link></li>
              </ul><!-- /.sub-menu -->
            </li>
            <li class="dropdown">
              <div class="menu-holder">News<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
              <ul>
                <li><nuxt-link to="/news">News</nuxt-link></li>
                <li><nuxt-link to="/news_detail">News Details</nuxt-link></li>
              </ul><!-- /.sub-menu -->
            </li>
            <li>
              <nuxt-link to="/contact">Contact</nuxt-link>
            </li>
          </ul>
        </nav>

    </header>
  </div>
</template>

<script>
    export default {
      name: "Nav",
      data(){
        return {
          sticky: false,
          mobileToggle: false
        }
      },
      mounted() {
        window.addEventListener('scroll', this.handleScroll);
      },
      methods: {

        handleScroll() {
          if (window.scrollY > 70) {
            this.sticky = true
          } else if (window.scrollY < 70) {
            this.sticky = false
          }
        },
      }
    }
</script>

<style scoped>

</style>
