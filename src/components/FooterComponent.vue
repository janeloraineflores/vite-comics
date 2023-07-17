<script>
    export default {
        name: "FooterComponent",
        data() {
            return {

            }
        },
        methods: {

        }
    }
</script>

<template>
   
   <footer>
        <section class="footer-top">
        <div class="container">
            <div class="footer-cols">

            <div class="footer-col">
                <div class="footer-logo">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                </div>
                <a href="#">
                DIGITAL COMICS
                </a>
            </div>
            <div class="footer-col">
                <div class="footer-logo">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                </div>
                <a href="#">
                DC MERCHANDISE
                </a>
            </div>
            <div class="footer-col">
                <div class="footer-logo">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                </div>
                <a href="#"> 
                SUBSCRIPTION
                </a>
            </div>
            <div class="footer-col">
                <div class="footer-logo">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                <a href="#">
                SHOP LOCATOR
                </a>
            </div>
            <div class="footer-col">
                <div class="footer-logo">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                </div>
                <a href="#">
                POWER VISA
                </a>
            </div>
            </div>
        </div>
        </section>

        <section class="footer-middle">

        <div class="container">
            <div class="footer-cols">
            
                <div class="left">
                    <div class="footer-col">
                        <ul>
                        <li>
                            <h4 href="#">
                            DC COMICS
                            </h4>
                        </li>
                        <li>
                            <a href="#">
                            Characters
                            </a>
                        </li>
                        <li>
                            <a href="#">
                            Comics
                            </a>
                        </li>
                        <li>
                            <a href="#">
                            Movies
                            </a>
                        </li>
                        <li>
                            <a href="#">
                            TV
                            </a>
                        </li>
                        <li>
                            <a href="#">
                            Games
                            </a>
                        </li>
                        <li>
                            <a href="#">
                            Videos
                            </a>
                        </li>
                        <li>
                            <a href="#">
                            News
                            </a>
                        </li>
                        <li>
                            <h4 href="#">
                            SHOP
                            </h4>
                        </li>
                        <li>
                            <a href="#">
                            Shop DC
                            </a>
                        </li>
                        <li>
                            <a href="#">
                            Shop DC Collectibles
                            </a>
                        </li>
                        </ul>
                    </div>

                <div class="footer-col">
                    <ul>
                    <li>
                        <h4 href="#">
                        DC
                        </h4>
                    </li>
                    <li>
                        <a href="#">
                        Terms Of Use
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Privacy policy (New)
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Ad Choices
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Advertising
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Jobs
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Subscritions
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Talent Workshops
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        CPSC Certificates
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Ratings
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Shop Help
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        Contact Us
                        </a>
                    </li>
                    </ul>
                </div>

                <div class="footer-col">
                    <ul>
                    <li>
                        <h4 href="#">
                        SITES
                        </h4>
                    </li>
                    <li>
                        <a href="#">
                        DC
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        MAD Magazine
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        DC Kids
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        DC Universe
                        </a>
                    </li>
                    <li>
                        <a href="#">
                        DC Power Visa
                        </a>
                    </li>
                    </ul>
                </div>
                </div>
                <div class="right">
                    <div class="image-container">
                        <img src="../assets/img/dc-logo-bg.png" alt="">
                    </div>
                </div>

            </div>

        </div>

        </section>

        <section class="footer-bottom">
        <div class="container">
            
            <button>
            SIGN-UP NOW!
            </button>
            <div class="icons">
                <h4>
                    FOLLOW US
                </h4>
                <a href="#" >
                    <i class="bi bi-facebook"></i>
                </a>
                <a href="#">
                    <i class="bi bi-twitter"></i>
                </a>
                <a href="#">
                    <i class="bi bi-youtube"></i>
                </a>
                <a href="#">
                    ()
                </a>
                <a href="#">
                    <i class="bi bi-geo-alt-fill"></i>
                </a>
            </div>
            
           
        </div>
        </section>

    </footer>
</template>

<style lang="scss" scoped>
     
  footer {

.footer-cols {
  display: flex;
  flex-wrap: wrap;
}

.footer-col {
  width: calc(100% / 5);
  display: flex;
  
}

}

.footer-top {
background-color: #0282F9;
padding: 40px 10px;


.footer-logo {
  width: 35px;
  height: 40px;
  margin-right: 5px;

  img{
    width: 100%;
    height: 100%;
  }
}

.footer-col {
  align-items: center;

  a {
    text-decoration: none;
    color: white;
  }
}
}

.footer-middle {
    background-image: url(../assets/img/footer-bg.jpg);
    padding-top: 30px;
    padding-bottom: 40px;
    
   

    .footer-cols {
        display: flex;
        justify-content: space-between;

        .left {
            width: 80%;

            .footer-col {
                display: inline-block;
                
            }
        }

        .right {
            width: 20%;
           
           
            

            .image-container {
                width: 450px;
               

                img{
                    width: 100%;
                    height: 100%
                }
            }
        }
    }



    h4 {
    color: white;
    padding-top: 20px;
    padding-bottom: 10px;
    }

    ul {
    list-style: none;
    }

    li{
    margin-bottom: 3px;
    }

    a{
    text-decoration: none;
    color: grey;
    
    }
}

.footer-bottom {
    background-color: #323232;
    padding: 30px 0;


    .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    }

    button {
    background-color: rgba(0, 255, 255, 0);
    border: 2px solid #0282F9 ;
    color: white;
    padding: 20px;
    font-weight: bolder;  
    cursor: pointer;
    }

    .icons {
    display: flex;

    h4{
        color: #0282F9;
        margin-right: 20px;
    }

    * {
        margin-right: 10px;
    }

    a {
        text-decoration: none;
        color: lightslategrey;
        font-size: 30px;
    }
    }
}
</style>