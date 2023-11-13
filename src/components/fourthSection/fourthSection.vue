<template>
  <div class="fourth-sec">
    <div class="container">
      <FourthSecText />
      <InterestCalc />
    </div>
  </div>
</template>
<script>
import FourthSecText from "./textArea.vue";
import InterestCalc from "./interestCalculator.vue";
export default {
  name: "FourthSec",
  components: {
    FourthSecText,
    InterestCalc,
  },
};
</script>
<style scoped>
.fourth-sec {
  background-color: white;
}
.fourth-sec .container {
  display: flex;
  justify-content: center;
  width: fit-content;
  gap: 2rem;
  padding: 6rem;
  /* background-color: white; */
}
</style>
