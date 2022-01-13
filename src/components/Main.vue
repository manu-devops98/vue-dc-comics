<template>
  <main>
      <div class="container-80 cards">
          <p>-->Content goes here</p>
      </div>
          <div class="container-box">
              <div class="container-80">
              <div class="box">
                  <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                  <h3>DIGITAL COMICS</h3>
              </div>
              <div class="box">
                  <img src="../assets/img/buy-comics-merchandise.png" alt="">
                  <h3>DC MERCHANDISE</h3>
              </div>
              <div class="box">
                  <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                  <h3>SUBSCRIPTION</h3>
              </div>
              <div class="box">
                  <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                  <h3>COMIC SHOP LOCATOR</h3>
              </div>
              <div class="box">
                  <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                  <h3>DC POWERVISA</h3>
              </div>

              </div>
          </div>
  </main>
</template>

<script>
export default {
    name: "Main",
}
</script>

<style lang="scss" scoped>
  main {
      background-color: black;
      color: white;
      .cards {
          height: 100px;
          display: flex;
          align-items: center;
        p {
            font-size: 2em;
        }  
      }
      .container-box {
          background-color: #0082F9;
          .container-80 {
              display: flex;
              padding: 2em;
            .box {
                display: flex;
                align-items: center;
                width: calc(100% / 5);
                margin-left: 3em;
                img {
                    width: 20%;
                }
                h3 {
                    font-size: 0.8em;
                    margin-left: 1em;
                }
            }

          }
      }
  }
  
</style>