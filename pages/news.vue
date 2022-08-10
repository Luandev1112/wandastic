<template>
  <div>
    <Nav />
    <PageHeader title="News" />
    <BlogPage />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import BlogPage from "../components/BlogPage";
  export default {
    components: {
      BlogPage,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | News"
      }
    }
  }
</script>
