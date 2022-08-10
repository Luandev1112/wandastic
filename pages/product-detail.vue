<template>
  <div>
    <Nav />
    <PageHeader title="Product Detail" />
    <ProductDetail />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import ProductDetail from "../components/ProductDetail";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      PageHeader,
      ProductDetail,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Product Detail"
      }
    }
  }
</script>
