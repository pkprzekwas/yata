<template>
  <div class="container">
    <nav-bar class="navbar" />
    <side-bar class="sidebar" />
    <main-page class="mainpage" />
  </div>
</template>
<script>
import SideBar from "./SideBar.vue";
import NavBar from "./NavBar.vue";
import MainPage from "./MainPage.vue";

export default {
  name: "PageLayout",
  components: {
    SideBar,
    NavBar,
    MainPage,
  },
};
</script>
<style scoped>
.navbar {
    grid-area: navbar;
    margin-top: 0;
}

.sidebar {
    grid-area: sidebar;
}

.mainpage {
    grid-area: mainpage;
}

.container {
  display: grid;
  grid-template-columns: 2fr 10fr;
  grid-template-rows: 70px auto;
  grid-template-areas: 
   "navbar  navbar  navbar"
   "sidebar mainpage mainpage";
  width: 100vw;
  height: 100vh;
}
</style>