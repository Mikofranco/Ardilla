<template>
  <div class="fourth-page-container">
    <h1 class="h1"><span class="h1-purple">Unlimited</span> Investment</h1>
    <br />
    <h1 class="h1">Opportunities</h1>
    <p class="message">
      Plan towards your future by investing with ardilla, Grow your money
      confidently and securely with the available investment oppurtuinities
    </p>
    <button>
      Invest with ardilla coming soon
      <span class="button-icon"><img v-bind:src="svg" alt="" /></span>
    </button>
  </div>
</template>
<script>
import pic from "../../assets/send.svg";
export default {
  name: "FourthSecText",
  data() {
    return {
      svg: pic,
    };
  },
};
</script>
<style scoped>
.fourth-page-container {
  background-color: #fffdf2;
}
.h1 {
  color: var(--teal-600, #0d9488);
  font-family: Cabinet Grotesk;
  font-size: 80px;
  font-style: normal;
  font-weight: 800;
  line-height: 100px;
}
.h1-purple {
  color: #3d0072;
}
.fourth-page-container .message {
  color: #3d0072;
  font-family: Cabinet Grotesk;
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 50px; /* 208.333% */
}
.fourth-page-container button{
    padding:1rem;
    font-size: 18px;
    border-radius: 15px;
}
.button-icon {
  background-color: #3d0072;
}
</style>
