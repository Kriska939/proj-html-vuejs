<template>
  <div class="mt-5 pt-2">
    <!-- JUMBOTRON-->
    <section id="jumbotron" class="container-fluid">
      <div class="row align-items-center text-center h-400">
        <div class="col-12">
          <h3 class="c-white">Commence Business</h3>
          <h1 class="mb-4 fw-300">Distant Mentoring Program</h1>
          <button
            class="
              btn btn-outline-success btn-jumbotron
              fw-bold
              f-12
              px-4
              py-2
              main-color
            "
          >
            Download free guidebook <i class="fas fa-arrow-right"></i>
          </button>
        </div>
      </div>
    </section>

    <!-- FIRST SECTION HALF TEXT HALF IMG -->
    <section class="infoBox mt-5 d-flex">
      <div class="infoTextType1 me-5 pt-5">
        <div class="mb-2">
          <h6 class="f-12 d-inline">EVERYTHING IN</h6>
          <span class="f-12 cinder fw-bold"> MAXCOACH</span>
        </div>
        <div class="mb-2">
          <h2 class="d-inline fw-bold f-35">Learn about our</h2>
          <span class="f-35 main-color"> Work Culture </span>
          <h2 class="d-inline fw-bold f-35">at MaxCoach</h2>
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
      <div class="infoImgType1 pt-5">
        <img
          src="../assets/images/people-infobox1.jpg"
          alt="Office"
          class="img-fluid br-5"
        />
        <img
          src="../assets/images/extra-img.jpg"
          alt="Office Lady"
          class="extra-img br-5"
        />
      </div>
    </section>

    <!-- SECTION ABOUT SITE STATS -->
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
    <!-- SECOND SECTION HALF TEXT HALF IMG -->
    <section class="infoBox mt-5 mb-5 d-flex">
      <div class="infoImgType2 pt-5">
        <img
          src="../assets/images/infobox-2.jpg"
          alt="Office"
          class="img-fluid br-5"
        />
        <img
          src="../assets/images/icon-youtube-play.png"
          alt="Youtube Icon"
          class="youtube clickable"
        />
      </div>
      <div class="infoTextType2 ms-5 pt-5">
        <div class="mb-2 mt-4">
          <h6 class="f-12 d-inline fw-bold">HOW WE WORK</h6>
        </div>
        <div class="mb-2">
          <h2 class="d-inline fw-bold f-35">Upgrade Your Skills</h2>
          <span class="f-35 main-color"> Upgrade Your Life </span>
        </div>
        <p class="description f-12">
          Opening up more opportunities in front of you to get the ticket to
          more enjoyable door in life. Getting equipped with new skills for new
          sets of insights into your career. <br />MaxCoach accompany learners
          in every stage of learning.
        </p>
        <a href="#" class="f-12 cinder fw-bold"
          >Download free guidebook <i class="fas fa-arrow-right"></i
        ></a>
      </div>
    </section>
    <!-- FIRST SECTION WITH CARDS (includes "courses" component) -->
    <section class="cardsShowcase bg-grey br-special pb-5">
      <div class="text-center">
        <h6 class="f-12 fw-bold pt-3">JOIN MAXCOACH AT BEST</h6>
        <div class="mb-5">
          <h2 class="d-inline fw-bold f-35">Latest Online</h2>
          <span class="f-35 main-color"> Courses </span>
        </div>
      </div>
      <div class="infoBox">
        <Courses />
        <div class="text-center w-400 m-auto">
          <p class="d-inline f-12 fw-600">
            Control your personal preference settings to get notified about
            appropriate courses.
          </p>
          <a href="#" class="f-12 main-color fw-bold"
            >View all courses <i class="fas fa-arrow-right"></i
          ></a>
        </div>
      </div>
    </section>

    <!-- THIRD SECTION HALF TEXT HALF IMG -->
    <section class="infoBox mt-5 d-flex">
      <div class="infoTextType1 me-5 pt-5">
        <div class="mb-2">
          <h6 class="f-12 d-inline">TESTIMONIALS</h6>
        </div>
        <div class="mb-2">
          <h2 class="d-inline fw-bold f-35">Why Do People</h2>
          <span class="f-35 main-color"> *Hearts* </span>
          <h2 class="d-inline fw-bold f-35">Us?</h2>
        </div>
        <p class="description f-12">
          Seeking for verbals of our service quality? Find them here. <br />
          Everything is transparent and straightforward for your sense of
          justification.
        </p>
        <a href="#" class="f-12 cinder fw-bold"
          >View all <i class="fas fa-arrow-right"></i
        ></a>
      </div>
      <div class="infoImg pt-5">
        <img
          src="../assets/images/infobox-missing.jpg"
          alt="Office"
          class="img-fluid br-5"
        />
      </div>
    </section>

    <!-- FOURTH SECTION HALF TEXT HALF IMG -->
    <section class="infoBox mt-5 mb-5 d-flex">
      <div class="infoImgType3 pt-5">
        <img
          src="../assets/images/team-image-big.png"
          alt="Team Image"
          class="img-fluid br-5"
        />
      </div>
      <div class="infoTextType2 ms-5 pt-5">
        <div class="mb-2 mt-5">
          <h6 class="f-12 d-inline">EVERYTHING IN</h6>
          <span class="f-12 cinder fw-bold"> MAXCOACH</span>
        </div>
        <div class="mb-2">
          <h2 class="d-inline fw-bold f-35">We're Here to</h2>
          <span class="f-35 main-color"> Transform </span>
          <h2 class="d-inline fw-bold f-35">You!</h2>
        </div>
        <p class="description f-12">
          As learners, people can enjoy great companionship from MaxCoach
          mentors and educators. We can help you develop and grow at your best.
        </p>
        <button
          class="
            btn btn-outline-success btn-freebie
            fw-bold
            f-12
            px-4
            main-color
          "
        >
          Get free guide
        </button>
      </div>
    </section>

    <!-- SECOND SECTION WITH CARDS (includes "posts" component) -->
    <section class="cardsShowcase bg-grey pb-5 pt-5">
      <div class="text-center">
        <h6 class="f-12 fw-bold pt-3">JOIN MAXCOACH AT BEST</h6>
        <div class="mb-5">
          <h2 class="d-inline fw-bold f-35">Latest From</h2>
          <span class="f-35 main-color"> Our Blogs </span>
        </div>
      </div>
      <div class="infoBox">
        <Posts />
        <div class="text-center w-400 m-auto">
          <p class="d-inline f-12 fw-600">
            Control your personal preference settings to get notified about
            appropriate courses.
          </p>
          <a href="#" class="f-12 main-color fw-bold"
            >View all courses <i class="fas fa-arrow-right"></i
          ></a>
        </div>
      </div>
    </section>

    <!-- NEWSLETTER SECTION -->
    <section id="newsletter" class="mb-5">
      <div class="mb-2 mt-5 text-center">
        <h2 class="d-inline fw-bold f-35 cinder">Subscribe</h2>
        <span class="f-35 main-color"> Newsletters </span>
      </div>
      <div class="text-center w-400 m-auto">
        <p class="d-inline f-12 fw-600">
          Enter your email address to register to our newsletter subscription
          delivered on a regular bases!
        </p>
        <div class="input-group mb-3 mt-3 f-12">
          <input
            type="text"
            class="form-control f-12"
            placeholder="Enter your email"
          />
          <div class="input-group-append">
            <button
              class="
                btn btn-outline-success btn-freebie
                newsButton
                fw-bold
                f-12
                py-2
                px-3
                main-color
              "
            >
              Subscribe
            </button>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Courses from "./Courses.vue";
