<template>
  <div class="home">
    <img
      class="home__background"
      src="@/assets/background.png"
      alt="background"
    />
    <div class="content-container">
      <Navigation />
      <Content />
    </div>
  </div>
</template>

<script>
import Navigation from "./Navigation.vue";
import Content from "./Content.vue";
export default {
  name: "Home",
  components: {
    Navigation,
    Content,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.home {
  width: 100%;
  height: 100vh;
  position: relative;
}

.home__background {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.content-container {
  width: 100%;
  margin: 0 auto;
  max-width: 1420px;
  position: relative;
}
</style>
