<!DOCTYPE html>
<html lang="en">
<head>
  <title></title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <link rel="stylesheet" type="text/css" href="aure.css">
  <style>
  @media only screen and (min-width : 800px) {
        .landing p {font-size: 24px;

        }

        .mycontainer img {float:left;padding: 5px;

        }

        .mycontainer p {font-size: 18px;text-align: left;

        }

        .mycontainer img {width:50px;height: 50px;

        }

      }
  @media only screen and (max-width: 800px){

        .max {max-width: 300px;margin: 0 auto;

        }

        .mycontainer p {text-align: center;

        }

  }
  .mycontainer:nth-child(odd) {background-color: #d9d9d9;}
  </style>
</head>
<body>
  <div id="header">
    <nav class="navbar navbar-inverse">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#" style="color:green;">NUNATU</a>
        </div>
        <div class="collapse navbar-collapse" id="myNavbar">
          <ul class="nav navbar-nav">
            <li class="active"><a href="">Home</a></li>
            <li><a href="#">Mission</a></li>
            <li><a href="#">Vision</a></li>
            <li><a href="#">Notre Equipe</a></li>
            <li><a href="mailto:info@nunatu.org">&#9993 info@nunatu.org</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
  <div id="content">
    <div class="landing" style="position:relative;text-align:center;color:white;">
      <picture>
      <source media="(max-width:799px)" srcset="handsclose.jpeg">
      <source media="(min-width:800px)" srcset="hands.jpeg">
        <img src="hands.jpeg" style="display: block;width:100%;height:600px;margin-left:auto;margin-right:auto;margin-top:-20px;">
      </picture>
      <img src="logonuru.pdf" style="max-width:100%;height:200px;position: absolute;top: 25%;left: 50%;transform: translate(-50%, -50%);">
      <p style="position: absolute;top: 70%;left: 50%;transform: translate(-50%, -50%);background: rgb(0, 0, 0);background: rgba(0, 0, 0, 0.5);color: #f1f1f1;padding: 20px;">
      Nous sommes une <strong style="color:green;">initiative priv&eacute;e</strong> impuls&eacute;e par la compassion
      pour les personnes vivant au quotidien une <strong style="color:green;">pr&eacute;carit&eacute;</strong> qui ne
      leur permet pas de r&eacute;pondre &aacute; leurs <strong style="color:green;">besoins humains</strong> les plus
      &eacute;l&eacute;mentaires (physiques, &eacute;conomiques, civils)...</p>
    </div>
    <div class="mycontainer">
      <div class="max" style="width:1000px;margin: 0 auto;">
        <h2 style="text-align:center;">Notre Vision</h2>
        <p style="text-align:center;">Notre vision est de permettre aux enfants, aux jeune et aux femmes d'&ecirc;tre
        des membres valorisés de leur communauté, leur donner les moyens de s'y &eacute;panouir et d'&ecirc;tre des
        acteurs actifs de d&eacute;veloppement par les renforcements de capacit&eacute;, l'entrepreneuriat et les
        initiatives sociales.</p>
      </div>
    </div>
    <div class="mycontainer">
      <div class="max" style="width:1000px;margin: 0 auto;">
        <h2 style="text-align:center;margin-top:30px;padding-top:20px;">Notre Mission</h2>
        <img src="number1.jpg" style="width:30px;height:30px;margin-left:140px;">
        <p>Stimuler le d&eacute;veloppement personnel et la
        r&eacute;lisation de soi. </p>
        <img src="numbertwo.jpg" style="width:30px;height:30px;margin-left:140px;">
        <p>Accompagner chaque personne vuln&eacute;rable &aacute; (re)d&eacute;couvrir son potentiel et sa dignit&eacute;. </p>
        <img src="numbertree.jpg" style="width:30px;height:30px;margin-left:140px;">
        <p>Transformer chaque individu en personne ressource et en acteur de développement de sa soci&eacute;t&eacute;. </p>
        <br>
        <br>
      </div>
    </div>
  </div>
  <div id="footer" style="background-color:#808080;">
    <div class="container">
	     <div class="row-fluid">
         <div class="ubuntu">
           <div class="span8" style="margin-top:2vw;">
           <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2520.6706787534026!2d4.407767515661505!3d50.81873997952778!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c3db33e3fe068d%3A0x640f11f8e5b0172b!2sBoulevard+des+Invalides+183%2C+1160+Auderghem!5e0!3m2!1sfr!2sbe!4v1537985267018" width="100%" height="auto" frameborder="0" style="border:0" allowfullscreen></iframe>
    	    </div>
        </div>

      	<div class="span4" style="color:white;">
    		<h2>Nunatu Asbl</h2>
    		<address>
    			<strong>Nunatu, la compassion en action</strong><br>
    			Boulevard des invalides 183/12<br>
    			1160 Bruxelles<br>
    			Belgique<br>
    			&#9742 +32489 93 95 66<br>
    		</address>
    	</div>
    </div>
  </div>
</div>
</body>
</html>
