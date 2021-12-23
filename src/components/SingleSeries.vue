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
    display: flex;
    flex-direction: column;
    padding: 10px;
    
    .img-serie{
        width: 170px;
        height: 170px;
        overflow: hidden;
        padding-bottom: 20px 0px;
        

        img{
            display: block;
        }
    }
    h4{
        padding: 20px 0;
        text-transform: uppercase;
    }
}
</style>