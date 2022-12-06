<template>
  <section class="sponsor_section">
    <div class="sponsor_sect container py-5">
      <div class="row row-cols-sm-2 row-cols-lg-4 text-center container p-3 g-5">
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/sponsor-1-2x.png"
            alt=""
          >
          <div class="icon_box">
            <i class="fa-solid fa-chevron-up blue_icon" />
            <i class="fa-solid fa-chevron-up blue_icon" />
            <i class="fa-solid fa-chevron-up blue_icon" />
          </div>
          <div class="subtext_box text-center p-1">
            <!-- eslint-disable-next-line -->
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae iure unde autem nam a inventore molestiae.</p>
            <a href="#!"><strong>Visit Yoga Studio</strong>
              <i class="fa-solid fa-chevron-right" /></a>
          </div>
        </div>
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/sponsor-2-2x.png"
            alt=""
          >
          <div class="icon_box">
            <i class="fa-solid fa-chevron-up blue_icon" />
            <i class="fa-solid fa-chevron-up blue_icon" />
            <i class="fa-solid fa-chevron-up blue_icon" />
          </div>
          <div class="subtext_box text-center p-1">
            <!-- eslint-disable-next-line -->
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae iure unde autem nam a inventore molestiae.</p>
            <a href="#!"><strong>Join Fitness Center</strong>
              <i class="fa-solid fa-chevron-right" /></a>
          </div>
        </div>
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/sponsor-3-2x.png"
            alt=""
          >
          <div class="icon_box">
            <i class="fa-solid fa-chevron-up blue_icon" />
            <i class="fa-solid fa-chevron-up blue_icon" />
            <i class="fa-solid fa-chevron-up blue_icon" />
          </div>
          <div class="subtext_box text-center p-1">
            <!-- eslint-disable-next-line -->
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae iure unde autem nam a inventore molestiae.</p>
            <a href="#!"><strong>Learn about FC</strong>
              <i class="fa-solid fa-chevron-right" /></a>
          </div>
        </div>
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/sponsor-4-2x.png"
            alt=""
          >
          <div class="icon_box">
            <i class="fa-solid fa-chevron-up blue_icon" />
            <i class="fa-solid fa-chevron-up blue_icon" />
            <i class="fa-solid fa-chevron-up blue_icon" />
          </div>
          <div class="subtext_box text-center p-1">
            <!-- eslint-disable-next-line -->
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae iure unde autem nam a inventore molestiae.</p>
            <a href="#!"><strong>Visit Power Gym</strong>
              <i class="fa-solid fa-chevron-right" /></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionPage7',

};
</script>

<style lang="scss" scoped>
a {
  text-decoration: none;
  color: #000000;
}

.blue_icon {
  color: rgb(1, 162, 255);
}

.col {
  .col img {
    width: 200px;
    padding-bottom: .5em;
  }
  &:hover {
    cursor: pointer;
    transform: scale(1.1);
  }
}

</style>
