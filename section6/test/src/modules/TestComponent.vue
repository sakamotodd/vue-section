<template>
  <div class="red-b">
    <div class="border__blue">SCSSのてすと</div>
    <div class="background__primary">SCSSのてすと</div>
    {{ testData }}</div>
</template>

<script>
export default {
  name: 'TestComponent',
  data() {
    return {
      testData: '初期値データです。',
    }
  },
}
</script>

<style scoped lang="scss">
  .red-b {
    border: 1px solid red;
  }

  .border {
    &__blue {
      border: 1px solid blue;
    }
  }

  .background__primary {
  background-color: $color-primary;
}
</style>
