<template>
    <section class="banner">
        <!-- banner -->
        <div>
            <img src="../assets/vue-dc-comics-1/img/jumbotron.jpg" alt="Banner">
        </div>


            <!-- text -->
        <div class="banner-text">
            <h3>CURRENT SERIES</h3>
        </div>

        <!-- list item -->
        <div>
            <SingleSeries />
        </div>

        

        
    </section>
</template>

<script>
import SingleSeries from "./SingleSeries.vue";

export default {
    name: "ComicsList",
    components: {
        SingleSeries,
    },
}
</script>

<style scoped lang="scss">
.banner{
    height: 400px;
    width: 100%;
    overflow: hidden;

    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top;
    }
}
.banner-text{
    z-index: 2;
}
</style>