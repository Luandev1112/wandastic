<template>
  <div>
    <Nav />
    <PageHeader title="Service Detail" />
    <ServiceDetail />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import ServiceDetail from "../components/ServiceDetail";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      ServiceDetail,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Service Detail"
      }
    }
  }
</script>
