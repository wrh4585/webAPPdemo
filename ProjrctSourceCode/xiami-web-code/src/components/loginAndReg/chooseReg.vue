<template>
	<div>
		<div id="choseReg">
			<h1>注册虾米</h1>
			<ul>
				<li class="choose_lis">
					<span class="choose_span">手机号/邮箱</span>	<input id="userId_r" type="text" value="">
				</li>
				<li class="choose_lis">
					<span class="choose_span">输入密码</span><input id="userPass_r" type="password" value="">
				</li>
				<!--<li class="choose_lis">-->
				<!--<span class="choose_span">确认密码</span><input id="userPass_re" type="password" value="">-->
				<!--</li>-->
			</ul>
			<input type="button" value="注   册" id="regBtn01">
		</div>
	</div>
</template>

<script>
	export default {
		name: "chooseReg"
	}
</script>

<style scoped>
	#choseReg h1{
		font-size: .33rem;
		color: #ffffff;
		font-weight: 100;
		margin-top: .3rem;
	}
	.choose_lis{
		display: block;
		height: .35rem;
		margin-top: .2rem;
		display: -webkit-flex;
		justify-content: space-between;
		align-items: center;
	}
	.choose_span{
		display: block;
		height: .35rem;
		font-size: .2rem;
		line-height: .35rem ;
		color: #cccccc;
	}
	.choose_lis input{
		display: block;
		height: .3rem;
		width:2.0rem ;
		margin-right: .1rem;
		background-color: rgba(0,0,0, .1);
		border:none;
		color: #cccccc;
		font-size: .18px;
		text-indent: .05rem;
	}
	 #regBtn01{
		display: block;
		width: 3.2rem;
		height: .48rem;
		background-color:#5055644f;
		border: 1px solid #4b5a85;
		outline: none;
		border-radius: .1rem;
		font-size: .15rem;
		color: #ffffff;
		margin: .45rem auto 0;
	}
</style>