<template>
  <footer class="container-fluid">
    <div class="infoBox pt-5 d-flex justify-content-around">
      <div id="address">
        <ul class="p-0 f-12 fw-bold">
          <h6 class="white fw-bold">Address</h6>
          <li class="pb-2">{{ companyAddress.road }}</li>
          <li class="pb-2">{{ companyAddress.contacts }}</li>
          <li class="pb-2">{{ companyAddress.mail }}</li>
        </ul>
        <div class="social">
          <i class="fab fa-facebook-square me-3 clickable"></i>
          <i class="fab fa-twitter-square me-3 clickable"></i>
          <i class="fab fa-instagram me-3 clickable"></i>
          <i class="fab fa-linkedin clickable"></i>
        </div>
      </div>
      <div id="browsePages" class="d-flex">
        <ul class="p-0 me-4 f-12 fw-bold w-250">
          <h6 class="white fw-bold">Explore</h6>
          <div class="d-flex">
            <div class="col-6">
              <li
                v-for="(page, index) in sitePages1"
                :key="index"
                class="pe-4 pb-2"
              >
                <a href="#">{{ page.title }}</a>
              </li>
            </div>
            <div class="col-6">
              <li
                v-for="(page, index) in sitePages2"
                :key="index"
                class="pe-4 pb-2"
              >
                <a href="#">{{ page.title }}</a>
              </li>
            </div>
          </div>
        </ul>
        <ul class="p-0 me-4 f-12 fw-bold">
          <h6 class="white fw-bold">Information</h6>
          <li v-for="(page, index) in infoPages" :key="index" class="pe-4 pb-2">
            <a href="#">{{ page.title }}</a>
          </li>
        </ul>
      </div>
    </div>
    <div id="copyright">
      <p class="pt-4 text-center f-12">&copy; Maxcoach. All rights reserved</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",

  data() {
    return {
      companyAddress: {
        road: "382 NE 191st St # 87394 Miami, FL 33179-3899",
        contacts: "+1(305)547-9909 (9am - 5pm EST, Monday - Friday",
        mail: "support@maxcoach.com",
      },

      sitePages1: [
        {
          title: "Start Here",
          url: "#",
        },
        {
          title: "Blog",
          url: "#",
        },
        {
          title: "About us",
          url: "#",
        },
      ],

      sitePages2: [
        {
          title: "Success story",
          url: "#",
        },
        {
          title: "Courses",
          url: "#",
        },
        {
          title: "Contact us",
          url: "#",
        },
      ],

      infoPages: [
        {
          title: "Membership",
          url: "#",
        },
        {
          title: "Purchase guide",
          url: "#",
        },
        {
          title: "Privacy policy",
          url: "#",
        },
        {
          title: "Terms of service",
          url: "#",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
@import "@/assets/scss/_vars.scss";

footer {
  background-color: $vulcan;
  height: 280px;
}

ul {
  list-style-type: none;
}

.social {
  i {
    font-size: 20px;
  }
}

#browsePages {
  a {
    text-decoration: none;
    color: $storm-dust;
  }
}
</style>