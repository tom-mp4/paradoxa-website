<script setup>
// eslint-disable-next-line import/no-extraneous-dependencies
import MarqueeText from 'vue-marquee-text-component';
</script>

<template>
  <marquee-text class="scrolling-text" :repeat="20" :duration="30">
    PARIS 20.04 - BAYONNE 02.06 - BORDEAUX 29.03 - SJPP 12.04 -&nbsp;
  </marquee-text>
</template>

<style lang="scss" scoped>
@use '@/assets/styles/_colors.scss';
@use '@/assets/styles/_fonts.scss';

.scrolling-text {
  z-index: 1;

  background: colors.$red;
  padding: 25px 0;

  color: colors.$white;
  font-family: fonts.$Mattone;
  font-size: 38px;
}

</style>
