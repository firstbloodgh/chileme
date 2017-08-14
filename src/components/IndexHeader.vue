<template>
	<header class="head">
		<div class="headtop">
			<span>临安市一分利超市...</span>
			<span>中雨32度</span>
		</div>
		<div class="headcen"><input type="text" name="" placeholder="搜索商家、商品" /></div>
		<div class="headbott">
			<a href="javascript">麦乌烧</a>
			<a href="javascript">泡面</a>
			<a href="javascript">饺子</a>
			<a href="javascript">蟹煲</a>
			<a href="javascript">羊肉串</a>
			<a href="javascript">薯条</a>
			<a href="javascript">黄焖鸡</a>
			<a href="javascript">比萨</a>
			<a href="javascript">甜点</a>
			<a href="javascript">麦乌烧</a>
			<a href="javascript">麦乌烧</a>
			<a href="javascript">麦乌烧</a>
			<a href="javascript">麦乌烧</a>
			<a href="javascript">麦乌烧</a>
			<a href="javascript">麦乌烧</a>
		</div>
	</header>
</template>

<script type="text/javascript">
	export default {
		name: "IndexHeader",
		data(){

		}
	}
</script>
<style type="text/css">
	.head{
		height:3.253333rem;
		background-image: linear-gradient(90deg,#0af,#0085ff);
		padding: 0.266667rem 0.373333rem;
	}
	.head .headtop{
		font-size:0.48rem;
		color: #ffffff;
		display: flex;
		align-items: center;
		justify-content: space-between;
		height: 0.92rem;
	}
	.head .headcen{
		padding: 0.2rem 0rem;
	}
	.head .headcen input{
		height: 0.96rem;
		border: 0.0rem;
		border-radius: 0.96rem;
		width: 100%;
		text-align: center;
		font-size: 0.346667rem;
	}
	.head .headbott{
		white-space: nowrap;
		overflow: auto;
	}
	.head .headbott a{
		margin-right: 0.4rem;
		color: #ffffff;
		text-decoration: none;
	}
	.head .headbott a:last-child{
		margin-right: 0rem;
	}
	.head .headbott a:hover{
		color: #ffffff;
		text-decoration: none;
	}
</style>