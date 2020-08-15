<template>
  <div class="home">
    {{name}}: meow
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'alice',
    }
  }
}
</script>

<style>
  .home {
    color: wheat;
  }
</style>