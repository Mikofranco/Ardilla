<template>
  <div class="option">
    <button class="custom-button">
      Product <img v-bind:src="arrow" alt="" />
    </button>
    <button class="custom-button">Business <span>Beta</span></button>
    <button class="custom-button">
      Company <img v-bind:src="arrow" alt="" />
    </button>
    <button class="custom-button">Learn</button>
  </div>
</template>

<script>
import arrowDown from "../../assets/gridicons_dropdown.svg";
export default {
  name: "OptionSection",
  data() {
    return {
      arrow: arrowDown,
    };
  },
};
</script>

<style scoped>
.option{
  font-size: 20px;
}
.custom-button {
  background-color: transparent;
  border: none;
  padding: 10px 20px;
  color: white;
  cursor: pointer;
  display: flex;
}

.button-image {
  margin-right: 10px;
}

.extra-text {
  font-size: 14px;
  margin-left: 10px;
}
span {
  border: 1px solid white;
  border-radius: 5px;
  margin-left: 3px;
}
div {
  display: flex;
  justify-content: center;
}
</style>
