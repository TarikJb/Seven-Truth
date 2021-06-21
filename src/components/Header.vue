<template>
  <!-- Header -->
  <div class="container-fluid">
    <nav class="navbar navbar-light bg-light">
      <a class="navbar-brand" href="#">
        <img src="../assets/icon.png" width="30" height="30" />
        7 Truth about you</a
      >
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style>
.navbar-light .navbar-brand {
  color: white;
  font-size: 18px;
  font-weight: 800 !important;
  line-height: 10px;
  word-spacing: 0px;
}
.bg-light {
  background-color: #c313b6 !important;
  height: 40px;
  padding: 0px;
}
.navbar-light .navbar-brand:hover {
  color: white;
}
.navbar-light .navbar-brand img {
  margin-left: 10px;
}

.container-fluid {
  padding: 0px;
  margin: 0px;
  max-width: 100%;
}
</style>
