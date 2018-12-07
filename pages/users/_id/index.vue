<template>
  <div>
    <h2>This is users id is {{ $route.params.id }} </h2>
  </div>
</template>

<script>
export default {
  validate({ params }) {
    return /^\d+$/.test(params.id)
  }
}
</script>
