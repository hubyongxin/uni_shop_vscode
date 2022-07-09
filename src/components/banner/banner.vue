<template>
    <view class="banner">
       
        <img class="banner_img" src="../../static/swiper/吴永鑫证件照.jpg" alt="">
       
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
.banner{
    width: 100%;
    height: 300rpx;
}
.banner_img{
    width: 100%;
    height: 300rpx;

}

</style>
