
<template>
    <footer>
        <section class="refer">
            <div class="container">
                <!-- col sx -->
                <div class="col col-sx">
                    <!--  COL INSIDE -->
                    <div class="col-inside">

                        <h2>DC COMICS</h2>

                        <ul>
                            <li>
                                <a href="#">Characters</a>
                            </li>
                            <li>
                                <a href="#">Comics</a>
                            </li>
                            <li>
                                <a href="#">Movies</a>
                            </li>
                            <li>
                                <a href="#">TV</a>
                            </li>
                            <li>
                                <a href="#">Games</a>
                            </li>
                            <li>
                                <a href="#">Videos</a>
                            </li>
                            <li>
                                <a href="#">News</a>
                            </li>
                        </ul>

                        <h2>SHOP</h2>

                        <ul>
                            <li>
                                <a href="#">Shop DC</a>
                            </li>
                            <li>
                                <a href="#">Shop DC Collectibles</a>
                            </li>
                        </ul>
                    </div>

                    <!--  COL INSIDE -->
                    <div class="col-inside">

                        <h2>DC</h2>

                        <ul>
                            <li>
                                <a href="#">Terms Of Use</a>
                            </li>
                            <li>
                                <a href="#">Privacy policy (new)</a>
                            </li>
                            <li>
                                <a href="#">Ad Choices</a>
                            </li>
                            <li>
                                <a href="#">Advertising</a>
                            </li>
                            <li>
                                <a href="#">Jobs</a>
                            </li>
                            <li>
                                <a href="#">Subscription</a>
                            </li>
                            <li>
                                <a href="#">Talent Workshops</a>
                            </li>
                            <li>
                                <a href="#">CPSC Certificates</a>
                            </li>
                            <li>
                                <a href="#">Ratings</a>
                            </li>
                            <li>
                                <a href="#">Shop Help</a>
                            </li>
                            <li>
                                <a href="#">Contact Us</a>
                            </li>
                        </ul>

                    </div>
                    <!--  COL INSIDE -->
                    <div class="col-inside">

                        <h2>SITES</h2>

                        <ul>
                            <li>
                                <a href="#">DC</a>
                            </li>
                            <li>
                                <a href="#">MAD Magazine</a>
                            </li>
                            <li>
                                <a href="#">DC Kinds</a>
                            </li>
                            <li>
                                <a href="#">DC Universe</a>
                            </li>
                            <li>
                                <a href="#">DC Power Visa</a>
                            </li>
                           
                        </ul>
                        
                    </div>
                    
                    
                </div>
                <!-- col dx -->
                <div class="col col-dx">
                    
                </div>
            </div>

        </section>
       <section class="share-sites">
           <div class="container">
                <div class="col-sx">
                    <button>SIGN-UP NOW</button>
                </div>
                <div class="col-dx">
                    <h2>FOLLOW US</h2>
                    <ul>
                        <li>
                            <img src="../assets/vue-dc-comics-1/img/footer-facebook.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/vue-dc-comics-1/img/footer-twitter.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/vue-dc-comics-1/img/footer-youtube.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/vue-dc-comics-1/img/footer-pinterest.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/vue-dc-comics-1/img/footer-periscope.png" alt="">
                        </li>
                    </ul>
                </div>
           

            </div>

       </section>
    </footer>
</template>

<script>
export default {
    name: "Footer",
};
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

.refer{
    background-image: url("../assets/vue-dc-comics-1/img/footer-bg.jpg");
    height: 50vh;
    width: 100%;
    background-size: cover;
    display: flex;
    align-items: center;

    .col{
        width: calc(100% / 2);
        display: flex;
        
    }
    .col-dx{
        background-image: url("../assets/vue-dc-comics-1/img/dc-logo-bg.png");
        height: 100%;
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;

    }
}
.col-inside{
    width: calc((100% / 3) - 70px);

        h2{
            color:$white-color;
            font-size: 20px;
            padding: 10px 0px;
        }
        
        ul{
            li{
                padding: 5px 0;

                a{
                    color: rgb(155, 152, 152);
                    font-size: 14-px;
                }
            }
        }   
    }
.container{
    height: 100%;
    display: flex;
    align-items: center;
}
.share-sites{
    background-color: #303030;
    width: 100%;
    height: 100px;
    display: flex;
    
    .col-sx{
        flex-grow: 1;
        button{
            padding: 10px;
            border: 2px solid $brand_primary_color;
            background-color: #303030;
            color: white;
            cursor: pointer;
            font-size: 20px;
        }
    }
    .col-dx{
        display: flex;
        align-items: center;
        font-size: 15px;

        h2{
            color:$brand_primary_color;
            padding: 0 20px;
        }

        ul{
            display: flex;

            li{
                padding: 0 7px ;
            }
        }
        

    }
}


</style>