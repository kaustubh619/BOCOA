<template>
  <div class="header">
    <img src="~static/images/main_logo.png" class="img-logo" />
  </div>
</template>

<script>
  export default {};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  width: 100%;
  height: auto;
  padding: 4px 20px;
  background-image: linear-gradient(to bottom right, #e1f5c4, #ede574);
}

.img-logo {
  width: 130px;
  z-index: 1;
}

@media screen and (max-width: 768px) {
  .img-logo {
    width: 100px;
  }
}
</style>