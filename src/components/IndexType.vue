<template>
	<div class="types">
		<div class="type" v-for = "nav in navs">
			<a :href="nav.url">
				<img :src="nav.imgurl">
				<p>{{nav.title}}</p>
			</a>
		</div>

		<div id="icolb"></div>
	</div>
</template>

<script type="text/javascript">
	export default{
		name: "IndexType",
		data(){
			return {
				navs:[
					{title:'美食' , imgurl : '/static/img/meishi.png' , url : 'javascript'},
					{title:'甜品饮品' , imgurl : '/static/img/tianpin.png' , url : 'javascript'},
					{title:'商超便利' , imgurl : '/static/img/shangchao.png' , url : 'javascript'},
					{title:'预订早餐' , imgurl : '/static/img/zaocan.png' , url : 'javascript'},
					{title:'果蔬生鲜' , imgurl : '/static/img/guoshu.png' , url : 'javascript'},
					{title:'大牌满减' , imgurl : '/static/img/dapai.png' , url : 'javascript'},
					{title:'准时达' , imgurl : '/static/img/zunshida.png' , url : 'javascript'},
					{title:'浪漫鲜花' , imgurl : '/static/img/langman.png' , url : 'javascript'},
				]
			}
		}
	}
</script>

<style type="text/css">
	.types{
		height: 4.72rem;
		background-color: #ffffff;
	}
	.type{
		height: 1.717333rem;
		width: 25%;
		float: left;
		text-align: center;
		margin-top:0.293333rem;
	}
	.type p{
		margin-top: 0.133333rem;
	}
	.type img{
		width: 1.2rem;
		height: 1.2rem;
	}
	#icolb{
		clear: both;
		width: 100%;
		height: 0.384rem;
	}
</style>