<template>
  <header>
    <nav class="navbar navbar-expand-sm navbar-light bg-white">
      <div class="container">
        <ul class="navbar-nav mb-2 mb-lg-0">
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
        <img src="@/assets/images/dark-logo.png" alt="Max Logo" />
        <form class="d-flex">
          <div class="nav-icons d-flex align-items-center me-3">
            <i class="fas fa-shopping-cart me-3"></i>
            <i class="far fa-user-circle"></i>
          </div>
          <input class="form-control" type="text" placeholder="Search" />
          <button
            class="btn btn-outline-secondary"
            type="button"
            id="button-addon2"
          >
            <i class="fas fa-search"></i>
          </button>
        </form>
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
img {
  max-width: 120px;
}

input,
button {
  border: none;
  background-color: rgb(231, 230, 230);
}

input {
  border-radius: 5px 0px 0px 5px;
}

button {
  border-radius: 0px 5px 5px 0px;

  i {
    color: lightskyblue;
  }
}
</style>