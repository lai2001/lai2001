- 👋 Hi, I’m @lai2001
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
lai2001/lai2001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>英雄联盟</title>
		<style>
			*{
				margin:0px;
				padding:0px;
				color:#FFFFFF;
			}
			.header{
				height:100px;
				background-color:#000000;
				background-image:url(img/logo-public.png);
				background-repeat:no-repeat;
				background-position:30px center;
			}
			.item{
				display:inline-block;
				margin-top:25px;
				margin-right:50px;
				text-align:center;
			}
			.mr-left{
				margin-left:250px;
			}
			.search{
				width:26px;
				height:26px;
				background-image: url(img/topfoot-spr.png);
				display: inline-block;
				background-position:-376px -39px;
			}
			.user{
				width:56px;
				height:56px;
				background-image: url(img/topfoot-spr.png);
				display:inline-block;
				background-position:-212px -113px;
			}
			.user-img{
				height:30px;
				width:30px;
				margin:12px;
			}
			.content{
				height:900px;
				background-image:url(img/bg.jpg);
				background-repeat:no-repeat;
				background-size:100% 100%;
				/*数值（长宽）
				百分比（水平 垂直）*/
			} 
			.nav-content{
				/* margin:30px; */
				height:200px;
				/* width:200px; */
				background-color:rgb(0,0,0);
				opacity:.5;
				/*0完全透明 1完全不透明*/
				border-radius:10px 20px 30px 40px;
				/*与margin类似*/
			}
	</style>
	</head>
	<body>
			<div class="header">
			<div class="item mr-left">
				<p>游戏资料</p>
				<p>GAME INFO</p>
			</div>
			<div class="item">
				<p>商城合作</p>
				<p>STORE</p>
			</div>
			<div class="item">
				<p>社区互动</p>
				<p>COMMUNITY</p>
			</div>
			<div class="item">
				<p>赛事官网</p>
				<p>ESPORTS</p>
			</div>
			<div class="item">
					<p>自助系统</p>
					<p>SYSTEM</p>
			</div>
			<div class="search"></div>
			<div class="user">
			<img src="img/default.png" class="user-img"/></div>
			</div>
			<div class="content">
			<div class="nav-content"></div>
			<div class="">
			</div>
		</div>
	</body>
</html>
