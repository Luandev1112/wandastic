<template>
  <div>
    <Nav />
    <PageHeader title="Services" />
    <ServicePage />
    <ServiceOne />
    <BrandOne />
    <FaqOne />
    <CallToActionThree />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import ServicePage from "../components/ServicePage";
  import ServiceOne from "../components/ServiceOne";
  import BrandOne from "../components/BrandOne";
  import FaqOne from "../components/FaqOne";
  import CallToActionThree from "../components/CallToActionThree";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      CallToActionThree,
      FaqOne,
      BrandOne,
      ServiceOne,
      ServicePage,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Services"
      }
    }
  }
</script>
