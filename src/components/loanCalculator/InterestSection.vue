<template>
  <div class="container">
    <InfoSection />
    <IntrestCalculator />
  </div>
</template>
<script>
import InfoSection from "./infoSection.vue";
import IntrestCalculator from "./calculator.vue";
export default {
  name: "InterestSection",
  components: {
    InfoSection,
    IntrestCalculator,
  },
};
</script>
<style scoped>
.container{
    display: flex;
    gap: 2rem;
    align-items: center;
    padding: 8rem 14rem;
    background-color: white;
}
</style>
