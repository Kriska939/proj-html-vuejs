<template>
  <div class="mt-5 pt-2">
    <section id="jumbotron" class="container-fluid">
      <div class="row align-items-center text-center h-400">
        <div class="col-12">
          <h3 class="c-white">Commence Business</h3>
          <h1 class="mb-4 fw-300">Distant Mentoring Program</h1>
          <button class="btn btn-outline-success fw-bold f-12 p-3 main-color">
            Download free guidebook <i class="fas fa-arrow-right"></i>
          </button>
        </div>
      </div>
    </section>
    <section class="infoBox mt-5 d-flex">
      <div class="infoText me-5 pt-5">
        <div class="mb-2">
          <h6 class="f-12 d-inline">EVERYTHING IN</h6>
          <span class="f-12 cinder fw-bold"> MAXCOACH</span>
        </div>
        <div class="mb-2">
          <h3 class="d-inline">Learn about our</h3>
          <span class="f-30 main-color"> Work Culture </span>
          <h3 class="d-inline">at MaxCoach</h3>
        </div>
        <p class="description f-12">
          Spend some time to visit our website or head office and discover our
          current courses, enrollment procedure, and registration deadline.
          We're opening new classes every beginning of each month.
        </p>
        <p class="description d-inline f-12">Have questions?&nbsp;</p>
        <a href="#" class="f-12 main-color fw-bold"
          >Get Free Guide <i class="fas fa-arrow-right"></i
        ></a>
      </div>
      <div class="infoImg ps-5 pt-5">
        <img src="../assets/images/people-infobox1.jpg" alt="Office" />
        <img
          src="../assets/images/extra-img.jpg"
          alt="Office Lady"
          class="extra-img"
        />
      </div>
    </section>
    <section
      id="numbers"
      class="d-flex justify-content-center mb-5 text-center"
    >
      <div class="me-5">
        <h3 class="fw-bold f-30 main-color">129+</h3>
        <h6 class="f-12 fw-bold">ENROLLED LEARNERS</h6>
      </div>
      <div class="me-5">
        <h3 class="fw-bold f-30 main-color">80</h3>
        <h6 class="f-12 fw-bold">FINISHED SESSIONS</h6>
      </div>
      <div class="me-5">
        <h3 class="fw-bold f-30 main-color">4%</h3>
        <h6 class="f-12 fw-bold">SATISFACTION RATE</h6>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style scoped lang="scss">
@import "@/assets/scss/_vars.scss";
.h-400 {
  height: 450px;
}

#jumbotron {
  background-image: url("../assets/images/home-3-hero-bg.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

h1,
.c-white {
  color: $white;
}

.btn {
  background-color: $white;
  border: 1px solid white;
}

.btn:hover {
  background-color: $mountain-meadow;
  color: $white;
}

.infoBox {
  max-width: 950px;
  margin: 0 auto;
  max-height: 450px;

  .infoText {
    width: 30%;
    height: 70%;
  }

  .infoImg {
    width: 70%;
    background-image: url("../assets/images/maxcoach-shape-02.png"),
      url("../assets/images/maxcoach-shape-07-150x150.png");
    background-repeat: no-repeat;
    background-position: right bottom, center top;
    padding-bottom: 50px;
    height: 70%;
    position: relative;
  }

  .extra-img {
    position: absolute;
    top: 0;
    transform: translateX(-70%);
    border-radius: 5px;
  }
}
</style>