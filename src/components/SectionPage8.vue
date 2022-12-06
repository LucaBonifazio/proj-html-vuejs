<template>
  <section class="motivational_sect text-white">
    <div class="gradient_box">
      <div class="container text-center">
        <i class="fa-solid fa-play" />
        <h1>Crossfit workout of the day</h1>
        <h4 style="color:gold">
          November 15th, 2019
        </h4>
        <a href="#!">View all videos <i class="fa-solid fa-arrow-right" /></a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionPage8',

};
</script>

<style lang="scss" scoped>
.motivational_sect{
  height: 500px;
  background-image: url('@/assets/img/banner14-2x.jpg');
  background-size: cover;
  background-repeat: no-repeat;
}

.container{
  margin: 0 auto;
  width: 100%;
  max-width: 900px;
  padding: 11rem;
}

a{
  text-decoration: none;
  color: rgb(255, 255, 255);
}

.gradient_box{
  height: 100%;
  // eslint-disable-next-line
  background-image: linear-gradient(to bottom right, rgba(21, 6, 240, 0.459),
  rgba(102, 2, 2, 0.74));
}
</style>
