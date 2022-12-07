<template>
  <section class="choise_sect">
    <div class="container">
      <div class="row row-cols-3 container card_box">
        <div class="col">
          <div class="card text-bg-dark">
            <img
              src="@/assets/img/service6-2x.jpg"
              class="card-img"
              alt="photo"
            >
            <div class="card-img-overlay gradient_box">
              <div class="container_img_text">
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
        </div>
        <div class="col">
          <div class="card text-bg-dark">
            <img
              src="@/assets/img/box1-2x.jpg"
              class="card-img"
              alt="photo"
            >
            <div class="card-img-overlay gradient_box">
              <div class="container_img_text">
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
        </div>
        <div class="col">
          <div class="card text-bg-dark">
            <img
              src="@/assets/img/box3-2x.jpg"
              class="card-img"
              alt="photo"
            >
            <div class="card-img-overlay gradient_box">
              <div class="container_img_text">
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
          <span class="avatar_name px-4">Brad Johnson</span>
          <span class="avatar_loco">Las Vegas</span>
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
    padding-bottom: 8rem;
  }

  .card {
    background-color: rgba(255, 255, 255, 0)!important;
    border: none;
    border-radius: 2px 2px 50px 2px;
    overflow: hidden;
    &:hover {
      transform: scale(1.1);
      transition: 1s;
    }
  }

  .container_img_text{
    position: absolute;
    bottom: 4px;
  }

  .card-text,
  .gold_icon {
    color: gold;
  }

  .motivational_text {
    font-size: 2rem;
    max-width: 750px;
    padding-top: 25rem;
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
    .avatar_name {
      color: rgb(255, 255, 255);
    }
    &:hover {
      cursor: pointer;
      transform: scale(1.2);
      transition: 1s;
      span {
        color: gold;
      }
    }
  }

  .avatar_loco{
    color: rgb(82, 82, 82);
  }

  .gradient_box{
  height: 100%;
  // eslint-disable-next-line
  background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgb(0, 0, 0),);
}
</style>
