<template>
  <div>
    <Navbar />
    <div class="jumbotron" />
    <nuxt/>
  </div>
</template>

<script>
import Navbar from '@/components/navbar/Navbar'
export default {
  components: {
    Navbar
  }
}
</script>
