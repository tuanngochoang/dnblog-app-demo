<template>
  <div class="blog-page">
    <Header />
    <BlogList />
    <Footer />
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
import BlogList from '../components/BlogList.vue'

export default {
  name: "BlogPage",
  components: {
    Header,
    Footer,
    BlogList
  }
}
</script>
