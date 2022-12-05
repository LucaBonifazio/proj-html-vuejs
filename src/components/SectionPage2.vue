<template>
  <section class="choise_sect">
    <div class="container">
      <div class="row row-cols-3 container card_box">
        <div class="col image_1">
          <div class="card text-bg-dark">
            <img
              src="@/assets/img/service6-2x.jpg"
              class="card-img"
              alt="photo"
            >
            <div class="card-img-overlay">
              <i class="fa-solid fa-chevron-up" />
              <i class="fa-solid fa-chevron-up" />
              <i class="fa-solid fa-chevron-up" />
              <h5 class="card-title">
                Crossfit Workout
              </h5>
              <div class="card-text">
                Push your limit
              </div>
            </div>
          </div>
        </div>
        <div class="col image_2">
          <div class="card text-bg-dark">
            <img
              src="@/assets/img/box1-2x.jpg"
              class="card-img"
              alt="photo"
            >
            <div class="card-img-overlay">
              <i class="fa-solid fa-chevron-up" />
              <i class="fa-solid fa-chevron-up" />
              <i class="fa-solid fa-chevron-up" />
              <h5 class="card-title">
                New gym apparel
              </h5>
              <div class="card-text">
                Look good, feel good
              </div>
            </div>
          </div>
        </div>
        <div class="col image_3">
          <div class="card text-bg-dark">
            <img
              src="@/assets/img/box3-2x.jpg"
              class="card-img"
              alt="photo"
            >
            <div class="card-img-overlay">
              <i class="fa-solid fa-chevron-up" />
              <i class="fa-solid fa-chevron-up" />
              <i class="fa-solid fa-chevron-up" />
              <h5 class="card-title">
                Team training
              </h5>
              <div class="card-text">
                Fidn a partner
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="motivational_text container text-center">
        <!-- eslint-disable-next-line -->
          <p class="text-white">"How you respond to the challenge in the second half will determine what you become after the game, whether you are a winner or a loser."</p>
        <i class="fa-solid fa-chevron-up gold_icon" />
        <i class="fa-solid fa-chevron-up gold_icon" />
        <i class="fa-solid fa-chevron-up gold_icon" />
        <div class="image_box">
          <img
            class="avatar_image img-fluid"
            src="@/assets/img/avatar-1-2x.jpg"
            alt="photo"
          >
          <span class="avatar_name text-white px-4">Brad Johnson</span>
          <small class="avatar_loco">Las Vegas</small>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FooterPage',

};
</script>

<style scoped lang="scss">
  .choise_sect {
    position: relative;
    background-image: linear-gradient(to bottom right, #2805c4, #bc0428);
    height: 800px;
  }

  .image_1,
  .image_2,
  .image_3 {
    padding: 1em;
    max-width: 300px;
    height: 300px;
  }

  .card:hover {
    transform: scale(1.2);
  }
  .card-img-overlay {
    padding-top: 10rem;
  }

  .card-text,
  .gold_icon {
    color: gold;
  }

  .motivational_text {
    font-size: 2rem;
    max-width: 750px;
    padding-top: 20rem;
  }

  .card_box {
    justify-content: center;
    position: absolute;
    top: -70px;
    inherits: 0;
  }

  .image_box {
    .avatar_image {
      border-radius: 10rem;
    }
    &:hover {
      cursor: pointer;
      transform: scale(1.2);
    }
  }
</style>
