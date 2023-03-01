<template>
 <Home :data= card />
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'App',
  components :{
    Home,
   },
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
</style>
