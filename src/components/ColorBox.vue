<template>
  <div :class="boxColor" class="box"></div>
</template>

<script setup>
const props = defineProps({
  color: {
    type: String,
    required: true,
    validator: (value) => ["red", "blue", "green"].includes(value),
  },
});

const boxColor = props.color;
</script>

<style scoped>
.box {
  width: 200px;
  height: 200px;
}
.red {
  background-color: red;
}
.blue {
  background-color: blue;
}
.green {
  background-color: green;
}
</style>
