<template>
  <div class="intrest-calculator">
    <h3>Calculate your interests</h3>
    <div class="container">
      <div class="content-section">
        <label for="payment-option">How often are you saving?</label>
        <select name="payment-option" id="payment-option">
          <option value="monthly">Monthly</option>
          <option value="weekly">Weekly</option>
          <option value="daily">Daily</option>
        </select>
        <label for="save-amount">How much are you saving?</label>
        <input type="number" id="save-amount" />
        <label for="saving-length">How long are you saving?(Months)</label>
        <input type="number" id="saving-length" />
      </div>
      <div class="image-section">
        <img v-bind:src="picture" alt="" />
      </div>
    </div>
  </div>
</template>
<script>
import image from "../../assets/frame.svg";
export default {
    name: "InterestCalculator",
  data() {
    return {
      picture: image,
    };
  },
};
</script>
<style scoped>
.intrest-calculator {
  color: white;
  background-color: #10001f;
  width: fit-content;
  padding: 2rem 3rem 0 2rem;
  border-radius: 20px;
}
.intrest-calculator input {
  display: block;
  background-color: transparent;
  color: white;
  border-bottom: 1px solid white;
  padding: 10px;
  font-size: 18px;
  outline: none;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  -webkit-appearance: none;
  appearance: none;
}
input[type="number"] {
  -moz-appearance: textfield;
}
.intrest-calculator select {
  background-color: transparent;
  color: white;
  padding: 10px;
  font-size: 18px;
  outline: none;
  border: 1px solid white;
  width: 100%;
  border-radius: 5px;
}
.intrest-calculator label {
  display: block;
  margin: 1rem;
}
.intrest-calculator .container {
  display: flex;
  align-content: center;
  gap: 1.5rem;
}
#payment-option {
  background-color: #10001f;
}
.image-section {
  width: 290px;
  height: 308px;
}
</style>
