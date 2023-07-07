<script setup>
</script>

<template>
  <div class="canva">
    <div class="card">

    </div>
  </div>
</template>

<style scoped lang="scss">
@use '@/assets/styles/_colors.scss';
@use '@/assets/styles/_fonts.scss';

.canva {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 40vh;
  width: 90%;
  background-color: colors.$white;

  .card {
    height: 40%;
    width: 50vw;
    background-color: colors.$red;
  }
}

</style>
