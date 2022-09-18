<template>
  <header class="header">
    <NavBar/>
  </header>
</template>

<script>
  import NavBar from '~/components/header/NavBar'

  export default {
    name: 'HeaderComponent',
    components: { NavBar }
  }
</script>

<style scoped>

</style>
