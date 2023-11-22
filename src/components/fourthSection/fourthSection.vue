<template>
  <div class="fourth-sec">
    <div class="container">
      <FourthSecText />
    </div>
  </div>
</template>
<script>
import FourthSecText from "./textArea.vue";
export default {
  name: "FourthSec",
  components: {
    FourthSecText,
  },
};
</script>
<style scoped>
.fourth-sec {
  background-color: #FFFDF2;
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
