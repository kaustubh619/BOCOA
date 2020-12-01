<template>
  <div class="header">
    <img src="~static/images/main_logo.png" class="img-logo" />
    <div>
      <span
        style="
          display: block;
          text-align: center;
          font-size: 17px;
          font-weight: bold;
        "
        ><span style="color: red">S</span>mar<span style="color: red"
          >t</span
        ></span
      >
      <span
        style="
          display: block;
          text-align: center;
          font-size: 17px;
          font-weight: bold;
        "
        ><span style="color: red">B</span>engalur<span style="color: red"
          >u</span
        >
      </span>
    </div>
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