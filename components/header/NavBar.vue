<template>
  <nav class="nav">
    <p class="nav-item">text</p>
    <p class="nav-item">text</p>
    <p class="nav-item">text</p>
    <p class="nav-item">text</p>
    <p class="nav-item">text</p>
    <p class="nav-item">text</p>
  </nav>
</template>

<script>
  export default {
    name: 'NavBar'
  }
</script>

<style lang="scss">
.nav {
  display: flex;
  justify-content: center;
  margin: 0;
  padding: 0;
  background: #fff;
  border-bottom: 2px solid #f0f0f0;
  .nav-item {
    margin: 0 10px;
    padding: 40px 30px;
  }
}
</style>
