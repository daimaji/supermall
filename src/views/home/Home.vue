<template>
    <div id="home">
      <Navbar class="home-nav">
        <div slot="center">购物街</div>
      </Navbar>
    </div>
</template>

<script>
  import Navbar from 'components/common/navbar/Navbar'

    export default {
      name: "Home",
      components: {
        Navbar
      }
    }
</script>

<style scoped>
  .home-nav {
    background-color: pink;
    color: #fff;
  }
</style>
