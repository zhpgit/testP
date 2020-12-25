<template>
    <div class="clock">
        <h3>
            <span class="mr15">每天一次打卡</span>
            <span>收获一份惊喜</span>
        </h3>
        <h4>
            <span class="mr10">无需投资</span>
            <span>天天赚钱</span>
        </h4>
        <el-row>
            <el-col :span="12">
                <div>
                    <div class="clock_icon clock_reward"></div>
                    <span class="clock_title">新人奖励</span>
                    <p class="clock_txt">7天内打卡每天额外获2元奖励</p>
                    <p class="clock_txt">满20提现</p>
                </div>
            </el-col>
            <el-col :span="12">
                <div>
                    <div class="clock_icon clock_invite"></div>
                    <span class="clock_title">邀请奖励</span>
                    <p class="clock_txt">邀请好友参与，最高日赚10000元！</p>
                    <p class="clock_txt">赚钱先机，错过再无！</p>
                </div>
            </el-col>
        </el-row>
        <a href="javascript:void(0)" class="clock_btn">立即打卡</a>
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
    .mr10{margin-right:10px;}
    .clock{width:100%;padding-bottom:50px;overflow:hidden;}
    .clock h3{
        width:100%;height:34px;margin:66px auto 20px;line-height:34px;
        text-align:center;font-size:34px;font-weight:normal; 
    }
    .clock h4{
        width:100%;height:20px;margin-bottom:70px;line-height:20px;
        text-align:center;font-size:20px;font-weight:normal; 
    }
    .clock_icon{
        width:205px;height:226px;margin:0 auto; 
        background:url('http://localhost:8080/static/images/csssp.png') no-repeat; 
    }
    .clock_reward{background-position:0 -50px;}
    .clock_invite{background-position:0 -276px;}
    .clock_title{ 
        display:block;width:100%;margin:48px auto 20px;color:#666;font-size:36px; 
        text-align:center; 
    }
    .clock_txt{width:100%;text-align:center;font-size:20px;line-height:30px;}
    a.clock_btn{
        display:block;width:200px;height:50px;margin:66px auto 0;text-align:center; 
        line-height:50px;font-size:24px;color:#fff;font-weight:bold; 
        background:url('http://localhost:8080/static/images/csssp.png') no-repeat; 
        background-position:0 0; 
    }
</style>