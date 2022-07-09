<template>
    <view class="recommend">
        <view class="recommend_item">
            <img class="item_big" src="../../static/shangping/4.jpg" alt="">
            <view class="item_small">
                <img class="item" src="../../static/shangping/1.jpg" alt="">
                <img class="item" src="../../static/shangping/2.jpg" alt="">
                <img class="item" src="../../static/shangping/3.jpg" alt="">
            </view>
        </view>
    </view>

</template>
<script>
export default {
    name: 'recommend',
    components: {
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
    mounted () {
    },
    }
</script>
<style lang="scss" scoped>
.recommend{
    padding: 20rpx;
}
.recommend_item{
    display: flex;
    flex-direction: column;
    border-radius: 20rpx;
    border: 2rpx solid #cccccc;
    overflow: hidden;
    margin: 20rpx 0;
}
.item_big{
    width: 100%;
    height: 300rpx;
}
.item_small{
    width: 100%;
    height: 240rpx;
    .item{
        width: 33.33%;
        height: 240rpx;
    }
}

</style>
