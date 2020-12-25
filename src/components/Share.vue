<template>
    <div class="share">
        <h3>热门共享</h3>
        <el-row :gutter="20">
            <el-col :span="6">
                <div class="share_item">
                    <a href="javascript:void(0)" class="share_img_wrap">
                        <img src="/static/images/goods.jpg" class="share_img"/>
                    </a>
                    <a href="javascript:void(0)" class="share_price">￥125.00</a>
                    <a href="javascript:void(0)" class="share_desc">
                    Kuegou夏季新款男士短袖纯色立领修身T恤</a>
                </div>
            </el-col>
            <el-col :span="6">
                <div class="share_item">
                    <a href="javascript:void(0)" class="share_img_wrap">
                        <img src="/static/images/goods.jpg" class="share_img"/>
                    </a>
                    <a href="javascript:void(0)" class="share_price">￥125.00</a>
                    <a href="javascript:void(0)" class="share_desc">
                    Kuegou夏季新款男士短袖纯色立领修身T恤</a>
                </div>
            </el-col>
            <el-col :span="6">
                <div class="share_item">
                    <a href="javascript:void(0)" class="share_img_wrap">
                        <img src="/static/images/goods.jpg" class="share_img"/>
                    </a>
                    <a href="javascript:void(0)" class="share_price">￥125.00</a>
                    <a href="javascript:void(0)" class="share_desc">
                    Kuegou夏季新款男士短袖纯色立领修身T恤</a>
                </div>
            </el-col>
            <el-col :span="6">
                <div class="share_item">
                    <a href="javascript:void(0)" class="share_img_wrap">
                        <img src="/static/images/goods.jpg" class="share_img"/>
                    </a>
                    <a href="javascript:void(0)" class="share_price">￥125.00</a>
                    <a href="javascript:void(0)" class="share_desc">
                    Kuegou夏季新款男士短袖纯色立领修身T恤</a>
                </div>
            </el-col>
        </el-row>
    </div>
</template>

<script>
    export default {
        name:'share',
        data(){
            return{

            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    a{text-decoration:none;}
    .share{width:100%;padding-bottom:100px;overflow:hidden;}
    .share h3{ 
        width:100%;height:34px;margin:42px auto 49px;line-height:34px;text-align:center; 
        font-size:34px;font-weight:normal; 
    }
    .share_item{width:100%;}
    a.share_img_wrap{display:block;width:100%;margin-bottom:17px;overflow:hidden;}
    .share_img{ 
        display:block;width:100%;transition:all 1s;-webkit-transition:all 1s; 
        -o-transition:all 1s;-moz-transition:all 1s;-ms-transition:all 1s; 
    }
    a.share_img_wrap:hover .share_img{ 
        transform:scale(1.2);-webkit-transform:scale(1.2);-o-transform:scale(1.2); 
        -moz-transform:scale(1.2);-ms-transform:scale(1.2); 
    }
    a.share_price{display:block;text-align:left;font-size:16px;color:#ff5600;}
    a.share_desc{ 
        display:block;width:100%;margin-top:8px;line-height:24px;font-size:16px; 
        color:#606060;overflow:hidden; 
    }
    a.share_desc:hover{text-decoration:underline;}
</style>