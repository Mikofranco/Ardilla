<template>
  <div class="product-section">
    <div class="product-container">
      <h1 class="product-header">Product</h1>
      <div class="content">
        <div>
          <div class="content-element">
            <h3>{{ productHeader }}</h3>
            <p class="description">{{ productDescription }}</p>
            <p class="content">{{ productContent }}</p>
          </div>
          <ProductList productLstText="Create Unlimted savings plans" />
          <ProductList productLstText="Withdraw anytime" />
          <ProductList productLstText="Save with Friends with SAN ID" />
          <ProductList productLstText="Be better at saving" />
          <ProductList productLstText="Accountability profile" />
          <ProductList productLstText="Activity and report" />
        </div>
        <ProductImg />
      </div>
    </div>
  </div>
</template>
<script>
import ProductList from "./productList.vue";
import ProductImg from "./productSectionImg.vue";
export default {
  name: "ProductSection",
  props: {
    productHeader: String,
    productDescription: String,
    productContent: String,
  },
  components: {
    ProductList,
    ProductImg,
  },
};
</script>
<style scoped>
.product-section {
  background-color: #fffdf2;
  color: #3d0072;
  padding: 7rem 6rem;
  border-radius: 3rem 3rem 0 0;
}
.product-header {
  font-family: Cabinet Grotesk;
  font-size: 80px;
  font-style: normal;
  font-weight: 800;
  line-height: 110px;
  margin-left: 12rem;
}
.content {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 3rem;
}
.content-element h3 {
  color: var(--Secondary-color, #e8356d);
  font-family: Cabinet Grotesk;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
  line-height: 60px;
}
.content-element .description {
  font-family: Cabinet Grotesk;
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 40px;
}
.content-element .content {
  color: #9ca3af;
  font-family: Cabinet Grotesk;
  font-size: 18px;
  font-style: normal;
  font-weight: 700;
  line-height: 30px;
  margin-bottom: 1.5rem;
}
</style>
