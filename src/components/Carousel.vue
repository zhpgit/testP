<template>
    <div class="carousel">
        <el-carousel trigger="click" class="carousel_wrap">
            <el-carousel-item v-for="(img,idx) in imgs" :key="idx" class="carousel_item">
                <img :src="'/static/images/'+img.imgurl" class="carousel_img"/>
            </el-carousel-item>
        </el-carousel>
    </div>
</template>

<script>
    export default {
        name:'carousel',
        data(){
            return {
                imgs:[
                    {imgurl:"1.jpg"},
                    {imgurl:"2.jpg"}
                ]
            }
        }
    }
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .carousel,.carousel_wrap,.carousel_item,.carousel_img{
                            display:block;width:100%;height:460px; 
    }
</style>