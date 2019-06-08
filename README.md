<!DOC TYPE html>
<html>
<head>
<title>My Website</title>
<meta charset="utf8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" href="style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
<div class="background">
<div class="nav">
<a class="a active" href="#">HOME</a>
<a class="b" href="#">Who am I</a>
<a class="c" href="#">See my Work</a>
<a class="d" href="#">Contact Me</a>  
</div>
<div class="content">
	<div class="home">
	<h1>I am Harshita Batra</h1>
	<h3>Undergraduate</h3>
	</div>
</div>
	<div class="aboutus">
		<p><b>Hello Friends!</b><br>
		I am fourth year undergraduate currently pursuing my Bachelor's in Information Technology from Jaipur Engineering College and Research Centre</p><br>
		<p>I did an internship at Edgistify- An optimal solution to supply chain,Mumbai.</p>
	</div>
	<div class="work">
		<h1>Build my own cloud-</h1><br>
		<p>My Project includes understanding the components and infrastructure of the cloud and working with storage and database services, assessing security risks,private and public cloud management and obtaining cloud storage.</p><br><br>
		<h1>Worked on Wordpress-</h1><br>
		<p>Build company's blog page and integrated it by making changes in the code.</p><br><br>
	</div>
		<div class="contact">
		<a href="#" class="fa fa-facebook"></a><br><br><br><br><br>
		<a href="#" class="fa fa-google"></a><br><br><br><br><br>
		<a href="#" class="fa fa-linkedin"></a><br><br><br><br><br>
		
	</div>  
</div>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script type="text/javascript">
$(document).ready(function(){
	$('a').click(function(){
	var selected = $(this);
	$('a').removeClass('active');
	$(selected).addClass('active');	
});
	var $a = $('.a'),
		$b = $('.b'),
		$c = $('.c'),
		$d = $('.d'),
		$home = $('.home'),
		$aboutus = $('.aboutus'),
		$work = $('.work'),
		$contact = $('.contact')

		$a.click(function(){
			$home.fadeIn();
			$aboutus.fadeOut();
			$work.fadeOut();
			$contact.fadeOut();
		});
		$b.click(function(){
			$aboutus.fadeIn();
			$home.fadeOut();
			$work.fadeOut();
			$contact.fadeOut();
		});
		$c.click(function(){
			$work.fadeIn();
			$home.fadeOut();
			$aboutus.fadeOut();
			$contact.fadeOut();
		});
		$d.click(function(){
			$contact.fadeIn();
			$work.fadeOut();
			$home.fadeOut();
			$aboutus.fadeOut();
		});	


});
</script>
</body>
</html>
