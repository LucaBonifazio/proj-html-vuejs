<template>
  <footer class="bg__black position-relative">
    <div class="container pt-5">
      <div class="row row-cols-sm-1 row-cols-md-2 row-cols-lg-3 text-center">
        <div class="col text- copyright_div">
          <img
            class="logo_footer"
            src="@/assets/img/logo-2x.png"
            alt="logo"
          >
          <!-- eslint-disable-next-line -->
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet quisquam molestias harum, consequatur.Amet quisquam molestias harum, consequatur.</p>
          <div class="icon_box">
            <i class="fa-brands fa-facebook-f" />
            <i class="fa-brands fa-twitter" />
            <i class="fa-brands fa-youtube" />
            <i class="fa-brands fa-instagram" />
            <i class="fa-brands fa-linkedin-in" />
          </div>
        </div>
        <div class="col text-center">
          <h5>RECENT POSTS</h5>
          <ul>
            <li
              v-for="post in posts"
              :key="post.i"
            >
              <a href="#!"><i class="fa-solid fa-chevron-right" />{{ post }}</a>
            </li>
          </ul>
        </div>
        <div class="col text-center">
          <h5>CONCTAT INFORMATION</h5>
          <div
            class="pb-4"
            style="color: lightgrey"
          >
            4746 Tipple Road Michigan 48449
          </div>
          <div><strong>Mobile: 1.800.000.0000</strong></div>
          <div><strong>Email: info@your-company.com</strong></div>
        </div>
      </div>
    </div>
    <hr class="mt-5">
    <div
      class="container text-center"
      style="color:lightgrey"
    >
      <!-- eslint-disable-next-line -->
      <div class="p-4"><i class="fa-regular fa-copyright"></i> Copyright 2012 -2020|Avada theme by <strong style="color: white">ThemFusion</strong>|All rights reserved|Powere by <strong style="color: white">WordPress</strong></div>
    </div>
    <!-- eslint-disable-next-line -->
    <a href="#start_app">
      <i class="fa-solid fa-chevron-up icon_multiverse" />
    </a>
  </footer>
</template>

<script>
export default {
  name: 'FooterPage',
  props: {
    posts: Array,
  },
};
</script>

<style scoped lang="scss">
  .bg__black{
    color: rgb(255, 255, 255);
    background-color: rgb(0, 0, 0);
  }

  .logo_footer{
    width: 200px;
    padding-bottom: 2rem;
    &:hover {
    transform: scale(1.1);
  }
  }

  .icon_box i {
    color: #ec5a57;
    padding: .7rem;
    &:hover {
      color: #bc0428;
    }
  }

  li {
    list-style: none;
    a {
      color: rgb(255, 255, 255);
      text-decoration: none;
    }
  }

  .icon_multiverse {
    position: absolute;
    bottom: 0;
    right: 50px;
    padding: .6em 1em;
    border-radius: 2px;
    color: rgb(255, 255, 255);
    background-color: rgb(56, 56, 56);
    &:hover {
      background-color: rgb(109, 109, 109);
    }
  }
</style>
