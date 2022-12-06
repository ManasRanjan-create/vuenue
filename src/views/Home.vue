<template>
  <div class="about">
    <HomeCarousel />
    <HomeContent />
  </div>
</template>
<script>
import HomeCarousel from "../components/HomeComponents/HomeCarousel.vue";
import HomeContent from "../components/HomeComponents/HomeContent.vue";
export default {
  name: "Home",
  components: {
    HomeCarousel,
    HomeContent,
  },
};
</script>
<style lang="">
</style>