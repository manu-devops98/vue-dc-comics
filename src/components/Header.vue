<template>
  <header>
    <div class="container-80 flex">
      <img src="../assets/img/dc-logo.png" alt="" />
      <ul class="flex">
        <li><a href="">CHARACTERS</a></li>
        <li><a class="active" href="">COMICS</a></li>
        <li><a href="">MOVIES</a></li>
        <li><a href="">TV</a></li>
        <li><a href="">GAMES</a></li>
        <li><a href="">COLLECTIBLES</a></li>
        <li><a href="">VIDEOS</a></li>
        <li><a href="">FANS</a></li>
        <li><a href="">NEWS</a></li>
        <li><a href="">SHOP</a></li>
      </ul>
    </div>
    <!-- <div class="jumbotron-bg"></div> -->
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 120px;
  z-index: 9999;
  background-color: white;
  .container-80 {
    justify-content: space-between;
    align-items: center;
    img {
      width: 70px;
    }
    ul {
      list-style: none;
      li {
        a {
          font-size: 1em;
          text-decoration: none;
          color: black;
          display: block;
          padding: 3em 0.5em;
          border-bottom: 4px solid transparent;
          transition: 0.9s;
          &:hover {
            color: #0082f9;
            border-bottom: 4px solid #0082f9;
          }
          &.active {
            color: #0082f9;
            border-bottom: 4px solid #0082f9;
          }
        }
      }
    }
  }
  // .jumbotron-bg {
  //   background-image: url("../assets/img/jumbotron.jpg");
  //   background-size: cover;
  //   background-repeat: no-repeat;
  //   height: 300px;
  // }
}
</style>
