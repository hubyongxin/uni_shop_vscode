<template>
    <view class="card">
        <view class="item">
            <view class="item_title">- {{title}} -</view>
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
.card{
    display: flex;
    justify-content: center;
    align-items: center;

}
.item_title{
    font-size: 32rpx;
    font-weight: 600;
    
}

</style>
