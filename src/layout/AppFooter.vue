<template>
  <footer class="footer has-cards">
    <!-- <div class="container container-lg">
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/landing" title="Landing Page">
                            <img v-lazy="'img/theme/landing.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/profile" title="Profile Page">
                            <img v-lazy="'img/theme/profile.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
            </div>
    </div>-->
    <div class="container">
      <div
        id="navbarBottom"
        class="row align-content-center justify-content-around fixed-bottom"
        style="font-size:2rem"
      >
        <a
          class="nav-link nav-link-icon"
          href="https://www.facebook.com/creativetim"
          target="_blank"
          rel="noopener"
          data-toggle="tooltip"
          title="Like us on Facebook"
        >
          <i class="fa fa-facebook-square"></i>
        </a>

        <a
          class="nav-link nav-link-icon"
          href="https://www.instagram.com/creativetimofficial"
          target="_blank"
          rel="noopener"
          data-toggle="tooltip"
          title="Follow us on Instagram"
        >
          <i class="fa fa-instagram"></i>
        </a>

        <a
          class="nav-link nav-link-icon"
          href="https://twitter.com/creativetim"
          target="_blank"
          rel="noopener"
          data-toggle="tooltip"
          title="Follow us on Twitter"
        >
          <i class="fa fa-twitter-square"></i>
        </a>

        <!-- <a
          class="nav-link nav-link-icon"
          href="https://github.com/creativetimofficial/vue-argon-design-system"
          target="_blank"
          rel="noopener"
          data-toggle="tooltip"
          title="Star us on Github"
        >
          <i class="fa fa-github"></i>
        </a>-->
      </div>
    </div>
  </footer>
</template>
<script>
export default {};
</script>
<style>
#navbarBottom {
  height: 2em;
  background-color: #7c9465;
}
</style>
