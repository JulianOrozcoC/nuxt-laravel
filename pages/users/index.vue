<template>
  <div>
    <div>
      <h1>Hello users</h1>
    </div>
    <div>
      <input
        v-model="id"
        type="text"
      >
      <button @click="loadUser">Load user </button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      id: ''
    }
  },
  methods: {
    loadUser() {
      this.$router.push(`/users/${this.id}`)
    }
  }
}
</script>
