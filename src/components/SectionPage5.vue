<template>
  <section class="playlist_articles">
    <div class="playlist_art container py-5">
      <div class="text_playlist d-flex justify-content-between pb-3">
        <h5>
          Latest articles
        </h5>
        <!-- eslint-disable-next-line -->
        <div><a href="#!"><strong>Read all articles</strong> <i class="fa-solid fa-chevron-right" /></a></div>
      </div>
      <div class="row row-cols-3">
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/blog4-2x-1200x773.jpg"
            alt=""
          >
          <div class="subtext_box text-center p-1">
            <h6>The best protein shake</h6>
            <div class="text_img">
              By admin | November 26th, 2019 | Gym
            </div>
          </div>
        </div>
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/blog1-2x-1200x773.jpg"
            alt=""
          >
          <div class="subtext_box text-center p-1">
            <h6>Ultimate cardio workout</h6>
            <div class="text_img">
              By admin | November 26th, 2019 | Gym
            </div>
          </div>
        </div>
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/blog3-2x-1200x773.jpg"
            alt=""
          >
          <div class="subtext_box text-center p-1">
            <h6>New juices available now</h6>
            <div class="text_img">
              By admin | November 26th, 2019 | Gym
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionPage5',

};
</script>

<style lang="scss" scoped>
a {
  text-decoration: none;
  color: #000000;
}
.col img {
    padding-bottom: .5em;
    &:hover {
      transform: scale(1.1);
    }
}
</style>
