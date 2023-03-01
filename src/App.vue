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
        "/img/img1.jpg",
        "/img/img2.jpg",
        "/img/img3.jpg",
        "/img/img4.jpg",
      ],
    };
  },
};
</script>

<style></style>
