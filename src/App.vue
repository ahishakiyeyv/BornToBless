<script setup>
import Menu from "./Component/Menu.vue";
</script>

<template>
  <Menu />
  <section class="section1">
    <div class="tag">
      <h1 class="tag-title">Volunteer Organization</h1>
    </div>
    <h1 class="title-headings">Born To Bless</h1>
    <p class="text-heading">
      A volunteer organization dedicated to bringing healthcare support and educational resources to
      underserved communities across Burundi.
    </p>
    <div class="btn-action">
      <button class="btn-act">Get Involved</button>
      <button class="btn1">Our Mission</button>
    </div>
  </section>
</template>

<style scoped>
.section1 {
  height: 100vh;
  background-color: rgba(45, 138, 112, 07);
  background-image: url("img/children.png");
  background-size: cover;
  background-position: center;
  background-blend-mode: multiply;
}
</style>
