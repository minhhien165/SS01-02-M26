<template>
  <div>
    <h1>Thông tin cá nhân</h1>
    <ul>
      <li>Họ và tên: {{ user.name }}</li>
      <li>Giới tính: {{ user.gental }}</li>
      <li>Ngày sinh: {{ user.date }}</li>
      <li>Email: {{ user.email }}</li>
      <li>Địa chỉ: {{ user.address }}</li>
    </ul>
  </div>
</template>

<script setup>
const user = {
  name: "Nguyễn Minh Hiển",
  gental: "Nam",
  date: "01/06/2005",
  email: "nmh@gmail.com",
  address: "Hà Đông, Hà Nội",
};
</script>

<style scoped></style>
