<template>
  <div class="container">
    <slot></slot>
  </div>
</template>

<script lang="ts">
export default {};
</script>

<style scoped lang="scss">
.container {
  margin: 0 auto;
  max-width: 1070px;
  @include screen("small") {
    width: 90%;
  }
  @include screen("medium") {
    width: 85%;
  }
  @include screen("large", "infinity") {
    width: 70%;
  }
}
</style>
