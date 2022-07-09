<template>
    <view class="">
        <shangping></shangping>
    </view>

</template>
<script>
import shangping from './shangping'
export default {
    name: 'card',
    components:{
        shangping
    },
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


</style>
