<template>
  <div class="cards d-flex justify-content-center">
    <div
      class="card me-5"
      style="width: 18rem"
      v-for="(card, index) in cardData"
      :key="index"
    >
      <img class="card-img-top" :src="card.picture" alt="Card image cap" />
      <div class="card-body">
        <h5 class="card-title">{{ card.price }}</h5>
        <p class="card-text">{{ card.name }}</p>
        <div class="courseInfo d-flex">
          <div class="lessons me-4">
            <i class="far fa-file-alt"></i>
            <span> {{ card.lessons + " Lessons" }}</span>
          </div>
          <div class="students">
            <i class="far fa-user"></i>
            <span> {{ card.lessons + " Students" }}</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  data() {
    return {
      cardData: [
        {
          picture: "../assets/images/course1.jpg",
          price: "$40.00",
          name: "Learning to Write as a Professional Author",
          lessons: "20",
          students: "50",
        },
        {
          picture: "../assets/images/course2.jpg",
          price: "$0.00",
          name: "Customer-Centric Info-Tech Strategies",
          lessons: "24",
          students: "769",
        },
        {
          picture: "../assets/images/course3.jpg",
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

<style>
</style>