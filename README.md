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
		<article>
			<section id="presentation">
				<h1>Qui suis-je ?</h1>
				<div class="sec">
					<div class="left">
						<img src="imgs/mini_photo_cv.jpg" alt="Ma photo">
					</div>
					<div class="right">
						<p>Je m'appelle <span class="nom">EL JAOUDI Abdel Jalil</span>, j'ai 48 ans et je vis à Tours</p>
						<p>curieux, autodidacte et rigoureux dans l'analyse des problèmes complexes et spécialiste dans la pensée de la complexité.</p>
						<p>actuelement en reconversion professionnelle après un long parcours dans les domaines de la sûreté national(Police national) et de la securité privée</p>
						<p>spécialiste dans le domaine de la sécurité incendie et l'assistance à la personne</p>
					</div>
				</div>
			</section>
			<section id="parcours">
				<h1>parcours et expériences</h1>
				<div class="sec">
					<h2>Expériences professionnelles</h2>
					<div class="exp">
						<div class="left">
							<h3>2005 -2018</h3>
						</div>
						<div class="right">
							<h3>sécurité privée</h3>
							<p>Agent de la sécurité privée et chef d'équipe chez securitas. (Agence de Tours)</p>
							<p>Agent de la sécurité incendie et assistance à la personne</p>
							<p>gestion de l'accueil, interventions sur alarmes (incendie et techniques)</p>
							<p>rondier statique sur un seul site et rondie mobile sur plusieurs sites</p>					
						</div>
						<div class="left">
							<h3>1999 - 2004</h3>
						</div>
						<div class="right">
							<h3>Sûrté national et agent de la Brigade royal au maroc</h3>
						</div>
						<div class="left">
							<h3>1997 - 2018</h3>
						</div>
						<div class="right">
							<h3>chercheur et analyste en Autodidacte</h3>
							<p>J’ai réussi à retracer les différentes Voies de l'évolution de la pensée humaine "depuis la Grèce de l'antiquité jusqu'à la science contemporaine". J'ai créé mon propre système qui représente le monde et l'homme: c'est un système qui rapporte de nouvelles idées susceptibles de réconcilier la physique quantique avec l'astrophysique; ce nouveau système est capable de corriger le langage ordinaire en précisant les définitions des concepts polysémique ; ce système ouvre des voies donnant accès à de nouvelles solutions pour la neuroscience... </p>
						</div>
						<div class="left">
							<h3>depuis 2018</h3>
						</div>
						<div class="right">
							<p>reconversion professionnelle "Orientation vers le Développement web". </p>
						</div>
					</div>
				</div>
			</section>
					
		</article>

		<footer>
			<p>Copyright 2019 EL JAOUDI Abdel Jalil -Toute reproduction interdite</p>
		</footer>
	</body>
</html>
