<template>
  <div>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/databinding/string">String</router-link> |
      <router-link to="/databinding/html">HTML</router-link> |
      <router-link to="/databinding/input">Input</router-link> |
      <router-link to="/databinding/select">Select</router-link> |
      <router-link to="/databinding/check">Checkbox</router-link> |
      <router-link to="/databinding/radio">Radio</router-link> |
      <router-link to="/databinding/attr">Attribute</router-link> |
      <router-link to="/databinding/list">List</router-link> |
      <router-link to="/databinding/Class">Class</router-link> |
      <router-link to="/databinding/Style">Style</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
