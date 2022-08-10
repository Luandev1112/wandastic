<template>
  <div>
    <Nav />
    <PageHeader title="Our Projects" />
    <ProjectPage />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import ProjectPage from "../components/ProjectPage";
  export default {
    components: {
      ProjectPage,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Agrikol  | Our Projects"
      }
    }
  }
</script>
