<template>
  <div class="interest-calc">
    <div class="container">
      <h2>Calculate your interest</h2>
      <label for="plan">How often are you saving?</label>
      <select name="plan" id="plan">
        <option value="monthly">Monthly</option>
        <option value="weekly">Weekly</option>
      </select>
      <label for="amount">How much are you saving?</label>
      <input type="number" required id="amount">
      <label for="time">How long are you saving in </label>
      <input type="number" required id="time">
    </div>
  </div>
</template>
<script>
export default {
  name: "InterestCalc",
};
</script>
<style scoped>
.interest-calc{
    background-color: black;
    width: 80%;

}
.interest-calc input, label{
    display: block;
}

</style>
