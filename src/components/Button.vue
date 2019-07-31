<template>
  <button class="button">
    {{ text }}
  </button>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      default: "button text"
    }
  }
};
</script>

<style scoped>
.button {
  display: inline-block;
  padding: 4px 8px;
  color: black;
  text-transform: uppercase;
  text-align: center;
  background-color: white;
  border: 1px solid black;
  border-radius: 4px;
}
.button:active {
  color: white;
  background-color: black;
}
</style>
