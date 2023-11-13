<template>
  <nav>
    <div>
      <img v-bind:src="logo" alt="" />
    </div>
    <Navbuttons></Navbuttons>
    <LoginSection />
  </nav>
</template>

<script>
import Navbuttons from "./options.vue";
import LoginSection from "./login.vue";
import pic from "../../assets/logo.svg";

export default {
  name: "NavSection",
  components: {
    Navbuttons,
    LoginSection,
  },
  data() {
    return {
      logo: pic,
    };
  },
};
</script>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  align-content: center;
  padding: 2rem;
}
</style>
