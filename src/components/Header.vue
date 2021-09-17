<template>
  <header>
    <!-- ADDED STICKYNESS WITH FIXED TOP RULE-->
    <nav class="navbar navbar-expand-sm navbar-light bg-white fixed-top">
      <div class="container">
        <ul class="navbar-nav mb-2 mb-lg-0 f-12">
          <!-- INSERIMENTO VOCI MENU DINAMICO -->
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
        <!-- LOGO CENTRALE-->
        <img src="@/assets/images/dark-logo.png" alt="Max Logo" />

        <!-- ICONE + SEARCHBAR -->
        <form class="d-flex">
          <div class="nav-icons d-flex align-items-center me-3">
            <i class="fas fa-shopping-cart me-3 clickable"></i>
            <i class="far fa-user-circle clickable"></i>
          </div>
          <input class="form-control f-12" type="text" placeholder="Search" />
          <button
            class="btn btn-outline-secondary"
            type="button"
            id="button-addon2"
          >
            <i class="fas fa-search main-color"></i>
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
          url: "#",
        },
        {
          text: "Pages",
          url: "#",
        },
        {
          text: "Courses",
          url: "#",
        },
        {
          text: "Features",
          url: "#",
        },
        {
          text: "Blog",
          url: "#",
        },
        {
          text: "Shop",
          url: "#",
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
}
</style>