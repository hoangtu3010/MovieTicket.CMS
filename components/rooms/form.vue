<template>
  <div>
    <div v-if="id">Form edit of rooms</div>
    <div v-else>Form add of rooms</div>
  </div>
</template>

<script>
export default {
  props: {
    id: {
      type: Number,
      default: 0,
    }
  },
  data() {
    return {};
  },
};
</script>

<style>
</style>