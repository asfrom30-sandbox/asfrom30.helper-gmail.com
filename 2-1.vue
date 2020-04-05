<template>
  <div>
    <div class="debug container">
      <div class="child">
        <span class="content">child</span>
      </div>
      <div class="child">
        <span class="content">child</span>
      </div>
      <div class="child">
        <span class="content">child</span>
      </div>
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
  height: 200px;
  align-items: center;
}

.child {
  display: flex;
  flex: 1 1 0;
  height: 100%;
}

.content {
  border: 1px solid green;
  margin: auto;
  /* justify-self: center; */
  align-self: center;
}
</style>
