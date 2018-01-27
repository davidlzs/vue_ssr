<template>
  <div id="app">
    Hello World!
    <p>
      <router-link to="/">Go To Home</router-link>
      <router-link to="/about">Go To About</router-link>
    </p>
    <router-view></router-view>
</template>
<script>
  export default {
  };
</script>
