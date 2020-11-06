<template>
  <div class="index-body">
    <div class="index-img"></div>
    <div class="container">
      <div class="row index-services">
        <div class="col-6 col-lg-3">
          <a
            href="http://jagruthi.livserv.com/wordpress/"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/grievance.webp" class="img-services" />
          </a>
        </div>
        <div class="col-6 col-lg-3">
          <a
            href="https://bescom.co.in/SCP/Myhome.aspx"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/bescom.webp" class="img-services" />
          </a>
        </div>
        <div class="col-6 col-lg-3">
          <a
            href="https://www.karnatakaone.gov.in/Info/Public/BangaloreOne"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/bangalore-one.webp" class="img-services" />
          </a>
        </div>
        <div class="col-6 col-lg-3">
          <a href="https://www.bwssb.gov.in/" target="blank" class="img-anchor">
            <img src="~static/images/bwssb_1.webp" class="img-services" />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {};
</script>

<style scoped>
.index-services {
  justify-content: center;
  align-items: center;
  padding: 20px;
}

@media screen and (max-width: 37.5em) {
  .index-services {
    height: 52vh;
  }
}

@media (min-width: 37.5em) and (max-width: 1024px) {
  .index-services {
    height: 56vh;
  }
}

.index-img {
  background-image: url("~static/images/vidhan_soudha_large.webp");
  height: 600px;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.img-anchor {
  display: flex;
  justify-content: center;
  align-items: center;
}

.img-services {
  border: 4px solid #ede574;
  border-radius: 50%;
  width: 200px;
  background: white;
  margin: 10px;
}

@media screen and (max-width: 37.5em) {
  .index-img {
    background-image: url("~static/images/vidhan_soudha_small.webp");
    height: 300px;
  }
  .img-services {
    border-radius: 50%;
    width: 140px;
    background: white;
  }
}

@media (min-width: 37.5em) and (max-width: 1024px) {
  .index-img {
    background-image: url("~static/images/vidhan_soudha_medium.webp");
    height: 400px;
  }
}
</style>
