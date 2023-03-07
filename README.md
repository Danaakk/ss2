
<!DOCTYPE html>
<html>


<head>
	<title>Scrolling Soft 2.0</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
<style>
		nav ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: hidden;
			background-color: #333;
		}

		nav li {
			float: left;
		}

		nav li a {
			display: block;
			color: white;
			text-align: center;
			padding: 14px 16px;
			text-decoration: none;
		}

		nav li a:hover {
			background-color: #111;
		}

html {
  background-image: url('https://cdn.wallpapersafari.com/90/57/BVPWdp.gif');
  background-repeat: no-repeat;
  background-size: cover;
  animation: play-once 1s linear forwards;
}

@keyframes play-once {
  to {
    background-image: none;
  }
}
  </style>
</head>

<body>
	<header>
		<nav>
			<ul>
				<li><a href="#home">Home</a></li>
				<li><a href="#about">What We Do</a></li>
				<li><a href="#services">Services</a></li>
				<li><a href="#contact">Contact</a></li>
                        <li><a href="#Join us">Join us</a></li>
                        <li><a href="#Additional Services">Additional Services</a></li>
                        
			</ul>
		</nav>
	</header>
	<main>
		<section id="home">
			<h1>Welcome to our digital transformation consulting and software development company</h1>
			<img src="scrolling soft image.jpg" alt="Image description">
		</section>
		<section id="about">
			
			<h2>Our team of expert IT consultants is on a mission to help you to stay on the cutting edge of technology and reach your full potential. We're here to revolutionize the way you approach Project Management, Agile Scrum Coaching, Business Functional Analysis, Cybersecurity and more.</h2>


		</section>
		<section id="services">
    <h2>Our Core Services</h2>
    <ul>
        <li>
            <a href="it-consulting-services.html">IT Consulting Services</a>
            <p>Our IT consulting experts are trained to provide solutions tailored to your business's unique needs and we are dedicated to helping you achieve your goals and make the most of the latest technologies.</p>
        </li>
        <li>
            <a href="web-mobile-application-development.html">Web &amp; Mobile Application Development</a>
            <p>Our web and mobile application development services can help you create user-friendly, efficient, and scalable applications that meet your business needs and goals.</p>
        </li>
        <li>
            <a href="artificial-intelligence.html">Artificial Intelligence</a>
            <p>Our artificial intelligence services can help you implement AI technologies in your business operations, allowing you to automate processes, gain insights from data, and make informed decisions.</p>
        </li>
        <li>
            <a href="it-staff-augmentation.html">IT Staff Augmentation</a>
            <p>Our IT staff augmentation services can provide you with the right talent to fill temporary or permanent positions in your organization, helping you to maintain efficiency and productivity.</p>
        </li>
    </ul>
</section>

		<section id="contact">
			<h2>Let's work together to explore new frontiers. Contact Us:</h2>
			<form action="submit-form.php" method="post">
				<label for="name">Name:</label>
				<input type="text" id="name" name="name">
				<label for="email">Email:</label>
				<input type="email" id="email" name="email">
				<label for="message">Message:</label>
				<textarea id="message" name="message"></textarea>
				<input type="submit" value="Submit">
			</form>
                  <h2></h2>
		</section>
	</main>
	<footer>
<footer>
   <img src="scrolling3.jpg" alt="Image description">
   <p>&copy; 2023 Scrolling Soft 2.0. All rights reserved.</p>
	</footer>
</body>
</html>
