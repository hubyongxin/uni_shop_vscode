<template>
	<view class="">
        <Banner></Banner>
	</view>
</template>

<script>
import Banner from '../../components/banner/banner.vue'
	export default {
        components:{
            Banner
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

<style>

</style>
