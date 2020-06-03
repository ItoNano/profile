<template>
  <div class="box">
    <div class="content">中身</div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {}
}
</script>

<style lang="scss">
.box {
  display: flex;
  justify-content: center;
  align-content: center;
  .content {
    border: 1px solid black;
  }
}
</style>