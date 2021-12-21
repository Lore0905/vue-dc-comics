
<template>
    <header class="container">
        <div class="col col-sx">
            <img id="logo" src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="logo">
        </div>
        
        <div class="col col-dx">
            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a :href="link.url">{{link.text}}</a>
                </li>
                
            </ul>
        </div>

    </header>
</template>

<script>
export default {
    name: "Header",
    data: function() {
        return {
            links: [
                {
                    text: 'CHARACTERS',
                    url: '#'
                },
                {
                    text: 'COMICS',
                    url: '#'
                },
                {
                    text: 'MOVIES',
                    url: '#'
                },
                {
                    text: 'TV',
                    url: '#'
                },
                {
                    text: 'GAMES',
                    url: '#'
                },
                {
                    text: 'COLLECTIBLES',
                    url: '#'
                },
                {
                    text: 'VIDEOS',
                    url: '#'
                },
                {
                    text: 'FANS',
                    url: '#'
                },
                {
                    text: 'NEWS',
                    url: '#'
                },
                {
                    text: 'SHOP',
                    url: '#'
                },
            ]
        }
    }
        
        
    
};
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

.col{
    height: 100px;
}
.col-sx{
    width: 35%;
    display: flex;
    align-items: center;

    #logo{
    width: 80px;
    }
}


.col-dx{
    width: 65%;
    
    ul{
    display: flex;
    justify-content: center;
    }
        li{
            margin: 0 7px;
        }
            a{
                display: block;
                line-height: 95px;
            }
            a:hover{
                color: $brand_primary_color;
                border-bottom: 5px solid $brand_primary_color;
            }
}

</style>
