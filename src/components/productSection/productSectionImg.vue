<template>
  <div>
    <img v-bind:src="picture" alt="" />
  </div>
</template>
<script>
import pic from "../../assets/right.svg";
export default {
  name: "ProductImg",
  data() {
    return {
      picture: pic,
    };
  },
};
</script>
