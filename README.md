# FlyToTheLimitFrontEndDevelopment
This is my final code for my Fly to the Limit web design concept. The website uses HTML,CSS, Javascript and JQuery plugins. 

This is the markup/HTML for the Fly to the Limit Index File

<!DOCTYPE html>
<head>
	<title>Fly to the Limit - Welcome to Fly to the Limit</title>

	<meta charset="UTF-8">
	<meta name="description" content="Fly to the Limit Home Page">
	<meta name="keywords" content="Fly to the Limit, Why Fly to the Limit, Lake Tour, Sunset Tour, 
	Glider Tour, Queenstown, New Zealand">
	<meta name="author" content="Michael Szeto">

	<link rel="stylesheet" type="text/css" href="css/styles.css">
	<link rel="icon" type="image/png" href="img/favicon.ico">
</head>
<body>
	<header>
		<div class="nav">
			<div class="col_4">
				<h1 id="home"><a href="index.html"><b>Fly to the Limit</b></a></h1>
			</div>

			<div class="col_8">
				<ul class="right_nav">				
					<li><a href="html/tours.html">Tours</a></li>
					<li><a href="html/gallery.html">Gallery</a></li> 
					<li><a href="html/booking.html">Book a flight</a></li> 
					<li><a href="html/prices.html">Pricing</a></li>  
					<li><a href="html/about.html">About</a></li>
					<li><a href="html/contact.html">Contact</a></li>
				</ul>
			</div>  
		</div>
	</header>
<div class="top">
</div>
	<div id="parallax_img">
		<div class="wrapper">
			<div class="header_text">
				<div class="img">
					<img src="img/logo.png" alt="Queenstown">
				</div>
				<h1><b>Welcome to Fly to the Limit</b></h1>
				<p class="slogan"><i>We take your adventure to the sky's limits.</i></p>
			</div>
		</div>
	</div>
	<div id="home_content">
		<div class="wrapper">
			<div class="col_12">
				<h3>Why people love us</h3>
				<p><br>When you go on a tour with Fly to the Limit, you really gain a one of a kind experience. Whenever we take our customers to the sky for the first time, we ensure that they are not only getting a valuable customer service, but also getting the best out of a rare occasion most people may not get to experience.</p>

				<p>We continuously ensure our planes are always operating at their best and are always ready to take on larger groups of seven if need be. In our variety of planes we are always doing everything we can to make the tour up high memorable. </p>				
			</div>

			<div class="col_3">
				<div class="img"><img src="img/cloud.png" alt="">
					<h4>In the cloud experiences</h4></div>
				</div>
				<div class="col_3">
					<div class="img"><img src="img/ticked.png" alt="">
						<h4>We tick all the <br>right boxes</h4>
					</div>
				</div>
				<div class="col_3">
					<div class="img"><img src="img/quote.png" alt="">
						<h4>Excellent communication</h4></div>
					</div>
					<div class="col_3">
						<div class="img"><img src="img/camera.png" alt="">
							<h4>Creating unforgetable memories</h4>
						</div>
					</div>	
				</div>
			</div>

			<div class="pale_bg cf">
				<div class="wrapper">
					<div class="col-12">
						<h3>Some popular tours</h3>
					</div>

					<div class="col_4">
						<div class="border_in">
							<a href="html/lake-tour.html">
								<img src="img/tour-2.jpg" alt="Queenstown Lake">
								<span>Lake Tour</span>
							</a>
						</div>	
					</div>

					<div class="col_4">
						<div class="border_in">
							<a href="html/glider-tour.html">
								<img src="img/tour-1.jpg" alt="Nikon D810 Airplane">
								<span>Glider Tour</span>
							</a>
						</div>	
					</div>					

					<div class="col_4">
						<div class="border_in">
							<a href="html/sunset-tour.html">
								<img src="img/tour-3.jpg" alt="Sunset">
								<span>Sunset Tour</span>
							</a>
						</div>
					</div>
					
				</div>
			</div>

			<footer>
				<div id="container">
					<div class="wrapper">
							<div id="copyright" class="col_6">&copy; Copyright 2015. All rights reserved<br> to Fly to the Limit inc.
						</div>
						<div class="col_6"> 				
							<div class="back_to_top_button">Back to top</div>
						</div>
					</div>
				</div>
			</footer>
	  <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
	  <script src="javascript/back-to-top.js"></script>
</body>
</html>
