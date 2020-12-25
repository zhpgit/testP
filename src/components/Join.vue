<template>
    <div class="join">
        <div class="join_wrap">
            <h3>
                <span class="mr15">参与共享活动</span>
                <span>实现财富增值</span>
            </h3>
            <h4>工资存入银行？积蓄放进保险柜？NO！</h4>
            <el-row>
                <el-col :span="8">
                    <div>
                        <div class="join_icon join_reward"></div>
                        <p class="join_desc">参与共享活动，立得现金奖励</p>
                    </div>
                </el-col>
                <el-col :span="8">
                    <div>
                        <div class="join_icon join_flex"></div>
                        <p class="join_desc">可继续可结束，自由灵活</p>
                    </div>
                </el-col>
                <el-col :span="8">
                    <div>
                        <div class="join_icon join_profit"></div>
                        <p class="join_desc">无需等待，加入天天坐等收钱</p>
                    </div>
                </el-col>
            </el-row>
            <a href="javascript:void(0)" class="join_btn">立即参与</a>
        </div>
    </div>
</template>

<script>
    export default {
        name:'share',
        data(){
            return {

            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    a{text-decoration:none;}
    .mr15{margin-right:15px;}
    .join{width:100%;padding-bottom:50px;background:#ddd;overflow:hidden;}
    .join_wrap{width:1190px;margin:0 auto;}
    .join_wrap h3{ 
        width:100%;height:36px;margin:65px auto 20px;line-height:36px; 
        text-align:center;font-size:36px;font-weight:normal; 
    }
    .join_wrap h4{ 
        width:100%;height:24px;margin-bottom:70px;line-height:24px;text-align:center; 
        font-size:24px;font-weight:normal; 
    }
    .join_icon{ 
        width:160px;height:160px;margin:0 auto; 
        background:url('http://localhost:8080/static/images/csssp.png') no-repeat; 
    }
    /* .join_reward{background-position:0 -502px;} */
    /* .join_flex{background-position:0 -662px;} */
    /* .join_profit{background-position:0 -822px;} */
    .join_desc{ 
        margin:34px auto 65px;font-size:18px;font-weight:300;text-align:center; 
        color:#666; 
    }
    a.join_btn{ 
        display:block;width:200px;height:50px;margin:0 auto;text-align:center; 
        line-height:50px;font-size:24px;color:#fff;font-weight:bold; 
        background:url('http://localhost:8080/static/images/csssp.png') no-repeat; 
        background-position:0 0; 
    }
</style>