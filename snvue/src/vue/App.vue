<template>
  <div>
    <h2 class="title">{{ name }}</h2>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      name: 'sn',
      age: 18,
      height: 175
    }
  }
}
</script>

<style scoped>
.title {
  color: pink;
}
</style>