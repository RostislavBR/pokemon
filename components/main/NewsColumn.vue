<template>
  <section class="news-wrapper">
    <div class="news-box one">1</div>
    <div class="news-box two">2</div>
    <div class="news-box three">3</div>
    <div class="news-box four">4</div>
  </section>
</template>

<script>
  export default {
    name: 'NewsColumn'
  }
</script>

<style lang="scss">
  .news-wrapper {
    display: flex;
    height: 400px;
    flex-flow: column wrap;
    font-size: 2.6em;
    background: #ffffff;
    border-radius: 5px;
    padding: 10px;
    box-shadow: 0px 5px 10px 2px rgba(34, 60, 80, 0.2);

    .news-box {
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .one {
      background: #508694;
      margin-right: 10px;
      flex-basis: 100%;
      order: 1;
    }

    .two {
      background: #BB844C;
      margin-bottom: 10px;
      flex-basis: 100px;
      flex: 1 1 0;
      order: 2;
    }

    .three {
      background: #929D79;
      margin-bottom: 10px;
      flex-basis: 100px;
      flex: 1 1 0;
      order: 3;
    }

    .four {
      flex-basis: 100px;
      flex: 1 1 0;
      order: 4;
    }
  }
</style>
