<template>
  <div class="index-body">
    <div class="index-img"></div>
    <div class="container">
      <div class="row index-services">
        <div class="col-4 col-lg-3">
          <a
            href="http://jagruthi.livserv.com/wordpress/"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/grievance.webp" class="img-services" />
          </a>
          <span class="title-services">Grievance Redressal</span>
        </div>
        <div class="col-4 col-lg-3">
          <a
            href="https://bescom.co.in/SCP/Myhome.aspx"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/bescom.webp" class="img-services" />
          </a>
          <span class="title-services">BESCOM</span>
        </div>
        <div class="col-4 col-lg-3">
          <a
            href="https://www.karnatakaone.gov.in/Info/Public/BangaloreOne"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/bangalore-one.webp" class="img-services" />
          </a>
          <span class="title-services">Bangalore One</span>
        </div>
        <div class="col-4 col-lg-3">
          <a href="https://www.bwssb.gov.in/" target="blank" class="img-anchor">
            <img src="~static/images/bwssb_1.webp" class="img-services" />
          </a>
          <span class="title-services">BWSSB</span>
        </div>
        <div class="col-4 col-lg-3">
          <a
            href="https://www.bmstindia.org/"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/blood_bank.jpg" class="img-services" />
          </a>
          <span class="title-services">Blood Bank</span>
        </div>
        <div class="col-4 col-lg-3">
          <a href="http://fm.ksfesonline.in/" target="blank" class="img-anchor">
            <img src="~static/images/fire.png" class="img-services" />
          </a>
          <span class="title-services">Fire & Emergency</span>
        </div>
        <div class="col-4 col-lg-3">
          <a href="https://www.bcp.gov.in/" target="blank" class="img-anchor">
            <img src="~static/images/police.png" class="img-services" />
          </a>
          <span class="title-services">Police</span>
        </div>
        <div class="col-4 col-lg-3">
          <a
            href="https://www.covid19india.org/"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/corona.jpg" class="img-services" />
          </a>
          <span class="title-services">Corona Dashboard</span>
        </div>
        <div class="col-4 col-lg-3">
          <a
            href="https://labouronline.kar.nic.in/"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/labour.webp" class="img-services" />
          </a>
          <span class="title-services">e-Labour</span>
        </div>
        <div class="col-4 col-lg-3">
          <a href="http://kspcb.gov.in/" target="blank" class="img-anchor">
            <img src="~static/images/pollution.jpg" class="img-services" />
          </a>
          <span class="title-services">Air Pollution</span>
        </div>
        <div class="col-4 col-lg-3">
          <a href="https://bbmp.gov.in/" target="blank" class="img-anchor">
            <img src="~static/images/bbmp.png" class="img-services" />
          </a>
          <span class="title-services">BBMP</span>
        </div>
        <div class="col-4 col-lg-3">
          <a
            href="http://www.schooleducation.kar.nic.in/index.html"
            target="blank"
            class="img-anchor"
          >
            <img src="~static/images/education.webp" class="img-services" />
          </a>
          <span class="title-services">Education</span>
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
    padding: 0;
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
    height: 220px;
  }
  .img-services {
    border-radius: 50%;
    width: 68px;
    height: 68px;
    background: white;
  }
}

@media (min-width: 37.5em) and (max-width: 1024px) {
  .index-img {
    background-image: url("~static/images/vidhan_soudha_medium.webp");
    height: 400px;
  }
}

.title-services {
  display: block;
  text-align: center;
  font-size: 14px;
  white-space: nowrap;
}
</style>
