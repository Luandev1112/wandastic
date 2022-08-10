<template>
  <div>
    <NavFive />
    <SliderFive />
    <BrandOne />
    <ServiceTwo />
    <TrustedOne />
    <TestimonialFour />
    <TeamOne />
    <TwoBoxes />
    <HealthyFood />
    <BlogOne />
    <ContactOne />
    <Footer />
  </div>
</template>

<script>
  import NavFive from "../components/NavFive";
  import SliderFive from "../components/SliderFive";
  import BrandOne from "../components/BrandOne";
  import ServiceTwo from "../components/ServiceTwo";
  import TrustedOne from "../components/TrustedOne";
  import TestimonialFour from "../components/TestimonialFour";
  import TeamOne from "../components/TeamOne";
  import TwoBoxes from "../components/TwoBoxes";
  import HealthyFood from "../components/HealthyFood";
  import BlogOne from "../components/BlogOne";
  import ContactOne from "../components/ContactOne";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      ContactOne,
      BlogOne,
      HealthyFood,
      TwoBoxes,
      TeamOne,
      TestimonialFour,
      TrustedOne,
      ServiceTwo,
      BrandOne,
      SliderFive,
      NavFive
    },
    head(){
      return {
        title: "Agrikol  | Home 5"
      }
    }
  }
</script>
