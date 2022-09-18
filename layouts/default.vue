<template>
  <div>
    <div class="logo-wrapper">
      <img src="https://assets.pokemon.com/assets/cms2-ru-ru/img/misc/gus/buttons/logo-pokemon-79x45.png"
           alt="site_slug" class="gus-bounce">
    </div>
    <Header/>
    <main>
      <div class="container">
        <Nuxt/>
      </div>
    </main>
  </div>
</template>

<script>
  import Header from '~/components/header/Header'

  export default {
    name: 'defaultLayouts',
    components: { Header }
  }
</script>

<style lang="scss">
  body, html {
    padding: 0;
    margin: 0;
    overflow: hidden;
    background-image: url("../image/body_bg.png");
    background-size: cover;
    background-repeat: no-repeat;
  }
  .container {
    width: 1024px;
    margin: 0 auto;
    background-color: #fff;
    background-image: url("../image/container_bg.png");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .logo-wrapper {
    display: flex;
    justify-content: center;
    padding: 10px 0;
    background: #f5f5f5;
    border-bottom: 2px solid #dedede;
  }
</style>
