<template>
  <div id="app">
    <div class="container">
    <img alt="Background image" src="./assets/back.jpg" class ="background-image" />
    </div>
    <div class = "photo">
    <img alt="Profile Photo" src="./assets/ME.jpg"  width = "750" height = "790" class = "crop">
    </div>
    <HelloWorld msg="Prabhjit Singh"/> <!-- Keep the HelloWorld component -->
    <div :class="{ 'about-highlight': $route.path === '/about' }">
      <AboutMe />
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
};
</script>
<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


.crop {
border-radius: 50%;
object-fit: cover;

}
.container {
  position: relative; /* Make sure the container has a positioning context */
  top: -85px;
  left: 0px;

}

.background-image {
  position: absolute;
  top: 0;
  left: 0;
  z-index: -1; /* Send the image to the back by setting a lower z-index */
  /* Other styles for the image (e.g., width, height) */
}


.about-highlight {
  background-color: #f0f0f0; /* Background color for the highlighted section */
  padding: 20px; /* Padding for spacing */
  border: 1px solid #ccc; /* Border for styling */
}

.photo {
  position: absolute;
  top: 450px;
  left:340px;
}
</style>
