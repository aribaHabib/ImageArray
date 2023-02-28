<template>
  <div class="container">
    <div v-for="item in card">
      <img v-bind:src="item" />
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      card: [
        "./src/assets/pexels-julius-silver-753325.jpg",
        "./src/assets/pexels-julius-silver-753337.jpg",
        "./src/assets/pexels-julius-silver-753626.jpg",
        "./src/assets/pexels-julius-silver-870711.jpg",
      ],
    };
  },
};
</script>

<style>
html {
  background: black;
  overflow: hidden;
}
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 1rem;
  width: 100vw;
  height: 100vh;
}
img {
  width: 300px;
}
</style>
