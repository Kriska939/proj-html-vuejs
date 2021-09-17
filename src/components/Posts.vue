<template>
  <div class="cards d-flex justify-content-center pb-5">
    <div
      class="card me-4"
      style="width: 20rem"
      v-for="(post, index) in postsData"
      :key="index"
    >
      <img class="card-img-top" :src="post.picture" alt="Card image cap" />
      <div class="card-body">
        <h5 class="card-text fw-600 cinder pb-2 f-18">{{ post.name }}</h5>
        <div class="courseInfo d-flex">
          <div class="lessons me-4">
            <i class="far fa-calendar pe-2"></i>
            <span class="f-12"> {{ post.date }}</span>
          </div>
          <div class="students">
            <i class="far fa-eye pe-2"></i>
            <span class="f-12"> {{ post.views + " views" }}</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Posts",
  data() {
    return {
      postsData: [
        {
          picture: require("../assets/images/blog-1.jpeg"),
          name: "Brush Strokes Energize Trees in Paintings",
          date: "May 15, 2020",
          views: "688",
        },
        {
          picture: require("../assets/images/blog-2.jpg"),
          name: "Pocket-Sized Notebooks Hold Miniature Paintings",
          date: "May 15, 2020",
          views: "603",
        },
        {
          picture: require("../assets/images/blog-3.jpg"),
          name: "Connection Between Self-Portraits and Identity",
          date: "May 15, 2020",
          views: "397",
        },
      ],
    };
  },
};
</script>

<style>
</style>