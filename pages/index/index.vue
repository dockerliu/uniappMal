<template>
	<view>
		<view class="iconfont icon-VIP">
			首页
		</view>
		<view class="d-flex bg-white border-top position-fixed border bottom-0 left-0 right-0" style=" height: 90upx;">
			<view class="flex-1 d-flex j-center a-center flex-column line-h">
				<view class="iconfont icon-xihuan line-h">
					收藏
				</view>
			</view>
			<view class="flex-1 d-flex j-center a-center flex-column line-h">
				<view class="iconfont icon-gouwuche line-h">
					购物车
				</view>
			</view>
			<view style="flex: 2.5;" class="text-white main-bg-color d-flex j-center a-center" hover-class="main-bg-hover-color">加入购物车</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
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
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
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
