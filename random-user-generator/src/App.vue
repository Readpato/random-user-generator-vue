<script>
import MainContent from "./components/MainContent.vue";

export default {
  components: {
    MainContent,
  },
};
</script>

<template>
  <div class="container">
    <MainContent />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Poppins", sans-serif;
  min-height: 100vh;
  width: 100%;
}

.container {
  width: 80%;
  height: auto;
  margin: 0 auto;
  display: block;
  border: 2px solid red;
}
</style>
