<template>
  <div class="container text-center">
    <div class="body">
      <h1 class="h1">Dare For your Friends</h1>
      <h3 class="h3">7 Truths about you</h3>
    </div>
    <div class="lang">
      <label>Select Language :</label><br />
      <select class="sl browser-default custom-select">
        <option value="en">English</option>
        <option value="ar">عربي</option>
      </select>
    </div>
    <label>Your Name :</label><br />
    <div class="name">
      <input type="text" class="form-control" placeholder="Full Name" />
    </div>
    <div class="btn bn-block">
      <button class="btn btn-default">👉&nbsp;Register&nbsp;👈</button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {},
}
</script>
<style scoped>
.sl {
  max-width: 60%;
}
.lang {
  margin-top: 50px;
}
.form-control {
  width: 75%;
}
.name {
  margin-left: 20%;
}
.btn {
  margin: 0px auto;
  margin-top: 2px;
  width: 79%;
}
.btn-default {
  color: white;
  background-color: #d00a6f;
}

.btn:hover,
.btn-default :hover {
  color: white !important;
}
</style>
