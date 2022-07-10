<template>
    <view style="height:80rpx">
        <view class="touch_bar">
            <scroll-view scroll-x="true" scroll-into-view>
                <view class="touch_bar_item" v-for="item in touchBarList" :key="item.id" @tap="changeBar(item.id)">
                    <text :class="touchBarindex == item.id ? 'active_color' : 'default_color'">{{item.title}}</text> 
                </view>
            </scroll-view>
        </view>
    </view>
</template>

<script>
export default {
    data() {
        return {
            touchBarList:[
                {id:0,title:'运动'},
                {id:1,title:'电器'},
                {id:2,title:'户外'},
                {id:3,title:'测试'},
                {id:4,title:'请问'},
                {id:5,title:'请12问'},
            ],
            touchBarindex:0,

        };
    },
    onLoad() {},
    methods: {
        changeBar:function(val){
            this.touchBarindex = val
        }
    },
};
</script>

<style lang="scss" scoped>
.touch_bar {
    background-color:white;
    position: fixed;
    top: 80rpx;
    width: 100%;
    height: 80rpx;
    line-height: 80rpx;
    z-index: 99;
    white-space: nowrap;
}
.touch_bar_item{
    display: inline-block;
    margin: 0 30rpx;

}
.active_color{
    padding-bottom: 6rpx;
    border-bottom: #67C23A solid 6rpx;
}

</style>
