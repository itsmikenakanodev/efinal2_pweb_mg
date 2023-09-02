<template>
  <div class="nav-bar">
    <router-link to="/tokens">Tokens</router-link>
    <router-link to="/estudiantes">Estudiantes</router-link>
  </div>
</template>

<script>
export default {};
</script>

<style>
.nav-bar {
  background-color: #333;
  color: #fff;
  padding: 10px;
  position: fixed;
  top: 0;
  left:0;
  width: 100%;
  z-index: 1000;
}

.nav-bar a {
  text-decoration: none;
  color: #fff;
  margin-right: 20px;
}

.nav-bar a:hover {
  color: #ff6600;
}
</style>