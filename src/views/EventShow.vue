<template>
  <h1>Showing event #{{ id }}</h1>
</template>

<script>
export default {
  props: {
    id: {
      type: Number,
      default: null
    }
  }
}
</script>

<style></style>
