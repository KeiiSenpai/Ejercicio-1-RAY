# Ejercicio-1-RAY
Primer Ejercicio para RAY
<!DOCTYPE html>
<html>
	<!-- ================================================================================================================ -->
	<!-- Cabeza de una estructura de una página web <head> ... </head> ================================================== -->
	<!--    - Configuración base de nuestra página web y el navegador. 
		    - Enlaces a recursos externos, estilos y scripts     -->
	<head>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0">

		<title>Inicio | RAY 2018</title>
		<meta name="description" content="Contenido, teoría y ejercicios de la asignatura RAY - 2018">
		<meta name="author" content="G.R.P.">

		<!-- Enlaces a archivos externos que definen estilos css -->
		<link href="style/bootstrap.min.css" rel="stylesheet">
		<link href="style/font-awesome.min.css" rel="stylesheet">
		<link href="style/animate.min.css" rel="stylesheet"> 
		<link href="style/lightbox.css" rel="stylesheet"> 
		<link href="style/main.css" rel="stylesheet">
		<link href="style/responsive.css" rel="stylesheet">
		<link href="style/customst.css" rel="stylesheet">

		<!--[if lt IE 9]>
			<script src="js/html5shiv.js"></script>
			<script src="js/respond.min.js"></script>
		<![endif]-->

		<!-- Enlaces a las imágenes a usar como iconos del navegador -->
		<link rel="shortcut icon" href="resources/image/ico/favicon.ico">
		<link rel="apple-touch-icon-precomposed" sizes="144x144" href="resources/image/ico/apple-touch-icon-144-precomposed.png">
		<link rel="apple-touch-icon-precomposed" sizes="114x114" href="resources/image/ico/apple-touch-icon-114-precomposed.png">
		<link rel="apple-touch-icon-precomposed" sizes="72x72" href="resources/image/ico/apple-touch-icon-72-precomposed.png">
		<link rel="apple-touch-icon-precomposed" href="resources/image/ico/apple-touch-icon-57-precomposed.png">

	</head>
	<!-- ================================================================================================================ -->


	<!-- ================================================================================================================ -->
	<!-- Cuerpo de una estructura de una página web <body> ... </body> ================================================== -->
	<!--    - Sección contenedora de todos los elementos renderizables por el navegador. 
		    - Cargas "tardías" de recursos externos -->
	<body>
		<div class="background-image"></div>
		<!-- ================================================================================================================ -->
		<!-- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->
		<header id="header">
			<div class="container">

				<div class="row">
					<div class="col-sm-12 overflow">
						<div class="social-icons pull-right">
							<ul class="nav nav-pills">
								<li><a href="https://www.youtube.com/user/TheWillyrex"><i class="fa fa-facebook"></i></a></li>
								<li><a href="http://pm1.narvii.com/6561/a52c9029a7e76f6dbcd8c0d495f924f64088c366_00.jpg"><i class="fa fa-twitter"></i></a></li>
								<li><a href="https://www.youtube.com/watch?v=nlLqaezOquU"><i class="fa fa-google-plus"></i></a></li>
								<li><a href="https://www.youtube.com/watch?v=Y-qOt6KinYo"><i class="fa fa-dribbble"></i></a></li>
								<li><a href="https://www.youtube.com/watch?v=DYgqNZ349Ow&t=9988s"><i class="fa fa-linkedin"></i></a></li>
							</ul>
						</div> 
					</div>
				</div>

			</div> <!-- div#ray-title.container -->
			<!-- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->
			<div id="cifp_navbar" class="navbar navbar-inverse" role="banner">
				<div class="container">

					<div class="navbar-header">
						<!-- Menú tipo botón expandible para la versión móvil -->
						<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
							<span class="sr-only">Toggle navigation</span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
						</button>
						<!-- Logo y enlace a la página de inicio -->
						<a class="navbar-brand" href="index.html">
							<h1><img src="file:///C:/Users/u_38016571/Downloads/959742997_preview_xvideos_logo.png" alt="logo"></h1>
						</a>
					</div>

					<!-- Barra de navegación -->
					<div class="collapse navbar-collapse">
						<ul class="nav navbar-nav navbar-right">
							<li class="active"><a href="index.html">Inicio</a></li>

							<li class="dropdown"><a href="pages/teoria.html">Abre aqui que vendo jamones de pata negra<i class="fa fa-angle-down"></i></a>
								<ul role="menu" class="sub-menu">
									<li><a href="pages/teoria/tema001.html">Jaja en verdad no</a></li>
								</ul>
							</li>

							<li class="dropdown"><a href="pages/practicas.html">Memingos <i class="fa fa-angle-down"></i></a>
								<ul role="menu" class="sub-menu">
									<li><a href="pages/ejercicios/ejercicio001.html">Ejercicios 1</a></li>
									<li><a href="pages/ejercicios/ejercicio002.html">Ejercicios 2</a></li>
								</ul>
							</li>

							<li class="dropdown"><a href="pages/portfolio.html">Parafarmacia Paco <i class="fa fa-angle-down"></i></a>
								<ul role="menu" class="sub-menu">
									<li><a href="pages/portfolio/galeria.html">Doname tu dinero porque si</a></li>
									<li><a href="pages/portfolio/cv.html ">Poligono industrial ancestral</a></li>
								</ul>
							</li>

							<li class="dropdown"><a href="pages/recursos.html">Recursos <i class="fa fa-angle-down"></i></a>
								<ul role="menu" class="sub-menu">
									<li><a href="pages/recursos/cheetsheet.html ">Plantilla Triangle</a></li>
									<li><a href="pages/recursos/rec-html.html ">HMTL 5</a></li>
									<li><a href="pages/recursos/rec-css.html ">CSS 3</a></li>
									<li><a href="pages/recursos/rec-bootstrap.html ">BootStrap</a></li>
									<li><a href="pages/recursos/rec-javascript.html ">JavaScript</a></li>
									<li><a href="pages/recursos/rec-threejs.html ">Three.js</a></li>
								</ul>
							</li>
						</ul>
					</div>

					<div class="search">
						<form role="form">
							<i class="fa fa-search"></i>
							<div class="field-toggle">
								<input type="text" class="search-form" autocomplete="off" placeholder="Search">
							</div>
						</form>
					</div>

				</div>

			</div> <!-- div#ray-navbar.navbar.navbar-inverse -->

			<!-- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->
		</header>
		<!--/#header - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->
		<!-- ================================================================================================================ -->

		<!-- ================================================================================================================ -->
		<section id="home-slider">
			<div class="container">
				<div class="row">
					<div class="main-slider">
						<div class="slide-text">
							<style>
								
								div.gallery { border: 0px solid #ccc;}
									div.gallery:hover {border: 1px solid #777;}
									div.gallery img {width: 100%;height: auto;}
									div.desc {padding: 15px;text-align: center;}* {box-sizing: border-box;}.responsive {padding: 0 6px;float: left;width: 100%;}
										@media only screen and (max-width: 1024px) {.responsive {width: 49.99999%;margin: 6px 0;}}
										@media only screen and (max-width: 800px) {.responsive {width: 100%;}}.clearfix:after {content: "";display: table;clear: both;}
								</style> 
						
									<div class="responsive">
									<div class="gallery">
                                      <a target="_blank" href="https://img.depor.com/files/article_content_ec_fotos/uploads/2018/09/11/5b9837f23288b.jpeg">
                                        <img src="https://img.depor.com/files/article_content_ec_fotos/uploads/2018/09/11/5b9837f23288b.jpeg" border:0 alt="Khazix" style="width:100%" >
                                      </a>
    								<div class="desc">Los cambios son buenos</div>
    								<audio src="file:///C:/Users/u_38016571/Downloads/Rengar%20Voice%20Spanish%20%20Rengar%20voz%20en%20Espa%C3%B1ol%20-%20League%20of%20Legends.mp3" controls="controls" type="audio/mpeg" preload="preload"></audio>
  									</div>
									</div>
								</div>
								<div class="header">

									<h3>Me gustan los globos</h3>
									<p>Pero sobre todo me gusta el queso rallado </p>
								</div>
											</body>


							

						<img src="file:///D:/Keii/RAY-teoria-1/style/Imagenes/malphite_glacial_skin_render_by_bladeiiii-d5ath95.png" class="slider-hill" alt="slider image">
						<img src="file:///C:/Users/u_38016571/Downloads/Casa%20de%20calamardo.png" class="slider-house" alt="slider image">
						<img src="file:///C:/Users/u_38016571/Documents/unnamed.png" class="slider-sun" alt="slider image">
						<img src="file:///C:/Users/u_38016571/Downloads/275px-Kha'Zix_Render.png" class="slider-birds1" alt="slider image">
						<img src="file:///C:/Users/u_38016571/Downloads/275px-Kha'Zix_Render.png" class="slider-birds2" alt="slider image">
					</div>
				</div>
			</div>
			
		</section>
		<!--/#home-slider-->
		<!-- ================================================================================================================ -->

		<!-- ================================================================================================================ -->
		<footer id="footer">
			<div id="footer-container" class="container">
				
				<div class="row">
					
					<div class="col-md-4 col-sm-6">
						<div class="testimonial bottom">
							<h2>Informate sobre mi ;)</h2>
							<div class="media">
								<div class="pull-left">
									<a href="#"><img src="https://vignette.wikia.nocookie.net/onepiece/images/4/44/Roronoa_Zoro_portrait.png/revision/latest/scale-to-width-down/81?cb=20170115112238&path-prefix=es" alt=""></a>
								</div>
								<div class="media-body">
									<blockquote>A ver, puerto numero 7, solo tengo que acordarme del numero ¿verdad? No es tan dificil. Maldito cocinero estupido tratandome como si fuese un niño (se perdió) </blockquote>
									<h3><a target="_blank" href="http://hcibib.org/tcuid/">- Zoro Roronoa (2008)</a></h3>
								</div>
							</div>
							
						</div> 
					</div>
					<div class="col-md-3 col-sm-6">
						<div class="contact-info bottom">
							<h2>Llamame ;)</h2>
							<address>
							E-mail: <a href="mailto:someone@example.com">adriantorrent4096@gmail.com</a> <br> 
							Teléfono: +34 (627) 184 257 <br> 
							Fax: NONE <br> 
							</address>

							<h2>Visitame ;)</h2>
							<address>
							Calle Pepito Grillo,Avenida Del Ciruelo Maduro, <br> 
							Numero Pi, <br> 
							Esparta, Saturno <br> 
							España <br> 
							</address>
						</div>
					</div>

					<!--
					<div class="col-md-4 col-sm-12">
						<div class="contact-form bottom">
							<h2>Send a message</h2>
							<form id="main-contact-form" name="contact-form" method="post" action="sendemail.php">
								<div class="form-group">
									<input type="text" name="name" class="form-control" required="required" placeholder="Name">
								</div>
								<div class="form-group">
									<input type="email" name="email" class="form-control" required="required" placeholder="Email Id">
								</div>
								<div class="form-group">
									<textarea name="message" id="message" required="required" class="form-control" rows="8" placeholder="Your text here"></textarea>
								</div>
								<div class="form-group">
									<input type="submit" name="submit" class="btn btn-submit" value="Submit">
								</div>
							</form>
						</div>
					</div>
					-->

					<div class="col-sm-12">
						<div class="copyright-text text-center">
							<p>CIFP César Manrique 2018.</p>
							<p>Modificación de la plantilla: <a target="_blank" href="">G.R.P.</a></p>
						</div>
					</div>
				</div>
			</div>
		</footer>
		<!--/#footer-->
		<!-- ================================================================================================================ -->

		<!-- ================================================================================================================ -->
		<!-- Carga "tardía" de librerías de scripts externos -->
		<script type="text/javascript" src="script/jquery.js"></script>
		<script type="text/javascript" src="script/bootstrap.min.js"></script>
		<script type="text/javascript" src="script/lightbox.min.js"></script>
		<script type="text/javascript" src="script/wow.min.js"></script>
		<script type="text/javascript" src="script/main.js"></script>
		<!-- ================================================================================================================ -->
	</body>
	<!-- ================================================================================================================ -->
</html>