import Posts from "./Posts.vue";
export default {
  name: "Main",
  components: {
    Courses,
    Posts,
  },
};
</script>

<style scoped lang="scss">
@import "@/assets/scss/_vars.scss";

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

.btn-jumbotron {
  background-color: $white;
  border: 1px solid white;
}

.btn-freebie {
  background-color: $mountain-meadow;
  color: $white;
  border: none;
}

.btn-jumbotron:hover {
  background-color: $mountain-meadow;
  color: $white;
}

.btn-freebie:hover {
  background-color: white;
  color: $mountain-meadow;
}

.infoTextType1 {
  width: 40%;
  height: 60%;
}

.infoTextType2 {
  width: 30%;
  height: 60%;
}

.infoImg {
  width: 60%;
  padding-bottom: 50px;
  padding-right: 20px;
  height: 70%;
}

.infoImgType1 {
  width: 60%;
  background-image: url("../assets/images/maxcoach-shape-02.png"),
    url("../assets/images/maxcoach-shape-07-150x150.png");
  background-repeat: no-repeat;
  background-position: right bottom, center top;
  padding-bottom: 50px;
  padding-right: 20px;
  height: 70%;
  position: relative;
}

.infoImgType2 {
  width: 70%;
  background-image: url("../assets/images/maxcoach-shape-07-150x150.png"),
    url("../assets/images/maxcoach-shape-05-150x150.png"),
    url("../assets/svg/svg-0.svg");
  background-repeat: no-repeat;
  background-position: right bottom, left center, left top;
  padding-bottom: 40px;
  padding-right: 20px;
  padding-left: 70px;
  height: 70%;
  position: relative;
}

.infoImgType3 {
  width: 55%;
  background-image: url("../assets/images/maxcoach-shape-07-150x150.png"),
    url("../assets/images/maxcoach-shape-05-150x150.png"),
    url("../assets/svg/svg-0.svg");
  background-repeat: no-repeat;
  background-position: right bottom, left center, left top;
  padding-bottom: 40px;
  padding-right: 20px;
  padding-left: 70px;
  height: 60%;
  position: relative;
}

.extra-img {
  position: absolute;
  top: 0;
  transform: translateX(-70%);
}

.youtube {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-30%, -50%);
}

.bg-grey {
  background-color: rgb(245, 245, 245);
}

.br-special {
  border-radius: 0px 0px 15% 15%;
}

input,
button {
  border: none;
  background-color: rgb(231, 230, 230);
}

.newsButton {
  border-radius: 0px 5px 5px 0px;
}

#newsletter {
  background-image: url("../assets/images/maxcoach-shape-02.png"),
    url("../assets/images/maxcoach-shape-09.png"),
    url("../assets/images/maxcoach-shape-01.png");
  background-repeat: no-repeat;
  background-position: right bottom, right top, left bottom;
  height: 230px;
  width: 950px;
  margin: 0 auto;
}
</style>