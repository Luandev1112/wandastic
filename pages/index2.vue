<template>
  <div>
    <NavTwo />
    <SliderTwo />
    <NeedAll />
    <ServiceTwo />
    <CallToActionTwo />
    <ProductTwo />
    <RecentProject />
    <TestimonialTwo />
    <VideoOne />
    <BrandTwo />
    <GetQuote />
    <GMap />
    <GalleryOne />
    <FooterTwo />
  </div>
</template>

<script>

  import FooterTwo from "../components/FooterTwo";
  import NavTwo from "../components/NavTwo";
  import SliderTwo from "../components/SliderTwo";
  import NeedAll from "../components/NeedAll";
  import CallToActionTwo from "../components/CallToActionTwo";
  import ProductTwo from "../components/ProductTwo";
  import RecentProject from "../components/RecentProject";
  import TestimonialTwo from "../components/TestimonialTwo";
  import VideoOne from "../components/VideoOne";
  import BrandTwo from "../components/BrandTwo";
  import GetQuote from "../components/GetQuote";
  import GMap from "../components/GMap";
  import GalleryOne from "../components/GalleryOne";
  import ServiceTwo from "../components/ServiceTwo";
  export default {
    components: {
      ServiceTwo,
      GalleryOne,
      GMap,
      GetQuote,
      BrandTwo,
      VideoOne,
      TestimonialTwo,
      RecentProject,
      ProductTwo,
      CallToActionTwo,
      NeedAll,
      SliderTwo,
      NavTwo,
      FooterTwo,
    },
    head(){
      return {
        title: "Agrikol  | Home 2"
      }
    }
  }
</script>
