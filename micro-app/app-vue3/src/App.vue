<template>
  <div id="root">
    <p>app-vue</p>
    <p style="margin: 20px 0">
      <ul>
        <li>
          <router-link to="/home">home </router-link>
        </li>
        <li>
          <router-link to="/list">list </router-link>
        </li>
      </ul>
    </p>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
ul, li {
  list-style: none;
}
</style>
