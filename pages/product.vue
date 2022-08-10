<template>
  <div>
    <Nav />
    <PageHeader title="Products" />
    <Products />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import Products from "../components/Products";
  export default {
    components: {
      Products,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Products"
      }
    }
  }
</script>
