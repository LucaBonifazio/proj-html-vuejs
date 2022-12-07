<template>
  <section class="trainer_sect">
    <div class="container gradient_box pt-5">
      <h3>
        Join our mailing today
      </h3>
      <h1>Insider offers & flash sales in your inbox every week</h1>
      <i class="fa-solid fa-chevron-up gold_icon" />
      <i class="fa-solid fa-chevron-up gold_icon" />
      <i class="fa-solid fa-chevron-up gold_icon" />
      <form @submit.prevent>
        <label for="mail">
          <input
            id="mail"
            v-model="email"
            type="email"
            class="form-control"
            placeholder="Insert your email...*"
          >
        </label>
        <button class="btn btn-primary px-5">
          Subscribe
        </button>
      </form>
      <!-- eslint-disable-next-line -->
        <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet, consectetur adipiscin elit sed porttitor lectus</p>
    </div>
    <div class="bg_black">
      <div class="container p-5">
        <!-- eslint-disable-next-line -->
          <div class="row row-cols-sm-1 row-cols-md-3 row-cols-lg-4 text-white text-center">
          <div class="col card_bb">
            <img
              class="img-fluid card_img"
              src="https://freesvg.org/img/Wrist-Watch-Line-Art.png"
              alt="watch"
            >
            <div class="subtext_box text-center px-1">
              <h5>Team training</h5>
              <h6>Find a partner</h6>
              <!-- eslint-disable-next-line -->
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid, hic fugiat? Totam, facere!</p>
              <a href="#!">Find a partner <i class="fa-solid fa-chevron-right" /></a>
            </div>
          </div>
          <div class="col card_bb">
            <img
              class="img-fluid card_img"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKQDlZf-U_nNr-PMfabecNyuajxqPSMExOz3P51A9iz8xsI0lHpVenYkF4YKQ4FfQM3Yg&usqp=CAU"
              alt="crossfit"
            >
            <div class="subtext_box text-center px-1">
              <h5>Crossfit workout</h5>
              <h6>Push your limits</h6>
              <!-- eslint-disable-next-line -->
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid, hic fugiat? Totam, facere!</p>
              <a href="#!">Learn about Corssfit <i class="fa-solid fa-chevron-right" /></a>
            </div>
          </div>
          <div class="col card_bb">
            <img
              class="img-fluid card_img"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/26/Pictograms-nps-land-exercise-fitness-2.svg/2048px-Pictograms-nps-land-exercise-fitness-2.svg.png"
              alt="fitness"
            >
            <div class="subtext_box text-center px-1">
              <h5>Weight loss plan</h5>
              <h6>Shed those pounds</h6>
              <!-- eslint-disable-next-line -->
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid, hic fugiat? Totam, facere!</p>
              <a href="#!">Schedule a workout <i class="fa-solid fa-chevron-right" /></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionPage4',
};
</script>

<style lang="scss" scoped>
 .trainer_sect{
    background-image: url('@/assets/img/banner1-2x.jpg');
    background-size: contain;
    background-repeat: no-repeat;
    .container{
      height: 500px;
    }
  }

  h3 {
    color: #ec5a57;
  }

  h1 {
    padding: 1rem 0;
    font-size: 3em;
    color: rgb(255, 255, 255);
    max-width: 750px;
  }

  .gold_icon {
    color: gold;
  }
  .btn {
    border-radius: 10em;
  }

  p {
    padding: 2rem 0;
    color: rgb(122, 122, 122);
    max-width: 700px;
  }

  .form-control{
    border-radius: 10rem;
    width: 500px;
    margin: 2rem 2rem 0 0;
  }

  .bg_black{
    background-color: rgb(0, 0, 0);
  }

  .row {
    display: flex;
    justify-content: space-between;
  }

  .card_bb{
    border: 2px solid rgb(0, 0, 255);
    padding: 1rem;
    &:hover {
      transform: scale(1.1);
      transition: 1s;
    }
    a {
      text-decoration: none;
      color: rgb(255, 255, 255)
    }
    h6 {
      color: gold;
    }
  }

  .card_img {
    width: 70px;
    height: 70px;
  }

  .gradient_box{
  height: 100%;
  // eslint-disable-next-line
  background-image: linear-gradient(to right, rgb(0, 0, 0),
  rgb(0, 0, 0),rgb(0, 0, 0),rgb(0, 0, 0),rgba(255, 255, 255, 0),
  rgba(255, 255, 255, 0),rgba(255, 255, 255, 0));
}
</style>
