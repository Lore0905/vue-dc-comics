<template>


    <!-- single serie -->
    <div class="single-serie">
        <!-- img-->
        <div class="img-serie">
            <img :src="seriesObject.thumb" :alt="seriesObject.series">
        </div>

        <!-- title  -->
        <h4>{{seriesObject.series}}</h4>
    </div>


</template>

<script>

export default {
    name: "SingleSeries",
    
    props: ['seriesObject']
}
</script>

<style scoped lang="scss">
.single-serie{
    width: calc(100% / 6);
    .img-serie{
        margin: auto;
    }
    h4{
        margin: auto;
    }
}
</style>