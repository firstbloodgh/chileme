<template>
	<footer class="footers">
		<div class="index-footer">
			<div class="in-f-b">
				<svg class="index-footerTabIcon_1EbB8wS">
					<use xlink:href="#index.18edf5a"></use>
				</svg>
				<span>外卖</span>
			</div>
			<div class="in-f-b">
				<svg class="index-footerTabIcon_1EbB8wS">
					<use xlink:href="#discover-regular.8ef537f"></use>
				</svg>
				<span>发现</span>
			</div>
			<div class="in-f-b">
				<svg class="index-footerTabIcon_1EbB8wS">
					<use xlink:href="#order-regular.41c17f8"></use>
				</svg>
				<span>订单</span>
			</div>
			<div class="in-f-b">
				<svg class="index-footerTabIcon_1EbB8wS">
					<use xlink:href="#profile-regular.c151d62"></use>
				</svg>
				<span>我的</span>
			</div>
		</div>
	</footer>
</template>

<style type="text/css">
.footers{
	height: 1.6rem;
}
.index-footer{
	border-top: 0.026667rem solid #eee;
	width: 100%;
	height: 1.6rem;
	background-color: #fff;
	position: fixed;
	bottom: 0;
	display: flex;
	justify-content: space-around;
	align-items: center;
}
.index-footer svg{
	width: 0.533333rem;
	height: 0.533333rem;
}
.index-footer .in-f-b{
	height: 70%;
	display: flex;
	flex-direction: column;
	justify-content: space-around;
	text-align: center;
}
.index-footer .in-f-b span{
	font-size: 0.24rem;
}
</style>