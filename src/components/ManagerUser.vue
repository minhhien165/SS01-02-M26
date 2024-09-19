<template>
  <div>
    <table>
      <thead>
        <tr>
          <th>STT</th>
          <th>Họ và tên</th>
          <th>Ngày sinh</th>
          <th>Giới tính</th>
          <th>Địa chỉ</th>
          <th>Hành động</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Mark Rober</td>
          <td>12/09/1970</td>
          <td>Nam</td>
          <td>New York</td>
          <td>
            <Delete></Delete>
            <Update></Update>
          </td>
        </tr>
        <tr>
          <td>2</td>
          <td>Lili</td>
          <td>26/05/1989</td>
          <td>Nữ</td>
          <td>London</td>
          <td>
            <Delete></Delete>
            <Update></Update>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script setup>
import Delete from "./bt09/btnDelete.vue";
import Update from "./bt09/btnUpdate.vue";
</script>

<style scoped>
table {
  border-collapse: collapse;
  width: 100%;
}
th,
td {
  border: 1px solid #ddd;
  padding: 8px;
  text-align: left;
}

th {
  background-color: #f2f2f2;
}
</style>
