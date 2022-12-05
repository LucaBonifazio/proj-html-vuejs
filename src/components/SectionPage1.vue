<template>
  <section class="intro_sect">
    <div class="container py-5">
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
      <div class="btn btn-dark p-3 px-4">
        Buy Avada today<i class="fa-solid fa-arrow-right mx-2" />
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

  p {
    padding: 2rem 0;
    color: rgb(122, 122, 122);
  }

</style>
