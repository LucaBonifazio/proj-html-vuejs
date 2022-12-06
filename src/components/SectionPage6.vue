<template>
  <section class="motivational_sect text-white">
    <div class="container text-center">
      <h1>"I've failed over and over again in my life. And tha is why I succeed."</h1>
      <i class="fa-solid fa-chevron-up gold_icon" />
      <i class="fa-solid fa-chevron-up gold_icon" />
      <i class="fa-solid fa-chevron-up gold_icon" />
      <!-- eslint-disable-next-line -->
      <p>Curabitur non nulla sit amet nisl tempus convallis quis ac lectus dolor sit amet, consectetur adipiscin elit sed porttitor lectus</p>
      <div class="btn btn-primary px-5">
        Buy Avada today <i class="fa-solid fa-chevron-right" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionPage6',

};
</script>

<style lang="scss" scoped>
.motivational_sect{
  height: 500px;
  background-image: url('@/assets/img/banner2-2x.jpg');
  background-size: cover;
  background-repeat: no-repeat;
}

.container{
  margin: 0 auto;
  width: 100%;
  max-width: 900px;
  padding: 7rem;
}

.gold_icon {
  color: gold;
}

.btn-primary{
  border-radius: 10rem;
}
</style>
