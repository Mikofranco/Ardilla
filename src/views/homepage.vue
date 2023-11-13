<template>
  <NavSection />
  <HeroInfo />
  <HeroImage />
</template>
<script>
import NavSection from "../components/navigations/navbar.vue";
import HeroInfo from "../components/herosection/infoSection.vue";
import HeroImage from "../components/herosection/heroSection.vue";

export default {
  components: {
    NavSection,
    HeroImage,
    HeroInfo,
  },
};
</script>
