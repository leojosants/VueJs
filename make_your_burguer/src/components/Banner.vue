<!--  -->
<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
  export default {
    name: 'Banner'
  }
</script>

<style scoped>
    #main-banner {
      background-image: url('/REPOSITORIO_GITHUB_DESKTOP/VueJs/make_your_burguer/public/img/burger.jpg');
      background-position: 0 -250px;
      background-size: cover;
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: flex-start;
    }

    #main-banner h1 {
      color: #fff;
      text-align: center;
      font-size: 60px;
      background-color: #222;
      padding: 50px 40px;
    }
</style>