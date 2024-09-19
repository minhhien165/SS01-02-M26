<script setup>
import listCourseVue from "./components/listCourse.vue";
import ColorBox from "./components/ColorBox.vue";
import CardVueVue from "./components/CardVue.vue";
import Caculation from "./components/Caculation.vue";
import UserInfo from "./components/UserInfo.vue";
import FormatName from "./components/FormatName.vue";
import AdminIndex from "./components/AdminIndex.vue";
import UserLayout from "./components/UserLayout.vue";
import ManagerUser from "./components/ManagerUser.vue";
import TodolistIndex from "./components/TodolistIndex.vue";
</script>

<template>
  <div>
    <listCourseVue></listCourseVue>
    <div class="boxs">
      <ColorBox color="red" />
      <ColorBox color="blue" />
      <ColorBox color="green" />
    </div>
    <CardVueVue></CardVueVue>
    <Caculation></Caculation>
    <UserInfo></UserInfo>
    <FormatName></FormatName>
    <AdminIndex></AdminIndex>
    <br />
    <UserLayout></UserLayout>
    <br />
    <ManagerUser></ManagerUser>
    <br />
    <TodolistIndex></TodolistIndex>
  </div>
</template>

<style scoped>
.boxs {
  display: flex;
  flex-direction: row;
  gap: 20px;
}
</style>
