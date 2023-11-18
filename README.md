HTML:

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>FashionReps</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<link rel="icon" href="img/logos.png" type="image/x-icon">
</head>
<body>
	<div class="main">
		<div class="header">
			<h1 class="logo"><b>Fashion_Reps</b></h1>
			<img class="logos" src="img/logos.png">
			<img class="user" src="img/mystic.jpg">
			<a class="reg" href="register.html">register</a>
			<div class="stripeee"></div>
			<div class="stripeee1"></div>
			<div class="stripeee2"></div>
			<div class="stripeee3"></div>
			<div class="stripeee4"></div>
		</div>
		<div class="recomendations">
			<form class="example" action="action_page.php">
  			<input type="text" placeholder="Search..." name="search">
  			<button type="submit"><i class="fa fa-search"></i></button></form>
  			<p class="other">WOMEN MEN KID ARRIVALS EXPLORE SUPPORT</p>
  			<h1 class="recs">Recommendations for you</h1>
  			<img class="track2" src="img/track2.png">
  			<p class="traack2">Balenciaga Track 2.0 (140$)</p>
  			<ul class="traack22">
  				<li>Sizes: 38-45(EU), 7-12 (US)</li>
  				<li>8 Different Colorways</li>
  				<li>Material: Polyester</li>
  				<li>Demiseason</li>
  			</ul>
  			<img class="xl1" src="img/3xl1.png">
  			<img class="xl2" src="img/3xl2.png">
  			<p class="xl3">Balenciaga 3XL (110$)<br></p>
  			<ul class="xl4">
  				<li>Sizes: 38-45(EU), 7-12 (US)</li>
  				<li>4 Different Colorways</li>
  				<li>Material: 50% Rubber, 50% Textile</li>
  				<li>Season: Late Spring, Summer</li>
  			</ul>
  			<img class="vetmo" src="img/vetmo.png">
  			<p class="v3tmo"><b>VETEMENTS</b> Hooded Racing Jacket (200$)</p>
  			<ul class="v1tmo">
  				<li>Sizes: S, M, L, XL</li>
  				<li>Color: Black and Navy</li>
  				<li>Material: 25% Nylon, 50% Cotton, 25% Polyester</li>
  				<li>Demiseason</li>
  			</ul>
  			<img class="chrome" src="img/chrome.png">
  			<p class="chromes">Chrome Hearts Jeans (80$)</p>
  			<ul class="chr0me">
  				<li>Sizes: S, M, L, XL</li>
  				<li>7 Different Colorways</li>
  				<li>Material: 91% Cotton, 7% Elastane, 2% Rubber</li>
  				<li>Demiseason</li>
  			</ul>
  			<img class="margiela" src="img/margiela.jpg">
  			<p class="margiela1"><b>M</b>aison <b>M</b>argiela Kiss Shirt (50$)</p>
  			<ul class="margiela2">
  				<li>Sizes: S, M, L, XL</li>
  				<li>Color: White</li>
  				<li>Material: 100% Cotton</li>
  				<li>Demiseason</li>
  			</ul>
  			<img class="ricks" src="img/ricks.png">
  			<img class="ricks1" src="img/ricks1.png">
  			<p class="ricks2">Rick Owens <b>DRKSHDW</b> Ramones Low (100$)</p>
  			<ul class="ricks3">
  				<li>Sizes: 40-44(EU), 9-12 (US)</li>
  				<li>Color: Black</li>
  				<li>Material: 50% Cotton, 25% Pulyurethane, 25% Viscose</li>
  				<li>Demiseason</li>
  			</ul>
		</div>
		<div class="footer">
			<p class="clientt">CLIENT SERVICES</p>
			<ul class="client">
				<li>FAQ</li>
				<li>Track Order</li>
				<li>Returns</li>
				<li>Shipping</li>
				<li>Payment</li>
			</ul>
			<p class="company">ABOUT COMPANY</p>
			<ul class="companyy">
				<li>Careers</li>
				<li>Legal</li>
				<li>Privacy Policy and Cookies</li>
				<li>Shipping</li>
				<li>Cookies Settings</li>
			</ul>
			<p class="contact">CONTACTS</p>
			<ul class="contactt">
				<li>Facebook</li>
				<li>TikTok</li>
				<li>Instagram</li>
				<li>Telegram</li>
			</ul>
			<p class="boutiques">BOUTIQUES</p>
			<ul class="boutiquess">
				<li>Store appointment</li>
				<li>Find a store nearby</li>
				<li>Country / Region: Ukraine / Europe</li>
				<li>Language: English</li>
			</ul>
			<div class="stripeee5"></div>
			<div class="stripeee6"></div>
			<div class="stripeee7"></div>
		</div>
	</div>

