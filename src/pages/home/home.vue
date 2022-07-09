<template>
	<view class="">

		<view>
            <!-- <tabbar></tabbar>
            <indexSwiper></indexSwiper>
            <recommend></recommend>
            <recommend></recommend>
            <card></card>
            <sahngpinglist></sahngpinglist> -->
            <Banner></Banner>
            <Icnos></Icnos>
   
 
 
		</view>
	</view>
</template>

<script>
    import tabbar from '../../components/tabbar/tabbar.vue'
    import indexSwiper from '../../components/index/indexSwiper.vue'
    import recommend from '../../components/index/recommend.vue'
    import card from '../../components/common/card.vue'
    import sahngpinglist from '../../components/common/sahngpinglist.vue'
    import Banner from '../../components/banner/banner.vue'
    import Icnos from '../../components/icnos/Icnos.vue'
	export default {
        components:{
            tabbar,indexSwiper,recommend,card,sahngpinglist,Banner,Icnos
        },
		data() {
			return {
				title: 'home'
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
