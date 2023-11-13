<template>
  <div class="info-section">
    <h1 class="gradient-text">Your Access To More</h1>
    <p>
      Ardilla helps you save and invest in achieving your financial goals, we
      have the most flexible and seamless way to grow your funds.
    </p>
    <button>Get Started</button>
  </div>
</template>

<script>
export default {
  name: "HeroInfo",
};
</script>
<style scoped>
.info-section {
  text-align: center;
  color: white;
  width: 70%;
  margin: auto;
}
.info-section .gradient-text {
  font-family: Cabinet Grotesk;
  font-size: 95px;
  font-style: normal;
  font-weight: 800;
  background-image: linear-gradient(
    92deg,
    #ffeb35 7.5%,
    rgba(25, 253, 130, 0.99) 107.24%
  );
  background-color: #ffeb35;
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.info-section p {
  width: 50%;
  margin: auto;
  font-size: 18px;
}
.info-section button {
  margin-top: 2rem;
  color: black;
  padding: 1rem 3rem;
  background-color: #ffffff;
  border-radius: 20px;
}
.info-section button:hover {
  background-color: #8807f7;
}
</style>
