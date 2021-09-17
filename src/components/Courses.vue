<template>
  <div class="cards d-flex justify-content-center pb-5">
    <div
      class="card me-4"
      style="width: 20rem"
      v-for="(course, index) in coursesData"
      :key="index"
    >
      <img class="card-img-top" :src="course.picture" alt="Card image cap" />
      <div class="card-body">
        <h3 class="card-title main-color fw-bold">{{ course.price }}</h3>
        <h5 class="card-text fw-600 cinder pb-2 f-18">{{ course.name }}</h5>
        <div class="courseInfo d-flex">
          <div class="lessons me-4">
            <i class="far fa-file-alt pe-2"></i>
            <span class="f-12 fw-600"> {{ course.lessons + " Lessons" }}</span>
          </div>
          <div class="students">
            <i class="far fa-user pe-2"></i>
            <span class="f-12 fw-600"> {{ course.lessons + " Students" }}</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Courses",
  data() {
    return {
      coursesData: [
        {
          picture: require("../assets/images/course1.jpg"),
          price: "$40.00",
          name: "Learning to Write as a Professional Author",
          lessons: "20",
          students: "50",
        },
        {
          picture: require("../assets/images/course2.jpg"),
          price: "$0.00",
          name: "Customer-Centric Info-Tech Strategies",
          lessons: "24",
          students: "769",
        },
        {
          picture: require("../assets/images/course3.jpg"),
          price: "$19.00",
          name: "Open Programming Courses for Everyone: Python",
          lessons: "17",
          students: "62",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
.card:hover {
  padding: 10px;
  box-shadow: 5px 5px rgb(202, 202, 202);
}
</style>