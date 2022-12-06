<template>
  <section class="playlist_video">
    <div class="image_container">
      <div class="image_box">
        <img
          class="img-fluid"
          src="@/assets/img/service15-2x.jpg"
          alt="photo"
        >
      </div>
      <div class="text_box">
        <h5>Tune up your workout</h5>
        <h1>The best health & fitness advice online</h1>
        <div class="logo_box d-flex">
          <img
            class="img-fluid"
            src="@/assets/img/unnamed.jpg"
            alt="logo"
          >
          <div class="logo_text">
            <div>ThemeFusion</div>
            <div class="yt_content d-flex">
              <div class="yt_text px-1">
                <i class="fa-brands fa-youtube me-2" />Youtube
              </div>
              <div class="yt_number">
                999+
              </div>
            </div>
          </div>
        </div>
        <!-- eslint-disable-next-line -->
        <p class="pt-4">Arcu eu facilisi un placerat nunc habitant. Magna semper mauris, venenatis, leo integer sit pellentesque</p>
        <div class="btn btn-danger btn_orange">
          <i class="fa-brands fa-youtube me-2" />Visit mi YouTube channel
        </div>
      </div>
    </div>
    <div class="playlist_ft container">
      <div class="text_playlist d-flex justify-content-between pb-4">
        <h5>Featured playlist</h5>
        <!-- eslint-disable-next-line -->
        <div><a href="#!"><strong> View all videos</strong><i class="fa-solid fa-chevron-right" /></a></div>
      </div>
      <div class="row row-cols-3">
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/video2-2x.jpg"
            alt=""
          >
          <div class="subtext_box text-center p-1">
            <h6>Thighs & glute workout</h6>
            <div class="text_img">
              Increase your mobility
            </div>
          </div>
        </div>
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/video7-2x.jpg"
            alt=""
          >
          <div class="subtext_box text-center p-1">
            <h6>Lift, firm & perk up</h6>
            <div class="text_img">
              Feel young again
            </div>
          </div>
        </div>
        <div class="col">
          <img
            class="img-fluid"
            src="@/assets/img/video9-2x.jpg"
            alt=""
          >
          <div class="subtext_box text-center p-1">
            <h6>Slim & trim your waist</h6>
            <div class="text_img">
              Shed those extra pounds
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionPage3',

};
</script>

<style lang="scss" scoped>
a {
  text-decoration: none;
  color: #000000;
}
.image_container{
  position: relative;
}
.image_box {
  position: absolute;
  top: -50px;
  width:600px;
  height:600px;
  img {
    border-radius: 2px 2px 50px 2px;
  }
}

.text_box {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-top: 5rem;
  margin-left: 50%;
  h5 {
    color: rgb(0, 102, 255);
  }
  h1 {
    font-size: 3rem;
  }
  img {
    width: 50px;
    height: 50px;
  }
}
.yt_content{
  .yt_text{
    color: rgb(255, 255, 255);
    background-color: rgb(250, 79, 0);
    border: 1px solid rgb(0, 0, 0);
  }
  .yt_number{
    color: rgb(0, 0, 0);
    background-color: rgb(255, 255, 255);
    border: 1px solid rgb(0, 0, 0);
  }
  .fa-youtube{
    color: rgb(255, 255, 255);
  }
  &:hover {
    cursor: pointer;
  }
}

.btn_orange {
  width: max-content;
  border-radius: 10rem;
  color: rgb(255, 255, 255);
  background-color: rgb(250, 79, 0);
}

.playlist_ft{
  margin-top: 18rem;
}

.text_img {
  color: rgb(0, 102, 255);
}

.col img {
    border-radius: 2px 2px 50px 2px;
    padding-bottom: .5em;
    &:hover {
      transform: scale(1.1);
    }
}

.row {
  margin-bottom: 5rem;
}

</style>
