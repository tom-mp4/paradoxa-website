<script setup>
</script>

<template>
  <div class="reservations">
    <div class="tickets">
      <a href="" class="button">
        <div class="left">
          <div class="location">
            <p class="info-text">paris</p>
            <p class="address">Cinéma de l'Orient</p>
          </div>
          <p class="info-text">02.04.23</p>
        </div>
        <div class="right">
          <p class="info-text">reserver</p>
        </div>
      </a>
      <div class="line">
      </div>
      <a href="" class="button">
        <div class="left">
          <div class="location">
            <p class="info-text">bordeaux</p>
            <p class="address">Cinéma Utopia</p>
          </div>
          <p class="info-text">02.04.23</p>
        </div>
        <div class="right">
          <p class="info-text">reserver</p>
        </div>
      </a>
      <div class="line">
      </div>
      <a href="" class="button">
        <div class="left">
          <div class="location">
            <p class="info-text">bayonne</p>
            <p class="address">Cinéma l'Atalante</p>
          </div>
          <p class="info-text">02.04.23</p>
        </div>
        <div class="right">
          <p class="info-text">reserver</p>
        </div>
      </a>
      <div class="line">
      </div>
      <a href="" class="button">
        <div class="left">
          <div class="location">
            <p class="info-text">sjpp</p>
            <p class="address">Cinéma Le Vauban</p>
          </div>
          <p class="info-text">02.04.23</p>
        </div>
        <div class="right">
          <p class="info-text">reserver</p>
        </div>
      </a>
      <div class="line">
      </div>
      <a href="" class="button">
        <div class="left">
          <div class="location">
            <p class="info-text">toulouse</p>
            <p class="address">Cinéma Utopia</p>
          </div>
          <p class="info-text">02.04.23</p>
        </div>
        <div class="right">
          <p class="info-text">reserver</p>
        </div>
      </a>
    </div>
    <video autoplay controls class="trailer">
        <source src="@/assets/bande-annonce-low-colo.mp4" type="video/mp4">
    </video>
  </div>
</template>

<style lang="scss" scoped>
@use '@/assets/styles/_colors.scss';
@use '@/assets/styles/_fonts.scss';

.reservations {
  display: flex;
  justify-content: space-between;
  background: colors.$white;
  height: 95vh;

  .tickets {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 90%;

    .button {
      display: flex;
      justify-content: space-between;
      align-items: center;

      padding: 10px 0;

      text-decoration: none;
      width: 70%;

      .left {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 45%;
      }
    }
  }
}

.info-text {
  font-size: 28px;
  text-decoration: none;
  color: colors.$black;
  font-family: Montserrat, sans-serif;
  font-weight: 500;
  text-transform: uppercase;
}

.location {
  line-height: 22px;

  .address {
    color: colors.$black;
    font-family: Montserrat, sans-serif;
  }
}

</style>
