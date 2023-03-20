<script setup>
</script>

<template>
  <div class="landing">
    <video class="background-video" autoplay loop muted>
      <source src="@/assets/background.mp4" type="video/mp4">
    </video>
    <div class="cta">
      <h1 class="title">PARADOXA</h1>
      <div class="additional-information">
        <p>ENNIO BERNEAU</p>
        <p>UN FILM DE TOM MARTIN</p>
        <p>GHJULIA VAN MUYLDERS</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '@/assets/styles/_colors.scss';
@use '@/assets/styles/_fonts.scss';

.landing {
  height: 100vh;

  .background-video {
    height: 100vh;
    width: 100vw;
    object-fit: cover;
    position: fixed;
    z-index: -1;
  }

  .cta {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;

    .title {
      font-family: fonts.$Mason;
      font-weight: bold;
      font-size: 15vw;
      line-height: 17vw;
      color: colors.$red;
    }

    .additional-information {
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      width: 75%;

      p {
        text-align: center;
        font-family: fonts.$Mattone;
        font-size: 1.1rem;
        font-weight: bold;
        color: colors.$white;
      }
    }
  }
}

</style>
