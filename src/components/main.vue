
<template>
    <main>
        <section id="first-part-main">
            <div class="container">
                <div>--<i class="fas fa-chevron-right"></i></div>
                <div class="text">Content goes here</div>
                <div><i class="fas fa-chevron-left">--</i></div>
            </div>
        </section>
        <section id="second-part-main" >
            <div class="container">
                <!-- col -->
                <div class="col">
                    <div class="col-img">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="buy-comics-digital-comics.png">
                    </div>
                    <div class="col-text">
                        DIGITAL COMICS
                    </div>
                </div>
                <!-- col -->
                <div class="col">
                    <div class="col-img">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-merchandise.png" alt="buy-comics-digital-comics.png">
                    </div>
                    <div class="col-text">
                        DC MERCHANDISE
                    </div>
                </div>
                <!-- col -->
                <div class="col">
                    <div class="col-img">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="buy-comics-digital-comics.png">
                    </div>
                    <div class="col-text">
                        SUBSRIPTION
                    </div>
                </div>
                <!-- col -->
                <div class="col">
                    <div class="col-img">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="buy-comics-digital-comics.png">
                    </div>
                    <div class="col-text">
                        COMICS SHOP LOCATOR
                    </div>
                </div>
                <!-- col -->
                <div class="col">
                    <div class="col-img">
                        <img src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="buy-comics-digital-comics.png">
                    </div>
                    <div class="col-text">
                        DC PWER VISA
                    </div>
                </div>
                
            </div>
        </section>
        
    </main>
</template>

<script>
export default {
    name: "Main",
};
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

#first-part-main{
    background-color: $brand_secondary_color;
    height: 150px;
    display: flex;
    align-items: center;

    .container{
        color: white;
        font-size: 30px;
    }
        .text{
            padding: 0 10px;
        }
}
#second-part-main{
    background-color: $brand_primary_color;
    height: 150px;
    
    .container{
    height: 100%;


        .col{
        width: calc(100% / 5);
        height: 100%;
        border: 1px solid black;
        display: flex;
        align-items: center;
        justify-content: center;
        }

        .col-img{
            width: 45px;
            
        }
        .col-text{
            padding: 0 10px;
            font-size: 14px;
            color: $white-color;
        }
    }

    
}
</style>