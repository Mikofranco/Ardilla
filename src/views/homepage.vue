<template>
  <NavSection />
  <HeroInfo />
  <HeroImage />
  <ProductSection
    productHeader="Save"
    productDescription="Save at your own pace!"
    productContent="Save your money daily, weekly, or monthly. No pressure. We work at your pace"
  />
  <interest-section/>
  <ForthSec />
  
</template>
<script>
import NavSection from "../components/navigations/navbar.vue";
import HeroInfo from "../components/herosection/infoSection.vue";
import HeroImage from "../components/herosection/heroSection.vue";
import ProductSection from "../components/productSection/productSection.vue";
import ForthSec from "../components/fourthSection/fourthSection.vue";
import InterestSection from '@/components/loanCalculator/InterestSection.vue';

export default {
  components: {
    NavSection,
    HeroImage,
    HeroInfo,
    ProductSection,
    ForthSec,
    InterestSection,
  },
};
</script>
