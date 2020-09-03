<template>
  <div class="main-page">
    <h1>Welcome ICECI</h1>
    <img width="800px" height="375px" src="./../assets/logo.png" />
  </div>
</template>
<script>
export default {
  name: "MainPage",
};
</script>
<style scoped>
div.main-page {
  background-color: #ffffff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

div.main-page h1 {
  color: #FF1493;
  margin-bottom: 150px;
}
</style>
