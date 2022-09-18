<template>
  <div class="main-wrapper">
    <NewsColumn/>
  </div>
</template>

<script>
  import NewsColumn from '~/components/main/NewsColumn'
  export default {
    name: 'IndexPage',
    components: { NewsColumn }
  }
</script>

<style scoped>

</style>
