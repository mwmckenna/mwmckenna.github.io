mwmckenna.github.io
===================
<!DOCTYPE html>
<head>
	<script src="/assets/jquery.js"></script>
	<link href="style.css" rel="stylesheet">
	<script>
		var image = [
			'http://i.imgur.com/kCL15fa.jpg',
			'http://i.imgur.com/2UyMZpw.jpg?2',
			'http://imgur.com/zK2qzz4',
			]
		var currentimage = 0;

		//Show next image
		var nextimage=function() {
		if (currentimage < image.length){
			currentimage = currentimage + 1;
		}}
		//When button is clicked, show next photo
		$(".next").click(function () {
			$("currentimage").show("nextimage");
			}
		//Show first photo as soon as Javascript loads
		currentimage();

	</script>
</head>
<body>
	<div class="TopRight"><img src="http://i.imgur.com/kCL15fa.jpg"
		<Title>Long Island Sound</Title>
	</div>
<h1>Mary McKenna</h1>
	<div class="AboutMe">about me<br />
		<small> Avid Skier. Passionate Painter. I tried coding for the first time as a senior in college and was surprised at how much fun I had doing it. After graduating from college in 2011,  I worked for a women's apparel start-up where I was occasionally able to use the basic knowledge I learned in my HTML course. When the company closed in 2012, I moved to Jackson Hole where I worked as a Reservations Agent for a vacation rental firm. I have always had a knack for numbers and patterns and I think that I would truly enjoy delving deeper into web development. The idea of creating and improving something that is used on a daily basis strongly appeals to me.</small></p>
		<div class="Mary"><img src="http://i.imgur.com/J9VR78V.png?2"></div>
	</div>
	<div id="Gallery">
		<img id="Photo"
		src='http://i.imgur.com/kCL15fa.jpg'>
	<br />
	<button class="next">next</button>
	</div>
	<div class="contact">
		<p>contact<br />
		<small> email: mwmckenna@gmail.com phone: 203.520.1850</p>
	</div>
	<div class="BottomLeft"><img src="http://i.imgur.com/2UyMZpw.jpg?2"<Title>Jackson Lake</Title>
	</div>
</body>