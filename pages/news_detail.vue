<template>
  <div>
    <Nav />
    <PageHeader title="News Detail" />
    <BlogSingle />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import BlogSingle from "../components/BlogSingle";
  export default {
    components: {
      BlogSingle,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | News Detail"
      }
    }
  }
</script>
