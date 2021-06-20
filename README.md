<html>
<head>
	<title>
	</title>
	<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Akaya+Telivigala&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha512-SfTiTlX6kk+qitfevl/7LibUOeJWlt9rbyDn92a1DqWOw9vWG2MFoays0sgObmWazO5BQPiFucnnEAjpAB+/Sw==" crossorigin="anonymous" />
</head>

<style type="text/css">
	*{
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		font-family: 'Akaya Telivigala', cursive;
	}
	a{
		text-decoration: none;
		color:white;
	}
	header{
		width: 100%;
		height: 100vh;
		background-color: #4158D0;
        background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
        position: relative;
	}
	header:before{
		content: "";
		width:420px;
		height: 450px;
		position: absolute;
		left: 0;
		bottom: 0;
		background-image: url('bingo.png');
		background-size: 100% 100%;
	}
	nav{
		width: 100%;
		height: 15vh;
		display: flex;
		justify-content: space-around;
		align-items: center;
		position: absolute;
	}
	.logo a{
		font-size: 1.6rem;
		text-transform: uppercase;
	}
	.menu ul li{
		list-style: none;
		display: inline-block;
		padding:  0 15px;

	}
	.menu ul li a{
		text-transform: capitalize;
		}
		.abhay, ul li:hover{
			border-top: 2px solid #5dade2;
			border-bottom: 2px solid #5dade2;
		}
		.contact_btn a{
			background-color: #d465ef;
			padding: 12px 26px;
			font-style: 14px;
			font-weight: 500;
			border: 1px solid transparent;
			text-transform: capitalize;

		}
		.contact_btn a:hover{
			background: linear-gradient(to bottom, #615cfd 0%, #d465ef 100%);
		}
		.center_content{
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
			text-align: center;
		}
		.center_content h1{
			color:#fff;
			font-size: 70px;
			text-transform: capitalize;
			font-weight: 700;
			margin-bottom: 10px;
		}
		.center_content h2{
			font-size: 25px;
			font-weight: 400;
			color:#fff;
			text-transform: capitalize;
		}
		.center_content h2:before{
			content:"";
			width: 65px;
			height: auto;
			border: 2px solid #fff;
			position :absolute;
			left: 40px;
			bottom: 0;
			margin-bottom: 10px;

		} 
		.social_nework{
			width: 100px;
			height: auto;
			top: 40%;
			right: 0; 
			position: absolute;
		}
		.fa_icons{
			width: 40px;
			height: 40px;
			border-radius: 50%;
			background: linear-gradient(to bottom, #615cfd 0%, #d465ef 100%);
			display: flex;
			justify-content: center;
			align-items: center;
		}
		.fa_icons:nth-child(even){
			margin: 20px 0;
		}
		.fa_icons:hover{
			background: linear-gradient(to bottom, #d465ef 0%, #615cfd 100%);
		}





</style>
<body>
	<header>
		<nav class="navi">
			<div class="logo">
				<a href="abhi" target="_blank">abhay patel</a>
			</div>
			<div class="menu">
				<ul>
				<li><a href="f" class="abhay">home</a></li>
				<li><a href="f" >about us</a></li>
				<li><a href="f" >gallary</a></li>
				<li><a href="f" >info</a></li>
			    </ul>
			</div>
			<div class="contact_btn">
				<a href="but">contact us</a>
				
			</div>
		</nav>
		<div class="center_content">
			<h1>Hello this is Abhay</h1>
			<h2>student / leaning new things</h2>
		</div>
		<div class="social_nework">
			<div class="fa_icons">
				<a href="#" target="_blank">
					<i class="fa fa-facebook" aria-hidden="true"></i> 
				</a></div>
				<div class="fa_icons">
				<a href="#" target="_blank">
					<i class="fa fa-instagram" aria-hidden="true"></i>
				</a></div>
				<div class="fa_icons">
				<a href="#" target="_blank">
					<i class="fa fa-twitter" aria-hidden="true"></i>
				</a></div>
				<div class="fa_icons">
				<a href="#" target="_blank">
					<i class="fa fa-whatsapp" aria-hidden="true"></i>
				</a>
				
			</div>
			
		</div>
	</header>
</body>
</html>
