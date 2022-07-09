<template>
    <view>
        <swiper
            indicator-dots
            autoplay
            circular
            class="swiper">
            <swiper-item>
                <img src="../../static/swiper/swiper1.jpg" alt="">
            </swiper-item>
            <swiper-item>
                <img src="../../static/swiper/swiper2.jpg" alt="">
            </swiper-item>
            <swiper-item>
                <img src="../../static/swiper/swiper3.jpg" alt="">
            </swiper-item>
        </swiper>
    </view>
</template>

<script>
export default {
    data() {
        return {
            title: 'Hello1',
        };
    },
    onLoad() {},
    methods: {},
};
</script>

<style lang="scss" scoped>
.swiper{
    width: 100%;
    height: 400rpx;
}
img{
    width: 100%;
    height: 400rpx;
}
</style>
