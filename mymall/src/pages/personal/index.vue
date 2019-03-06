<template>
    <div>
        <!-- 用户信息最最外面的盒子-->
        <div class="m-userinfo">
            <!-- 最上面一部分 -->
            <div class="m-top">
                <div class="m-left">
                   <img src="./images/1.jpg"> 
                </div>
                <div class="m-center">
                    <h2>桃子小姐</h2>
                    <span></span>
                </div>
                <div class="m-right">
                    <a href="#"></a>
                    <a href="#"></a>
                </div>
            </div> 
            <!-- 下面的一部分 -->
            <ul class="m-bottom">
                <li>
                    <a href="#">
                        <span>7</span>
                        <span>收藏夹</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span>10</span>
                        <span>关注店铺</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span>7</span>
                        <span>收藏夹</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span>5</span>
                        <span>足迹</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <span>6</span>
                        <span>优惠券</span>
                    </a>
                </li>
            </ul>
        </div>
        <!-- 最外面的盒子结束 -->
        <!-- 会员 淘气值开始 -->
        <div class="member">
            <div class="b-left">
                <img src="./images/TB1uUPQff9TBuNjy0FcXXbeiFXa-212-42.png">
                <span>淘气值 677</span>
            </div>
            <div class="b-right">
                <span>花小积分 兑大权益</span>
                <a href="#">进入我的会员中心</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.m-userinfo{
    width:100%;
    height:147px;
    background:#ff5000;
    padding:24px 10px 0;
}
.m-top{
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: space-between
}
.m-left img{
    width:49px;
    height:49px;
    border-radius:50%;
}
.m-center{
    display: flex;
    flex: 1;
    width: 100%;
    flex-direction: column;
}
.m-center h2{
    font-size:16px;
    line-height:24px;
    margin:0 5px 5px 20px;
    color: rgb(255, 255, 255);
}
.m-center span{
    width: 100%;
    height: 21px;
    background: url(./images/TB1Us_ja7voK1RjSZFNXXcxMVXa-436-63.png) left no-repeat;
    background-size: 145px 100%;
    margin-left:18px;
}
.m-right{
    display: flex;
    justify-content:space-around;
}
.m-right a{
    width:20px;
    height: 20px;
    background: url(./images/TB1RP44oQvoK1RjSZFDXXXY3pXa-54-54.png) center;
    background-size: 100% 100%;
}
.m-right a:last-of-type{
     background: url(./images/TB1dbweXwHqK1RjSZFgXXa7JXXa-57-54.png) center;
     background-size:20px 20px;
     margin-left: 16px;
}
.m-bottom{
    width:100%;
    height:50px;
    display:flex;
    margin-top:10px;
}
.m-bottom li{
    width: 25%;
}
.m-bottom li a{
    width:100%;
    height:100%;
    display:flex;
    align-items:center;
    font-size:12px;
    justify-content:center;
    flex-direction: column;
}
.m-bottom li a span{
    line-height:22px;
    color:#fff;
}
/* 会员 */
.member{
   width:100%;
   height:59px;
   display:flex;
   align-items:center;
   background:#fff;
   border-radius:6px; 
}
.b-left{
    height:100%;
    display:flex;
    justify-content:center;
    flex-direction: column;
    padding-left:20px;
}
.b-left img{
    height:14px;
    margin-bottom:5px;
}
.b-right{
    height:60%;
    display:flex;
    border-left:1px solid rgb(238,238,238);
    flex-direction: column;
    justify-content:center;
    padding-left:10px;
}
.b-right a{
    margin-top:10px;
}
</style>