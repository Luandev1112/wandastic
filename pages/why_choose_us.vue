<template>
  <div>
    <Nav />
    <PageHeader title="Why Choose us" />
    <BestCompany />
    <TestimonialThree />
    <BenefitsTwo />
    <WhyChooseOne />
    <CompanySolutions />
    <BrandFour />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import BestCompany from "../components/BestCompany";
  import TestimonialThree from "../components/TestimonialThree";
  import BenefitsTwo from "../components/BenefitsTwo";
  import WhyChooseOne from "../components/WhyChooseOne";
  import CompanySolutions from "../components/CompanySolutions";
  import BrandFour from "../components/BrandFour";
  export default {
    components: {
      BrandFour,
      CompanySolutions,
      WhyChooseOne,
      BenefitsTwo,
      TestimonialThree,
      BestCompany,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Why Choose us"
      }
    }
  }
</script>
