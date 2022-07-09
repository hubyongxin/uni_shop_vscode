<template>
	<view class="icnos">
        <view class="icno_item">
            <img class="icno_item_img" src="../../static/swiper/swiper1.jpg" alt="">
            <text class="icno_item_neme">运动户外</text>
	    </view>
                <view class="icno_item">
            <img class="icno_item_img" src="../../static/swiper/swiper2.jpg" alt="">
            <text class="icno_item_neme">户外</text>
	    </view>
                <view class="icno_item">
            <img class="icno_item_img" src="../../static/swiper/swiper3.jpg" alt="">
            <text class="icno_item_neme">户外</text>
	    </view>
        <view class="icno_item">
            <img class="icno_item_img" src="../../static/swiper/swiper1.jpg" alt="">
            <text class="icno_item_neme">运动户外</text>
	    </view>
        <view class="icno_item">
            <img class="icno_item_img" src="../../static/swiper/swiper2.jpg" alt="">
            <text class="icno_item_neme">运外</text>
	    </view>
        <view class="icno_item">
            <img class="icno_item_img" src="../../static/swiper/swiper1.jpg" alt="">
            <text class="icno_item_neme">运动户外</text>
	    </view>
                <view class="icno_item">
            <img class="icno_item_img" src="../../static/swiper/swiper2.jpg" alt="">
            <text class="icno_item_neme">运动户外</text>
	    </view>
                <view class="icno_item">
            <img class="icno_item_img" src="../../static/swiper/swiper3.jpg" alt="">
            <text class="icno_item_neme">运动户外</text>
	    </view>
	</view>
</template>

<script>
	export default {
        components:{
            
        },
		data() {
			return {
				title: '购物车'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>
<style lang="scss" scoped>
.icnos{
    display: flex;
    flex-wrap: wrap;
}
.icno_item{
    width: 25%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding-top: 20rpx;
}
.icno_item_img{
    width: 75%;
    border-radius: 50%;
}
.icno_item_neme{
    padding-top: 10rpx;
}

</style>


