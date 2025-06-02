<template>
  <div class="blog-item">
    <h2>{{ post.title }}</h2>
    <p>{{ post.summary }}</p>
  </div>
</template>

<script>
export default {
  name: "BlogItem",
  props: {
    post: Object
  }
}
</script>

<style scoped>
.blog-item {
  border-bottom: 1px solid #ccc;
  margin-bottom: 20px;
  padding-bottom: 10px;
}
</style>
