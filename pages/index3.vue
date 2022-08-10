<template>
  <div>
    <NavThree />
    <SliderThree />
    <WelcomeOne />
    <ServiceThree />
    <RecentProjectThree />
    <WorkOne />
    <QuoteOne />
    <WhyChooseOne />
    <TeamOne />
    <BrandThree />
    <WhatMakes />
    <BlogTwo />
    <CallToActionThree />
    <Footer />
  </div>
</template>

<script>

  import NavThree from "../components/NavThree";
  import SliderThree from "../components/SliderThree";
  import WelcomeOne from "../components/WelcomeOne";
  import ServiceThree from "../components/ServiceThree";
  import RecentProjectThree from "../components/RecentProjectThree";
  import WorkOne from "../components/WorkOne";
  import QuoteOne from "../components/QuoteOne";
  import WhyChooseOne from "../components/WhyChooseOne";
  import TeamOne from "../components/TeamOne";
  import BrandThree from "../components/BrandThree";
  import WhatMakes from "../components/WhatMakes";
  import BlogTwo from "../components/BlogTwo";
  import CallToActionThree from "../components/CallToActionThree";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      CallToActionThree,
      BlogTwo,
      WhatMakes,
      BrandThree,
      TeamOne,
      WhyChooseOne,
      QuoteOne,
      WorkOne,
      RecentProjectThree,
      ServiceThree,
      WelcomeOne,
      SliderThree,
      NavThree
    },
    head(){
      return {
        title: "Agrikol  | Home 3"
      }
    }
  }
</script>
