<template>
  <div>
    <div class="card">
      <div class="image-placeholder">Image</div>
      <div class="title">Title</div>
      <button class="add-to-cart">Add to cart</button>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.card {
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  width: 300px;
  text-align: center;
}
.image-placeholder {
  background-color: #c0c0c0;
  height: 200px;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}
.title {
  margin: 15px 0;
  font-size: 24px;
  font-weight: bold;
}
.add-to-cart {
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  cursor: pointer;
  margin-bottom: 15px;
  transition: background-color 0.3s;
}
.add-to-cart:hover {
  background-color: #0056b3;
}
</style>
