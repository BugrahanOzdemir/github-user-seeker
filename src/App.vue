<template>
  <div id="app">
    <main>
      <SearchBar />
      <CardInformation />
    </main>
  </div>
</template>

<script>
import CardInformation from "./components/CardInformation.vue";
import SearchBar from "./components/SearchBar.vue";

// import api from "./Api.js";

export default {
  name: "App",
  components: {
    SearchBar,
    CardInformation,
  },
};
</script>

<style lang="scss">
@use "@/styles/_global.scss" as *;

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  font-family: $font-family;
  font-size: 62.5%;
}

body {
  background-color: $primary-background-dark;
  transition: 0.3s ease all;
}

@media (min-width: 768px) {
  body {
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 100vh;
  }
}
</style>