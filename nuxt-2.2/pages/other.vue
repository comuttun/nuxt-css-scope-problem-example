<template>
  <div>
    <p>Other world!</p>
    <p class="special">Special world!</p>
  </div>
</template>

<script>
export default {
  layout: 'other'
}
</script>

<style scoped>
@import url('~/assets/css/other.css');

p.special {
  font-weight: bold;
}
</style>
