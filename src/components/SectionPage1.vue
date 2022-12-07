<template>
  <section
    id="start_app"
    class="intro_sect"
  >
    <div class="container py-5 gradient_box">
      <h3>
        Certified fitness professional
      </h3>
      <h1>Take control of your health</h1>
      <i class="fa-solid fa-chevron-up gold_icon" />
      <i class="fa-solid fa-chevron-up gold_icon" />
      <i class="fa-solid fa-chevron-up gold_icon" />
      <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet</p>
      <div class="btn btn-primary p-3 px-4 me-4">
        <i class="fa-brands fa-youtube me-2" />Visit my YouTube channel
      </div>
      <div class="btn btn-dark btn_black p-3 px-4">
        Buy Avada today<i class="fa-solid fa-arrow-right mx-2" />
      </div>
    </div>
    <i class="fa-solid fa-play" />
    <div class="sq_folder">
      <i class="fa-solid fa-id-card-clip" />
      <div><strong>Demos</strong></div>
    </div>
    <div class="sq_sale">
      <div class="price_sale">
        $ 39
      </div>
      <div>
        <strong>On Sale</strong>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionPage1',
};
</script>

<style scoped lang="scss">
  .intro_sect{
    height: 500px;
    background-image: url('@/assets/img/slider82x-scaled.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    position: relative;
  }

  h3 {
    color: #ec5a57;
  }

  h1 {
    padding: 1rem 0;
    font-size: 3em;
    color: rgb(255, 255, 255);
  }

  .gold_icon {
    color: gold;
  }
  .btn {
    border-radius: 10em;
  }
  .btn_black{
    background-color: black;
  }

  p {
    padding: 2rem 0;
    color: rgb(122, 122, 122);
  }

  .fa-play{
    position: absolute;
    top: 30%;
    right: 20%;
  }

  .gradient_box{
  height: 100%;
  // eslint-disable-next-line
  background-image: linear-gradient(to right, rgb(0, 0, 0),
  rgb(0, 0, 0),rgb(0, 0, 0),rgb(0, 0, 0),rgba(255, 255, 255, 0),
  rgba(255, 255, 255, 0),rgba(255, 255, 255, 0));
}

  .sq_folder,
  .sq_sale{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 2rem;
    color: rgb(1, 70, 136);
    background-color: rgb(255, 255, 255);
    width: 50px;
    height: 50px;
    border-radius: 5px;
    i {
      font-size: 30px;
    }
    &:hover {
      cursor: pointer;
      background-color: rgb(127, 246, 255);
    }
  }

  .sq_folder {
    position: absolute;
    top: 50px;
    right: 15px;
  }
  .sq_sale {
    position: absolute;
    top: 120px;
    right: 15px;
    white-space: nowrap;
    .price_sale{
      color: rgb(0, 194, 0);
      font-size: large;
    }
  }
</style>
