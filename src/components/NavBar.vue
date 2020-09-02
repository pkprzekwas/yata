<template>
  <nav class="nav-bar">
    <h2 class="logo">
      YATA
    </h2>
    <h3 class="logo-text">
      Yet another TODO app
    </h3>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
  props: {},
};
</script>

<style scoped>
nav.nav-bar {
  background-color: #f5f5f5;
  border-bottom: 1px solid #dddddd;
  display: flex;
  justify-content: center;
}
nav.nav-bar h2.logo {
  margin-bottom: 12px;
  color: #FF1493;
  align-self: flex-end;
  font-size: 36px;
  font-weight: 900;
  font-style: italic;
}

nav.nav-bar h3.logo-text {
  margin: 0 0 12px 12px;
  align-self: flex-end;
  font-weight: 200;
  font-style: italic;
}
</style>
