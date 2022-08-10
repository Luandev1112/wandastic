<template>
  <div>
    <Nav />
    <PageHeader title="About" />
    <AboutTwo />
    <TestimonialFour />
    <BrandOne />
    <VideoOne />
    <ProductOne />
    <TeamOne />
    <CallToActionOne />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import AboutTwo from "../components/AboutTwo";
  import TestimonialFour from "../components/TestimonialFour";
  import BrandOne from "../components/BrandOne";
  import VideoOne from "../components/VideoOne";
  import ProductOne from "../components/ProductOne";
  import TeamOne from "../components/TeamOne";
  import CallToActionOne from "../components/CallToActionOne";
  export default {
    components: {
      CallToActionOne,
      TeamOne,
      ProductOne,
      VideoOne,
      BrandOne,
      TestimonialFour,
      AboutTwo,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | About"
      }
    }
  }
</script>
