<template>
  <div>
    <div class="debug container">
      <div class="child">child</div>
      <div class="child">child</div>
      <div class="child">child</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.debug {
  border: 1px solid black;
}
.debug > div {
  border: 1px solid red;
}

.container {
  display: flex;
}

.child {
  display: flex;
  flex: 1 1 0;
}
</style>
