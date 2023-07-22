<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import Card from "./components/Card.vue";
</script>

<template>
  <div>
    <a class="inline-block" href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a class="inline-block" href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
  <Card />

  <section>
    <div class="waffle">1</div>
    <div class="waffle">2</div>
    <div class="waffle">3</div>
    <div class="waffle">4</div>
    <div class="waffle">5</div>
    <div class="waffle">6</div>
    <div class="waffle">7</div>
    <div class="waffle">8</div>
    <div class="waffle">9</div>
  </section>
  <div class="image"></div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

section {
  height: 100%;
}

.waffle {
  border: 1px solid salmon;
  box-sizing: border-box;
  lost-waffle: 1/3;
}
</style>
