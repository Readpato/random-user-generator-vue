<script>
export default {
  name: "UserDescription",
  data() {
    return {
      firstName: "Patrick",
      lastName: "Raedler",
      location: "Florence",
      email: "patoraedler@gmail.com",
    };
  },
};
</script>

<template>
  <div class="user-description">
    <img src="/" :alt="`Image of ${firstName} ${lastName}`" />
    <h2>{{ firstName }} {{ lastName }}</h2>
    <p>{{ location }}</p>
    <p>{{ email }}</p>
  </div>
</template>

<style scoped></style>
