<template>
    <view class="shangping">
        <view class="shangping_item">
            <img class="shangping_item_img" src="../../static/swiper/吴永鑫证件照.jpg" alt="">
            <view class="shangping_item_desc">吴永鑫dh的设计费世纪东方VS就大V束带结发去我带我去恶趣味阿萨德</view>
            <view class="price">
                <text class="pprice">￥299</text>
                <text class="oprice">￥599</text>
            </view>
            <text class="discount">{{(299/599*10).toFixed(1)}}折</text>
        </view>
    </view>

</template>
<script>
export default {
    name: 'card',
    props:{
        title:{
            type:String,
            default:'猜你喜欢'
        }
    },
    data () {
        return {
        }
    },
    computed: {
    },
    watch: {
    },
    methods: {
    },
    onLoad() {

    },
    }
</script>
<style lang="scss" scoped>
.shangping{
    display: flex;
    flex-wrap: wrap;
}
.shangping_item{
    width: 375rpx;
    padding-bottom: 20rpx;
    text-align: center;
}
.shangping_item_img{

    // width: 100%;
    height: 375rpx;

}
.shangping_item_desc{

   padding: 10rpx 20rpx 0 20rpx;
   display: -webkit-box;
   -webkit-box-orient: vertical;
   -webkit-line-clamp: 2;
   overflow: hidden;
}
.price{
    padding: 10rpx 0 ;
    .pprice{
        font-size: 32rpx;
    }
    .oprice{
        color: gray;
        padding: 0 10rpx;
        text-decoration:line-through;

    }
}
.discount{
    color: red;
    border: 2rpx solid red;
    border-radius: 10rpx;
    padding:0 4rpx;
}


</style>
