<template>
	<div @click="alt">{{msg}}</div>
</template>

<script>
	export default {
		data () {
			return {
				msg: '点击我',
				alt:function(){
					alert('你就是个垃圾');
				}
			}
		}
	}

</script>

<style>
	html{
		background:#f0f0f0;
		font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
	}
	div{
		width: 100%;
		font-size: 24px;
		text-align: center;
		margin-top: 150px;
	}
</style>