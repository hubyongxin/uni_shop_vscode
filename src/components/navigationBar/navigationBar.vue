<template>
    <view style="height:80rpx">
        <view class="nav_bar">
            <view class="title">
                小鑫商城
            </view>
        </view>
    </view>
</template>

<script>
export default {
    data() {
        return {
            
        };
    },
    onLoad() {},
    methods: {},
};
</script>

<style lang="scss" scoped>
.nav_bar {
    // display: flex;
    // justify-content: center;
    // align-items: center;
    background-color:wheat;
    position: fixed;
    width: 100%;
    height: 80rpx;
    line-height: 80rpx;
    text-align: center;
    z-index: 99;
    
}
.title{
    font-size: 36rpx;
    font-weight: bold;
}
</style>
