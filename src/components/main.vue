
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
                <div class="col" v-for="(item, index) in items" :key="index">
                    <div class="col-img">
                        <img :src="require('../assets/vue-dc-comics-1/img/' + item.img)">
                    </div>
                    <div class="col-text">
                        {{item.text}}
                    </div>
                </div>                
            </div>
        </section>
        
    </main>
</template>

<script>
export default {
    name: "Main",
    data: function(){
        return{
            items: [
                {
                    img: "buy-comics-digital-comics.png",
                    text: "DIGITAL COMICS"
                },
                {
                    img: "buy-comics-merchandise.png",
                    text: "DC MERCHANDISE"
                },
                {
                    img: "buy-comics-subscriptions.png",
                    text: "SUBSRIPTION"
                },
                {
                    img: "buy-comics-shop-locator.png",
                    text: "COMICS SHOP LOCATOR"
                },
                {
                    img: "buy-comics-shop-locator.png",
                    text: "DC PWER VISA"
                }
            ]
        }
    }
};
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

#first-part-main{
    background-color: $brand_secondary_color;
    display: flex;
    align-items: center;

    .container{
        color: white;
        font-size: 30px;
        padding: 60px 0;
    }
        .text{
            padding: 0 10px;
        }
}
#second-part-main{
    background-color: $brand_primary_color;
    
    .container{
    height: 100%;

        .col{
        width: calc(100% / 5);
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 60px 0;
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