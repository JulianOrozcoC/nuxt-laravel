<template>
  <div>
    <h1>Hello World</h1>
    <no-ssr>
      <v-select
        v-model="selected"
        :options="['foo', 'bar']"
        placeholder="Select Category"
      />
    </no-ssr>
  </div>
</template>

<script>
export default {
  data() {
    return {
      selected: ''
    }
  }
}
</script>
