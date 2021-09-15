<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-white">
      <div class="container">
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li
              class="nav-item dropdown"
              v-for="(option, index) in navOptions"
              :key="index"
            >
              <a class="nav-link text-dark dropdown-toggle" href="#">
                {{ option.text }}</a
              >
            </li>
          </ul>
          <!--ADD LOGO-->
          <figure>
            <img src="" alt="" />
          </figure>
          <form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <button class="btn btn-outline-secondary" type="button">
              <i class="fas fa-search"></i>
            </button>
          </form>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      navOptions: [
        {
          text: "Home",
        },
        {
          text: "Pages",
        },
        {
          text: "Courses",
        },
        {
          text: "Features",
        },
        {
          text: "Blog",
        },
        {
          text: "Shop",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
nav {
  height: 70px;
}
</style>