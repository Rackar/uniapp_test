<template>
	<view>
		<uni-grid  :options="[
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/shu.png',text:'圣诞树'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/lindang.png',text:'铃铛'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/laoren.png',text:'圣诞老人'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/liwu.png',text:'礼物'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/maozi.png',text:'帽子'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/shoutao.png',text:'手套'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/xueqiao.png',text:'雪橇'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/xunlu.png',text:'驯鹿'},
    {image:'https://img-cdn-qiniu.dcloud.net.cn/img/xuehua.png',text:'雪花'}]" ></uni-grid>
	</view>
</template>

<script>
	// import {uniBadge,uniGrid} from '@dcloudio/uni-ui'
	import uniGrid from '@dcloudio/uni-ui/lib/uni-grid/uni-grid.vue'
	export default {
		data() {
			return {
				
			};
		},
		components: {uniGrid}
	}
</script>

<style >

</style>
