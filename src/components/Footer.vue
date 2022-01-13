<template>
<footer>
    <div class="footer-top">
      <div class="container-80">
          <div class="col-left">
          <div class="col">
              <h3>DC COMICS</h3>
              <ul>
                  <li><a href="">Characters</a></li>
                  <li><a href="">Comics</a></li>
                  <li><a href="">Movies</a></li>
                  <li><a href="">TV</a></li>
                  <li><a href="">Games</a></li>
                  <li><a href="">Videos</a></li>
                  <li><a href="">News</a></li>
              </ul>
              <h3>SHOP</h3>
              <ul>
                  <li><a href="">Shop DC</a></li>
                  <li><a href="">Shop DC Collectibles</a></li>
              </ul>
          </div>
          <div class="col">
              <h3>DC</h3>
              <ul>
                  <li><a href="">Terms Of Use</a></li>
                  <li><a href="">Privacy Policy (New)</a></li>
                  <li><a href="">Add Choices</a></li>
                  <li><a href="">Advertising</a></li>
                  <li><a href="">Jobs</a></li>
                  <li><a href="">Subscriptions</a></li>
                  <li><a href="">Talent Workshop</a></li>
                  <li><a href="">CSPC Certificates</a></li>
                  <li><a href="">Ratings</a></li>
                  <li><a href="">Shop Help</a></li>
                  <li><a href="">Contact Us</a></li>
              </ul>
          </div>
          <div class="col">
              <h3>SITES</h3>
              <ul>
                  <li><a href="">DC</a></li>
                  <li><a href="">MAD Magazines</a></li>
                  <li><a href="">DC Kids</a></li>
                  <li><a href="">DC Universe</a></li>
                  <li><a href="">DC Power Visa</a></li>
              </ul>
          </div>

          </div>
          <div class="col-right">
              <img src="../assets/img/dc-logo-bg.png" alt="">
          </div>

        </div>
    </div>
      <div class="footer-bottom">
          <div class="container-80">
              <div class="col-left">
                  <a class="button" href="">SIGN-UP NOW!</a>
              </div>
              <div class="col-right">
                  <h2 id="follow">FOLLOW US</h2>
                  <img src="../assets/img/footer-facebook.png" alt="">
                  <img src="../assets/img/footer-twitter.png" alt="">
                  <img src="../assets/img/footer-youtube.png" alt="">
                  <img src="../assets/img/footer-pinterest.png" alt="">
                  <img src="../assets/img/footer-periscope.png" alt="">
              </div>
          </div>
      </div>
</footer>
</template>

<script>
export default {
    name: "Footer",
}
</script>

<style lang="scss" scoped>
.footer-top {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    position: relative;
    .container-80 {
        display: flex;
        justify-content: space-between;
        padding: 2em;
        .col-left {
            display: flex;
            .col {
                margin: 0 2em 0 0;
            }
            .col h3 {
                    color: white;
                    margin-bottom: 0.5em;
                }
                
            .col ul {
                list-style: none;
                li {
                    margin-bottom: 0.3em;
                    a {
                        color: #797979;
                        text-decoration: none;
                        font-size: 0.8em;
                        cursor: pointer;
                        &:hover {
                            text-decoration: underline;
                            color: white;
                            z-index: 3;
                        }
                    }
                }
            }
        }
        .col-right {
            text-align: center;
            // position: absolute;
            // top: -90px;
            // right: 180px;
            img {
               width: 60%;
           }
        }
    }     
}

.footer-bottom {
    background-color: #30302F;
    height: 100px;
    display: flex;
    z-index: 2;
   .container-80 {
       display: flex;
       align-items: center;
       justify-content: space-between;
       .button {
           text-decoration: none;
           color: white;
           padding: 1em 1.5em;
           border: 2px solid #0082F9;
           transition: 0.5s;
           &:hover {
               background-color: #0082F9;
           }
       }
       .col-right {
           display: flex;
           align-items: center;
           #follow {
               font-size: 1.2em;
               margin-right: 0.5em;
               color: #0082F9;
           }
           img {
               margin: 0 0.5em;
           }
       }
   }
}
</style>