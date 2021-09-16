<template>
  <div>
    <section id="jumbotron" class="container-fluid">
      <div class="row align-items-center text-center h-400">
        <div class="col-12">
          <h3 class="c-white">Commence Business</h3>
          <h1 class="mb-4">Distant Mentoring Program</h1>
          <button class="btn btn-outline-success btn-green-color">
            Download Free Guidebook <i class="fas fa-arrow-right"></i>
          </button>
        </div>
      </div>
    </section>
    <section class="infoBox pt-5 pb-5 mt-5 d-flex">
      <div class="infoText me-5">
        <h6>EVERYTHING IN MAXCOACH</h6>
        <h3>Learn about our Work</h3>
        <p class="description">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil porro
          quisquam, fugiat provident nobis fuga architecto cumque in, adipisci
          impedit quibusdam excepturi ut totam omnis a facere soluta accusamus!
          Ab.
        </p>
        <p class="description">Do you want to know more? Click here</p>
      </div>
      <div class="infoImg ms-5">
        <img src="../assets/images/people-infobox1.jpg" alt="Office" />
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

.btn-green-color {
  background-color: $white;
  color: $mountain-meadow;
  border: 1px solid white;
}

.btn:hover {
  background-color: $mountain-meadow;
  color: $white;
}

.infoBox {
  max-width: 950px;
  margin: 0 auto;

  .infoText {
    width: 30%;
  }

  .infoImg {
    width: 70%;
  }
}
</style>