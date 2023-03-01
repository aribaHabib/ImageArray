<template>
  <Home :data="card" />
</template>

<script>
import Home from "./components/Home.vue";
import img1 from "./assets/img1.jpg";
import img2 from "./assets/img2.jpg";
import img3 from "./assets/img3.jpg";
import img4 from "./assets/img4.jpg";

export default {
  name: "App",
  components: {
    Home,
  },
  data() {
    return {
      card: [img1, img2, img3, img4],
    };
  },
};
</script>

<style></style>
