<template>
  <div class="container">
    <div v-for="item in data">
      <img :src="item" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  props: {
    data: Array,
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
