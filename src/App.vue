<template>
  <Home :data="card" />
</template>

<script>
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Home,
  },
  data() {
    return {
      card: [
        "./src/assets/img1.jpg",
        "./src/assets/img2.jpg",
        "./src/assets/img3.jpg",
        "./src/assets/img4.jpg",
      ],
    };
  },
};
</script>

<style></style>
