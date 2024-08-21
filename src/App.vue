<!-- 메인 페이지 / 기본 -->

<template>
  <Header />
  <!-- <nav class="flex gap-10 mb-20">
    <router-link to="/">Home</router-link>
    <router-link to="/company">About</router-link>
    <router-link to="/notice">Notice</router-link>
    <router-link to="/service">Service</router-link>
  </nav> -->
  <main>
    <router-view />
  </main>
</template>

<script>
import Header from "@/components/layout/header.vue";
import "./styles/font.css";

export default {
  name: "App",

  components: {
    Header,
  },
};
</script>