</body>
</html>

CSS:

.main {
	position: relative;
	width:1080px;
	height:2120px;
	border:1px solid black;
	margin:0 auto;
	background: white;
}
.header {
	height:100px;
	width:100%;
	border:1px solid black;
	background-color: white;
}
.logo {
	font-family: 'Montserrat', sans-serif;
	width:130px;
	bottom:10px;
	position:relative;
	margin-left:380px;
	letter-spacing: 4px;
	font-size: 35pt;
}
.user {
	width:80px;
	height:80px;
	margin-left:985px;
	bottom:195px;
	position: relative;
}
.reg {
	font-family: 'Montserrat', sans-serif;
	margin-left:92.9%;
	bottom:210px;
	position: relative;
	font-size:10pt;
	height:20px;
	text-decoration:none;
}
* {box-sizing: border-box}

.container {
  padding: 16px;
}

input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}

hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}

.registerbtn {
  background-color: #4CAF50;
  color: white;
  padding: 16px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

.registerbtn:hover {
  opacity:1;
}

a {
  color: dodgerblue;
}
.signin {
  background-color: #f1f1f1;
  text-align: center;
}
form.example input[type=text] {
  padding: 10px;
  font-size: 17px;
  border: 1px solid grey;
  float: left;
  width: 80%;
  background: #f1f1f1;
}

form.example button {
  float: left;
  width: 20%;
  padding: 10px;
  background: #2196F3;
  color: white;
  font-size: 17px;
  border: 1px solid grey;
  border-left: none;
  cursor: pointer;
  position: relative;
  top:5px;
}

form.example button:hover {
  background: white;
}

form.example::after {
  content: "";
  clear: both;
  display: table;
}
.recs {
	margin-left:350px;
	position: relative;
	font-family: 'Montserrat', sans-serif;
	width:430px;
	margin-top:70px;
}
.track2 {
	width:450px;
	height:200px;
	margin-left:50px;
	margin-top:50px;
}
.traack2 {
	margin-left:180px;
	font-family: 'Montserrat', sans-serif;
	margin-top:-40px;
}
.traack22 {
	margin-left:40px;
	margin-top:20px;
	font-family: 'Montserrat', sans-serif;
	line-height: 30px;
}
.xl1 {
	width:200px;
	height:110px;
	margin-left:55%;
	position: relative;
	bottom: 315px;
}
.xl2 {
	width:220px;
	height:130px;
	margin-left:75%;
	position: relative;
	bottom: 445px;
	z-index:0; 
}
.xl3 {
	font-family: 'Montserrat', sans-serif;
	margin-left:68%;
	margin-top:-420px;
}
.xl4 {
	margin-left:55%;
	margin-top:0px;
	font-family: 'Montserrat', sans-serif;
	line-height: 30px;
}
.vetmo {
	height:300px;
	margin-top:70px;
	margin-left:150px;
}
.v3tmo {
	font-family: 'Montserrat', sans-serif;
	margin-left: 112px;
}
.v1tmo {
	margin-left:40px;
	margin-top:40px;
	font-family: 'Montserrat', sans-serif;
	line-height: 30px;
}
.chrome {
	height:350px;
	margin-left:68%;
	position: relative;
	bottom:540px;
}
.chromes {
	margin-left:66%;
	position: relative;
	bottom:565px;
	font-family: 'Montserrat', sans-serif;
}
.chr0me {
	margin-left:55%;
	bottom:540px;
	font-family: 'Montserrat', sans-serif;
	line-height: 30px;
	position: relative;
}
.stripeee {
	width:1px;
	height:1600px;
	margin-left: 550px;
	position: relative;
	background: black;
	bottom:80px;
	margin-top:84px;
}
.stripeee1 {
	width:348px;
	height:1px;
	position: relative;
	background: black;
	bottom:1700px;
}
.stripeee2 {
	width:298px;
	height:1px;
	position: relative;
	background: black;
	bottom:1700px;
	margin-left: 780px;
}
body {
	background:url(../img/ke.jpg);
}
.logos {
	width:80px;
	height:80px;
	bottom:110px;
	position: relative;
	margin-left:20px;
}
.margiela {
	position: relative;
	bottom:500px;
	width:300px;
	height:300px;
	margin-left: 130px;
}
.margiela1 {
	margin-left:14%;
	position: relative;
	bottom:505px;
	font-family: 'Montserrat', sans-serif;
}
.margiela2 {
	margin-left:5%;
	bottom:480px;
	font-family: 'Montserrat', sans-serif;
	line-height: 30px;
	position: relative;
}
.ricks {
	width:280px;
	height:150px;
	position: relative;
	margin-left:63%;
	bottom:1000px;
}
.ricks1 {
	width:280px;
	height:150px;
	position: relative;
	margin-left:63%;
	bottom:1000px;
}
.ricks2 {
	margin-left:59%;
	position: relative;
	bottom:995px;
	font-family: 'Montserrat', sans-serif;
}
.ricks3 {
	margin-left:55%;
	bottom:975px;
	font-family: 'Montserrat', sans-serif;
	line-height: 30px;
	position: relative;
}
.footer {
	width:1079px;
	height:100px;
	border-top:1px solid black;
	bottom:915px;
	position: relative;
}
.other {
	word-spacing: 30px;
	margin-left:28%;
	font-family: 'Montserrat', sans-serif;
	bottom:10px;
	position: relative;
}
.stripeee3 {
	width:1080px;
	height:1px;
	background: black;
	position: relative;
	bottom:1790px;
	right:2px;
}
.stripeee4 {
	width:1080px;
	height:1px;
	background: black;
	position: relative;
	bottom:1830px;
	right: 2px;
}
.client {
	font-family: 'Montserrat', sans-serif;
	position: relative;
	margin-left:20px;
	font-size:12pt;
	top:10px;
}
.clientt {
	font-family: 'Montserrat', sans-serif;
	position: relative;
	margin-left: 40px;
	top:10px;
}
.company {
	font-family: 'Montserrat', sans-serif;
	position: relative;
	margin-left:240px;
	bottom:138px;
}
.companyy {
	font-family: 'Montserrat', sans-serif;
	position: relative;
	margin-left:220px;
	bottom:138px;
}
.contact {
	font-family: 'Montserrat', sans-serif;
	position: relative;
	margin-left:540px;
	bottom:285px;
}
.contactt {
	font-family: 'Montserrat', sans-serif;
	position: relative;
	margin-left:520px;
	bottom:285px;
}
.boutiques {
	font-family: 'Montserrat', sans-serif;
	position: relative;
	margin-left:740px;
	bottom:414px;
}
.boutiquess {
	font-family: 'Montserrat', sans-serif;
	position: relative;
	margin-left:720px;
	bottom:414px;
}
.stripee5 {
	width:1px;
	height:195px;
	background: black;
	position: relative;
	bottom:565px;
	margin-left: 210px;
}
.stripee6 {
	width:1px;
	height:200px;
	background: black;
	position: relative;
	bottom:765px;
	margin-left: 510px;
}
body {
	background: url(../img/dasa.png);
}
.shit {
	height:800px;
	width:1730px;
	background:white;
	margin:0 auto;
}
