<template>
  <div class="product-lst">
    <BulletPoint class="bullet" />
    <p>{{ productLstText }}</p>
  </div>
</template>
<script>
import BulletPoint from "./bulletImg.vue";
export default {
  name: "ProductList",
  props: {
    productLstText: String,
  },
  components: {
    BulletPoint,
  },
};
</script>
<style scoped>
.product-lst{
    display: flex;
    align-items: center;
    gap: 3rem;
    margin-bottom: 1.5rem;
}
</style>
