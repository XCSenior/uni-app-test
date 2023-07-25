<template>
	<view>
		<h1>当前页面不存在</h1>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {
			/* 希望两秒钟以后跳回首页 */
			setTimeout(() => {
				uni.navigateTo({
					url: '/pages/index/index',
				})
			}, 2000);
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
