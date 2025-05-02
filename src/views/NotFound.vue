<template>
  <div class="page">
    <p>
      Oops, không thể tìm thấy trang. Trở về
      <router-link to="/">trang chủ</router-link>.
    </p>
  </div>
</template>

<script>
export default {
  name: 'NotFound'
}
</script>

<style scoped>
.page {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 300px;
  font-size: 1.2em;
}
</style>