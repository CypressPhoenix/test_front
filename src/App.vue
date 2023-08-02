<template>
  <div>
    <h1>{{ greeting }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      greeting: 'Hello World Test',
    };
  },
};
</script>

<style scoped>
h1 {
  color: blue;
  text-align: center;
}
</style>
