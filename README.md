# semaine3

Exercice 1 :
Voici le lien vers l'ensemble de mes badges Codecademy : https://www.codecademy.com/fr/users/datiche36/achievements  


Exercice 2 :  
<!DOCTYPE html>
<html>
	<head>
		<link type="text/css" rel="stylesheet" href="stylesheet.css"/>
		<title></title>
	</head>
	<body>
		<div id="header">
			<p id="name">Kévin DATICHE</p>
			<a href="mailto:you@yourdomain.com"><p id="email">kevin_datiche@hotmail.fr</p></a>
		</div>
		<div class="left"></div>
		<div class="right">
			<h4>Objectif</h4>
			<p>Devenir developpeur grâce à la formation de Simplon.</p>
			<h4>Expérience</h4>
			<ul>
				<li>negociateur immobilier à l'immobilière GUIGNARD</li>
				<li>technicien de relevé de dégradation des autoroutes de France à VECTRA</li>
			</ul>
			<h4>Compétences</h4>
			<ul>
			    <li>Plutôt doué avec l'informatique</li>
			    <li>Connaissances dans l'ingéniérie routière</li>
			</ul>
			<h4>Scolarité</h4>
			<ul>
			    <li>Bac STG option communication</li>
				<li>BTS Professions Immobilières (école de commerce)</li>
			</ul>
		</div>
		<div id="footer">
			<p>2 B Heurtebise, Buzançais, 36500 France | Tel: 06 73 02 25 67</p>
		</div>
	</body>
</html>  

div {
	border-radius: 5px;
}

#header {
	z-index: 1;
	position: fixed;
	width: 97.5%;
	margin-top: -20px;
	height: 60px;
	background-color: #668284;
	margin-bottom: 10px;
}

#name {
	float:left;
	margin-left: 5px;
	padding-top: 5px;
	font-size: 16px;
	font-family: Verdana, sans-serif;
	color: #ffffff;
}

#email{
	float:right;
	margin-right: 5px;
	padding-top: 5px;
	font-size: 16px;
	font-family: Verdana, sans-serif;
	color: #ffffff;
}

h4 {
	margin-left: 5px;
	margin-bottom: 15px;
	font-family: Verdana, sans-serif;
}

.right p {
	margin-left: 5px;
	margin-right: 5px;
	margin-top: -10px;
	font-family: Garamond, serif;
	color: #000000;
}

li {
	list-style-type: square;
}

a:hover {
	font-weight: bold;
}

.left {
	position: relative;
	float: left;
	margin-top: 50px;
	width: 10%;
	height: 400px;
	background-color: #B9D7D9;
	margin-bottom: 10px;
}

.right {
	position: relative;
	float: right;
	margin-top: 50px;
	width: 88%;
	height: 400px;
	background-color: #F4EBC3;
	margin-bottom: 10px;
}

#footer {
	position: relative;
	height: 50px;
	background-color: #668284;
	clear: both;
	font-family: Verdana, sans-serif;
	font-size: 14px;
	text-align: center;
	color: #cfffff;
}

#footer p {
	position: relative;
	padding-top: 15px;
}
