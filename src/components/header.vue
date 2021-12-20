
<template>
    <header class="container">
        <div class="col col-sx">
            <img id="logo" src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="logo">
        </div>
        
        <div class="col col-dx">
            <ul>
                <li>
                    <a href="#">CHARACTERS</a>
                </li>
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">MOVIES</a>
                </li>
                <li>
                    <a href="#">TV</a>
                </li>
                <li>
                    <a href="#">GAMES</a>
                </li>
                <li>
                    <a href="#">COLLECTIBLES</a>
                </li>
                <li>
                    <a href="#">VIDEOS</a>
                </li>
                <li>
                    <a href="#">FANS</a>
                </li>
                <li>
                    <a href="#">NEWS</a>
                </li>
                <li>
                    <a href="#">SHOP</a>
                </li>
            </ul>
        </div>

    </header>
</template>

<script>
export default {
    name: "Header",
};
</script>

<style scoped >
@import '../style/variables.scss';

.col{
    height: 100px;
}
.col-sx{
    width: 35%;
    display: flex;
    align-items: center;
    background-color: pink;
}
#logo{
    width: 80px;
}

.col-dx{
    width: 65%;
    background-color: lightblue;
}
ul{
    display: flex;
    justify-content: center;
}
li{
    margin: 7px;
}
a:hover{
    color: $brand_primary_color;
}
</style>