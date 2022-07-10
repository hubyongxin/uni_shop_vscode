<template>
	<view class="">
        <navigation-bar></navigation-bar>
        <touch-bar></touch-bar>
        <indexSwiper></indexSwiper>
	</view>
</template>

<script>
import navigationBar from '../../components/navigationBar/navigationBar.vue'
import touchBar from '../../components/touchBar/touchBar.vue'
import indexSwiper from '../../components/swipers/indexSwiper.vue'

	export default {
        components:{
            indexSwiper,navigationBar,touchBar
        },
		data() {
			return {
				
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
