<template>
  <div class="home-page">
    <TheHeader/>
    <Hero/>
    <Credibility/>
  </div>
</template>

<script>
import TheHeader from '~/components/TheHeader.vue';
import Hero from '~/components/Hero.vue';
import Credibility from '~/components/Credibility.vue';
export default {
  name: 'HomePage',
  components: {
    TheHeader,
    Hero,
    Credibility
  }
}
</script>

<style>

</style>
