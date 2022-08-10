<template>
  <div>
    <NavFour />
    <SliderFour />
    <DetailsOne />
    <WelcomeTwo />
    <EcoFriendly />
    <ServiceFour />
    <FaqOne />
    <TestimonialThree />
    <BrandFour />
    <AchievedOne />
    <FunfactOne />
    <BlogFour />
    <Footer />
  </div>
</template>

<script>

  import SliderFour from "../components/SliderFour";
  import NavFour from "../components/NavFour";
  import DetailsOne from "../components/DetailsOne";
  import WelcomeTwo from "../components/WelcomeTwo";
  import EcoFriendly from "../components/EcoFriendly";
  import ServiceFour from "../components/ServiceFour";
  import FaqOne from "../components/FaqOne";
  import TestimonialThree from "../components/TestimonialThree";
  import BrandFour from "../components/BrandFour";
  import AchievedOne from "../components/AchievedOne";
  import FunfactOne from "../components/FunfactOne";
  import BlogFour from "../components/BlogFour";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      BlogFour,
      FunfactOne,
      AchievedOne,
      BrandFour,
      TestimonialThree,
      FaqOne,
      ServiceFour,
      EcoFriendly,
      WelcomeTwo,
      DetailsOne,
      NavFour,
      SliderFour
    },
    head(){
      return {
        title: "Agrikol  | Home 4"
      }
    }
  }
</script>
