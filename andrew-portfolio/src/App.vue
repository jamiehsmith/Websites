<template>
  <div id="portfolio">
    <div id="header">
      <a href="/">Andrew Sacher</a>
      <Nav />
    </div>
    <div id="profile">
      <img id="profile-pic" src="./assets/andrew.jpeg" />
      <span>Hey, I'm Andrew</span>
    </div>
  </div>
</template>

<script>
import Nav from "./components/Nav.vue";

export default {
  name: "Portfolio",
  components: {
    Nav,
  },
};
</script>

<style>
#header {
  display: flex;
  justify-content: space-between;
  padding: 50px;
}

a {
  text-decoration: none;
  color: #000;
}

#profile {
  display: flex;
  align-content: center;
}
#profile-pic {
  height: 600px;
  padding: 0px 50px;
}
</style>
