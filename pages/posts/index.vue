<template>
  <div>
    <div>
      <h2>Making API request - the vue way</h2>
    </div>
    <hr>
    <div class="container row">
      <Card
        v-for="post in posts"
        :key="post.id"
        :post="post"
        class="ml-auto mr-auto"
      />
      <button
        v-scroll-to="'body'"
        class="btn btn-danger"
      >
        Back to Top
      </button>
    </div>
  </div>
</template>

<script>
import axios from 'axios'
import Card from '@/components/card/Card'
import { mapGetters } from 'vuex'

export default {
  components: {
    Card
  },
  computed: {
    ...mapGetters(['posts'])
  },
  /*   async asyncData({ store }) {
    let { data } = await axios.get('https://jsonplaceholder.typicode.com/posts')
    store.dispatch('setPosts', data)
  }, */
  head: {
    title: 'List of Posts'
  }
}
</script>
