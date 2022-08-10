<template>
  <div>
    <Nav />
    <PageHeader title="Project Detail" />
    <ProjectDetail />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import ProjectDetail from "../components/ProjectDetail";
  export default {
    components: {
      ProjectDetail,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Project Detail"
      }
    }
  }
</script>
