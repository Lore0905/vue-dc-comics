
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

        .col-sx{
            width: 40%;
        
        }
        
    }
    .col-dx{
        background-image: url("../assets/vue-dc-comics-1/img/dc-logo-bg.png");
        height: 100%;
        width: 50%;
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;

    }
}
.col-inside{
    width: calc(100% / 4);

        h2{
            color:$white-color;
            font-size: 20px;
            padding: 10px 0px;
        }
        
        li{
            padding: 3px 0;

            a{
                color: rgb(155, 152, 152);
                font-size: 14-px;
                padding: 10px 0;
            }
        }
            
    }
.container{
    height: 100%;
    display: flex;
    align-items: center;
}

</style>