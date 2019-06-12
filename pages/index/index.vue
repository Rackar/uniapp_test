<template>
	<view class="content">
		
	<view>
		<text class="title">{{title}}</text>
	</view>
		<image src="../../static/ic_launcher.png" mode=""></image>
		<navigator url="../Map/Map"><button type="primary" plain>浏览地图</button></navigator>
		<navigator url="../productList/productList"><button type="primary" plain>查看图表</button></navigator>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '测试'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		text-align: center;
		height: 400upx;
	}

	.logo {
		height: 200upx;
		width: 200upx;
		margin-top: 200upx;
	}

	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
