<template>
  <div class="hero-wrap">
    <img v-bind:src="heroImage" alt="" />
  </div>
</template>
<script>
import pic from "../../assets/phone.svg";
export default {
  name: "HeroImage",
  data() {
    return {
      heroImage: pic,
    };
  },
};
</script>
<style scoped>
.hero-wrap{
    width: fit-content;
    margin: auto;
}
</style>
