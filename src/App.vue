<script setup>
import Menu from "./Component/Menu.vue";
</script>

<template>
  <Menu />
  <section class="section1">
    <div class="tag">
      <h4 class="tag-title">Volunteer Organization</h4>
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
  background-color: rgba(45, 138, 112, 0.7);
  background-image: url("img/children.png");
  background-size: cover;
  background-position: center;
  background-blend-mode: multiply;
  padding: 12rem 2rem;
}
.tag {
  border: 1px solid var(--color-accent);
  width: 18rem;
  padding: 1rem;
  margin-bottom: 1rem;
  border-radius: 12px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--color-white);
}
.tag .tag-title {
  color: var(--primary-color);
  font-size: 14px;
  font-weight: 600;
  margin: 0;
  text-transform: uppercase;
}
.title-headings {
  font-size: 64px;
  color: var(--color-white);
  margin: 0;
  margin-bottom: 1rem;
}
.text-heading {
  font-size: 18px;
  color: var(--color-white);
  max-width: 600px;
  margin-bottom: 2rem;
}
.btn-action {
  display: flex;
  gap: 20px;
}
.btn-act {
  padding: 12px 24px;
  background-color: var(--primary-color);
  color: var(--color-white);
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-weight: 600;
  transition: background-color 0.3s ease;
}
.btn-act:hover {
  background-color: #1f6b52;
}
.btn1 {
  padding: 12px 24px;
  background-color: transparent;
  color: var(--color-white);
  border: 2px solid var(--color-white);
  border-radius: 5px;
  cursor: pointer;
  font-weight: 600;
  transition:
    background-color 0.3s ease,
    color 0.3s ease;
}
.btn1:hover {
  background-color: var(--color-white);
  color: var(--primary-color);
}
</style>
