<template>
  <div class="left-content">
    <h1>We're Keen On <span>Transparency</span></h1>
    <p>calculate your interest per time you save on our platform.</p>
    <button>Get started</button>
  </div>
</template>

<script>
export default {
    name:"InfoSection",

};
</script>
<style scoped>
.left-content h1 {
  /* text-align: center; */
  color: #3d0072;
  font-family: Cabinet Grotesk;
  font-size: 80px;
  font-style: normal;
  font-weight: 800;
  line-height: 80px;
}
.left-content span {
  color: #e8356d;
}
.left-content p {
  /* text-align: center; */
  color: #3d0072;
  font-family: Cabinet Grotesk;
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: 40px; /* 222.222% */
}
.left-content button {
  margin: auto;
  background-color: #8807f7;
  border: none;
  padding: 10px 20px;
  color: white;
  cursor: pointer;
  border-radius: 25px;
}
</style>
