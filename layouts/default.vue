<template>
  <div>
    <Navbar />
    <div class="jumbotron" />
    <nuxt/>
  </div>
</template>

<script>
import Navbar from '@/components/navbar/navbar'
export default {
  components: {
    Navbar
  }
}
</script>
