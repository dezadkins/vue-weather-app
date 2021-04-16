<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input
          type="text"
          name=""
          id=""
          class="search-bar"
          placeholder="Search..."
        />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      api_key: "18833f51ee8cb3359a47f58f81a6c64b",
    };
  },
};
</script>

<style>
#app {
  background-image: url("./assets/cold-bg.jpg");
  background-size: cover;
  background-position: bottom;
  transition: 0.4%;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "montserrat", sans-serif;
}

main {
  min-height: 100vh;
  padding: 25%;
}
</style>
