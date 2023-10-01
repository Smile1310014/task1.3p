<template>
  <div class="hello">
    <p1>Hlo Everybody, I am </p1>
    <h1>{{ msg }}</h1>
    <h5>Web/UX designer</h5>
    <p>
      <a href="#" class="router-link">
      <router-link to="/about">
        <div class="about-image">
        <img src="https://cdn3.vectorstock.com/i/1000x1000/69/17/about-me-button-vector-1296917.jpg" alt="About" class="elliptical-image" />
        </div>
      </router-link>
    </a>
    <a href="#" class="router-link">
        <router-link to="/project">
          <div class="project-image">
            <img src="https://www.clker.com/cliparts/n/k/M/B/n/L/project-button-hi.png" alt="Project" class="elliptical-image"/>
          </div>
        </router-link>
      </a>
      <a href="#" class="router-link">
        <router-link to="/home">
          <div class="home-image">
            <img src="https://img.freepik.com/premium-vector/home-icon-button-blue-glossy-with-shadow_514344-157.jpg" alt="Home" class="home-changes"/>
          </div>
        </router-link>
      </a>
      <router-view></router-view> <!-- This is where routed components will be displayed -->
    </p>
    <!-- <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.about-image {
  position: absolute;
  top: 400px;
  left:580px; /* This aligns the content (image) to the left */
}

.project-image {
  position: absolute;
  top: 400px;
  left: 820px;
}
.skills-image {
  position: absolute;
  top: 280px;
  left: 650px;
}
.skills-changes{
  width: 200px; /* Set the desired width */
  height: 190px; /* Set the desired height (increase this value) */
  clip-path: ellipse(49% 25% at 51% 48%); /* Create an elliptical clipping path */
  position: relative;
  top: -250px;
  left: 980px;
}

.home-image {
  position: relative;
  top: 155px;
  left: -1080px;
}
p1 {
  position: relative;
  top: 345px;
  left: 5px;
  font-size: 18px;
}
h1 {
  font-size: 40px;
  color: black;
  position: relative;
  top: 320px;
  left: 5px;
}

h5 {
  font-size: 22px;
  color: black;
  position: relative;
  top: 285px;
  left: 5px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.elliptical-image {
  width: 200px; /* Set the desired width */
  height: 190px; /* Set the desired height (increase this value) */
  clip-path: ellipse(49% 25% at 51% 44%); /* Create an elliptical clipping path */
  position: relative;
  top: -360px;
  left: 580px;
}

.home-changes {
  width: 200px; /* Set the desired width */
  height: 190px; /* Set the desired height (increase this value) */
  clip-path: ellipse(49% 25% at 51% 35%); /* Create an elliptical clipping path */
  position: relative;
  top: -350px;
  left: 580px;
}



</style>
