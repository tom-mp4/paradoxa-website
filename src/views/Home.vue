<template>
  <div class="home">
    <Landing />
    <Marquee />
    <Tickets />
    <Card />
  </div>
</template>

<script>
// @ is an alias to /src
import Landing from '@/components/Home/Landing.vue';
import Marquee from '@/components/Home/Marquee.vue';
import Tickets from '@/components/Home/Tickets.vue';
import Card from '@/components/Home/Card.vue';

export default {
  name: 'Home',
  components: {
    Landing,
    Marquee,
    Tickets,
    Card,
  },
};
</script>
