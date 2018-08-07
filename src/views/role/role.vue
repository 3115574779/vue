<template>
	<div class="all">
		<header>
			角色管理
		</header>
		<div class="container">
			<div class="container_wrap">
				<div class="c_left">
					<nav>
						<div class="title">
							输入角色名进行查询
						</div>
						<ul>
							<li class="active">默认管理员</li>
							<li>代理商角色</li>
							<li>业务员角色</li>
							<li>业务员角色</li>
							<li>分公司财务</li>
							<li>分公司经理</li>
							<li>大厅经理</li>
							<li>大厅财务</li>
							<li>代理商角色</li>
							<li>业务员角色</li>
							<li>业务员角色</li>
							<li>分公司财务</li>
							<li>分公司经理</li>
							<li>大厅经理</li>
							<li>大厅财务</li>
						</ul>
					</nav>
				</div>
				<div class="c_right">
					<h3>默认管理员</h3>
				</div>
			</div>
		</div>
	</div>
</template>
<script>
</script>

<style lang="scss">
	* {
		margin: 0;
		padding: 0;
		list-style: none;
	}
	
	.all {
		header {
			width: 100%;
			height: 60px;
			background: #fafafa;
			color: #757575;
			padding-left: 10px;
			line-height: 60px;
		}
	}
	
	.container {
		width: 100%;
		padding-left:22px;
		margin-top:10px;	
		margin-bottom:30px;	
		.container_wrap{
			padding-left:10px;		
		.c_left {
			width:202px;			
			float: left;		
			
			border:1px solid #ddd;
			nav{
				color:#91908c;
				ul{
					.active{
						background:#d1d2d7;
						color:#7d8587;
					}
					li{
						height:32px;
						line-height:32px;
						padding-left:10px;
					}
				}
				.title{
					text-align:center;
					line-height:32px;					
				}
		}
			}			
		.c_right {
			float: left;
			color:#525157;			
		}
		}
	}
</style>