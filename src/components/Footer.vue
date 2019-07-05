<template>
  <footer class="footer fixed-bottom">
    <div class="container">
      <p class="text-muted">Place sticky footer content here.</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  props: {
    msg: String
  }
};
</script>

<style scoped>
.footer{
  background-color: #c3c3c3;
}
</style>