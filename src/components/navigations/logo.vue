<template>
  <img v-bind:src="logo_image" alt="logo" />
</template>
<script>
import image from "../../assets/logo.svg";
export default {
  name: "LogoSection",
  data() {
    return {
      logo_image: image,
    };
  },
};
</script>

<style scoped></style>
