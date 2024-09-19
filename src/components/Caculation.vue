<template>
  <div>
    <h2>Danh sách kết quả</h2>

    <div>
      <p>Kết quả cộng: {{ add(number1, number2) }}</p>
      <p>Kết quả trừ: {{ subtract(number1, number2) }}</p>
      <p>Kết quả nhân: {{ multiply(number1, number2) }}</p>
      <p>Kết quả chia: {{ divide(number1, number2) }}</p>
    </div>
  </div>
</template>

<script setup>
let number1 = 10;
let number2 = 10;

// Hàm cộng
const add = (a, b) => a + b;

// Hàm trừ
const subtract = (a, b) => a - b;

// Hàm nhân
const multiply = (a, b) => a * b;

// Hàm chia
const divide = (a, b) => (b !== 0 ? a / b : "Không thể chia cho 0");
</script>

<style scoped>
div {
  margin-bottom: 10px;
}

input {
  margin-left: 10px;
}
</style>
