<template>
	<view class="content">
		<!-- <image class="logo" src="/static/logo.png"></image> -->
		<view>
			<text class="title">{{title}}</text>
		</view>
		<view>
			<navigator url="/pages/Hr/Staff/index" hover-class="navigator-hover">
				<button type="default">员工管理</button>
			</navigator>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '工作台'
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
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin: 200rpx auto 50rpx auto;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
