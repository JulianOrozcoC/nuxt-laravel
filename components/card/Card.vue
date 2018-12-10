<template>
  <div
    class="card text-white bg-dark mb-3"
    style="max-width: 18rem;"
  >
    <div class="card-header">Post: {{ post.id }}</div>
    <div class="card-body">
      <nuxt-link :to="{ name: 'posts-id', params: { id: post.id }}">
        {{ post.title }}
      </nuxt-link>
      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    post: {
      type: Object,
      required: true
    }
  }
}
</script>
