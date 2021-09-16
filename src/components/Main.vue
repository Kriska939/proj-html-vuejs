<template>
  <section id="jumbotron" class="container-fluid">
    <div class="row align-items-center text-center h-400">
      <div class="col-12">
        <h3>Commence Business</h3>
        <h1 class="mb-4">Distant Mentoring Program</h1>
        <button class="btn btn-outline-success btn-green-color">
          Download Free Guidebook <i class="fas fa-arrow-right"></i>
        </button>
      </div>
    </div>
  </section>
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
h3 {
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
</style>