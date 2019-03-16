# mon-CV-en-HTML-et-CSS
<!DOCTYPE html>
<html lang="fr-FR">
	<head>
		<title>contact.html</title>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<link rel="stylesheet" href="style.css">
	</head>
	<style >
		/****GENERAL****/

body{
	font-family: 'Century Gothic', Calibri, serif;
	font-size: 13px;
	margin: 0px;
	padding: 0px;
}
h1{
	font-size: 40px;
	font-weight: normal;
	text-align: center;
}
header{
	height: 100px;
}
footer{
	height: 80px;
	padding-top: 30px;
	text-align: center;
	background-color: #C5C5C5;
	border-top: 2px solid #AAA;
}
nav{
	width: 100%;
	background-color: #424558;
}
nav li{
	list-style-type: none;
	float: left;
}
nav ul{
	margin: 0px;
	padding: 0px;
}
nav a{
	display: inline-block;
	text-decoration: none;
	padding: 20px 30px;
	color: #FFF;
	text-transform: uppercase;
	font-size: 15px;

}
.table{
	display: table;
	margin: 0 auto;
}
.menu-ind:hover{
	border-top: 5px solid #4c8;
	background-color: rgba(64, 200, 130, 0.15);
}
.menu-exp:hover{
	border-top: 5px solid #f1dc4f;
	background-color: rgba(241, 211, 79, 0.15);
}
.menu-hob:hover{
	border-top: 5px solid #0070bb;
	background-color: rgba(000, 112, 192, 0.15);
}
.menu-con:hover{
	border-top: 5px solid #e44d26;
	background-color: rgba(228, 77, 38, 0.15);
}
nav li:hover a{
	padding: 15px 30px 20px 30px;
}
section{
	width: 100%;
	min-height: 600px;
	padding-bottom: 10px;
	margin-bottom: 10px;
}
.nom{
	font-weight: bold;
	color: blue;
}
.sec{
	margin: 0px 10px;
}
.left{
	float: left;
	width: 30%;
	font-weight: bold;
}
.right{
	float: right;
	width: 70%;
}
.sec::after,.exp::afler, {
	content: "";
	display: table;
	clear: both;
}
#presentation{
	border-top: 5px solid #4c8;
	background-color: rgba(64, 200, 130, 0.15);
	min-height: 300px;
}
#parcours{
	border-top: 5px solid #f1dc4f;
	background-color: rgba(241, 211, 79, 0.15);
}
#competences{
	border-top: 5px solid #e44d26;
	background-color: rgba(228, 77, 38, 0.15);
	min-height: 350px;
}
#formations{
	border-top: 5px solid #0070bb;
	background-color: rgba(000, 112, 192, 0.15);
	min-height: 550px;
}
.rouge{
	text-align: center;
	border-top: 5px solid #e44d26;
	background-color: rgba(228, 77, 38, 0.15);
	min-height: 300px;
}
.mail{
	color: blue;
	font-weight: bold;
	text-decoration : underline;
}
.num{
	color: blue;
	font-weight: bold;
}
.loghha{
	color: blue;
	font-weight: bold;
	text-decoration : underline;
}
.prog{
	color: blue;
	font-weight: bold;
	text-decoration : underline;
}
	</style>
	<body>
		<header>
				<h1>EL JAOUDI Abdel Jalil</h1>
		</header>

		<nav>
			<div class="table">
				<ul>
					<li class="menu-ind">
						<a href="index.html">Accueil</a>
					</li>
					<li class="menu-exp">
						<a href="experiences-pro.html">Expériences professionnelles</a>
					</li>
					<li class="menu-hib">
						<a href="hobbies.html">Loisirs</a>
					</li>
					<li class="menu-con">
						<a href="contact.html">Contactez-moi !</a>
					</li>
				</ul>
			</div>
		</nav>
		<section class="rouge">
			<h1>Contactez-moi !</h1>
			<div class="sec">
				<p>Mon profil vous intéresse ?</p>
				<p>N'hésitez pas à me contacter à l'adresse suivante:<br/>
					<span class="mail">khaljaoudi@outlook.fr</span></p>
					<p>mes némuros de téléphone sont les suivants : <br/><span class="num">06 50 95 66 02  /  02 47 51 65 61</span></p>
					<p>Je vous répondrai dans les meilleurs délais !</p>
				
			</div>
		</section>

		<footer>
			<p>Copyright 2019 EL JAOUDI Abdel Jalil -Toute reproduction interdite</p>
		</footer>
	</body>
</html>
