<template>
  <div>
    <img v-bind:src="picture" alt="" />
  </div>
</template>
<script>
import pic from "../../assets/Vector.svg";
export default {
    name: "BulletPoint",
  data() {
    return {
      picture: pic,
    };
  },
};
</script>
