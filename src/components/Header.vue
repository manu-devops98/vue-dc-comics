<template>
  <header>
      <div class="container-80 flex">
          <img src="../assets/img/dc-logo.png" alt="">
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
  </header>
</template>

<script>
export default {
    name: "Header",
}
</script>

<style lang="scss" scoped>

    header {
        .container-80 {
            // background-color: red;
            justify-content: space-between;
            align-items: center;
            padding: 1em;
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
                     padding: 2em 0.5em;
                     &:hover {
                        color: #0082F9;
                     }
                     &.active {
                         color: #0082F9;
                         border-bottom: 4px solid #0082F9;
                     }
                 } 
               }  
            }

        }
    }
</style>
