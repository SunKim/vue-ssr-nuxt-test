<template>
  <div class="container">
    <div>
      <h1 class="title">
        Home Sample
      </h1>
      <h2 class="subtitle">
        By Sun
      </h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Lome',
  layout: 'navbar',
  asyncData ({ req }) {
    return {
      name: req ? 'server' : 'client'
    }
  }
}
</script>

<style scoped>
</style>
