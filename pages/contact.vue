<template>
  <div>
    <Nav />
    <PageHeader title="Contact" />
    <Location />
    <ContactTwo />
    <GMap />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import Location from "../components/Location";
  import ContactTwo from "../components/ContactTwo";
  import GMap from "../components/GMap";
  export default {
    components: {
      GMap,
      ContactTwo,
      Location,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Contact"
      }
    }
  }
</script>
