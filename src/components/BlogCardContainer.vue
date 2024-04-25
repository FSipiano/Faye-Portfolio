<template>
<section>

<ul>
    <li v-for="post in posts" :key="post.title">
      <BlogCard :post="post">
</BlogCard>
    </li>
  </ul>

</section>
</template>
<script>

export default {
  
data() {
  return {
    posts: []
}
 },
 async fetch() {
      this.posts = await fetch(
        'https://dev.to/api/articles?username=javascriptcoff1&per_page=5'
      ).then(res => res.json())
    }
  }

</script>

