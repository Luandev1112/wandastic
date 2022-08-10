<template>
  <div>
    <Nav />
    <PageHeader title="Checkout" />
    <Checkout />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Checkout from "../components/Checkout";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      Checkout,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Checkout"
      }
    }
  }
</script>
