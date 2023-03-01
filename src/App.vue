<template>
  <div class="container">
    <div v-for="item in card">
      <img :src="item" />
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
        "./src/assets/pexels-julius-silver-870711.jpg",
        "./src/assets/pexels-julius-silver-753626.jpg",
      ],
    };
  },
};
</script>

<style>
* {
   margin: 0;
 padding: 0;
}
html {
  background: black;
  overflow: hidden;
  overflow-y: auto;

}
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 1rem;
  width: 100%;
  min-height: 100vh;
  
}
img {
  width: 300px; 
  padding: 10px 0 10px 0;
}
</style>
