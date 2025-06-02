<template>
  <section>
    <BlogItem v-for="post in posts" :key="post.id" :post="post" />
  </section>
</template>

<script>
import BlogItem from './BlogItem.vue'

export default {
  name: "BlogList",
  components: { BlogItem },
  data() {
    return {
      posts: [
        { id: 1, title: 'Vue 3 Composition API', summary: 'Giới thiệu Composition API trong Vue 3.' },
        { id: 2, title: 'Sử dụng Vue Router', summary: 'Tạo ứng dụng SPA với Vue Router.' },
        { id: 3, title: 'Pinia vs Vuex', summary: 'So sánh hai thư viện quản lý trạng thái.' }
      ]
    }
  }
}
</script>
