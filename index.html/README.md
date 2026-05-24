Stylesheet: [style.css](../style.css)

<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<meta name="description" content="Profile card webpage">
		<title>Ella's Profile Card</title>
		<link rel="stylesheet" href="style.css">
	</head>
	<body>
		<main>
			<section class="profile-card">
				<div class="headline">
					<h1>Ella Bunch</h1>
				</div>
				<div class="text-box">
					<p class="major">Major:</p>
					<p class="role">Illustration</p>
					<p class="bio">Im currently working on improving my graphic novel art skills, I love comic books expecially physical media. My current favorites are Absolute batman, absolute martian manhunter and transformers skybound.</p>
				</div>
				<button class="project-button">Projects</button>
			</section>
			<div class="image-gallery" aria-label="Featured covers">
				<figure>
					<a href="https://en.wikipedia.org/wiki/Absolute_Batman" target="_blank" rel="noopener">
						<img src="https://raw.githubusercontent.com/ellabnch/01-profile-card-html/main/Batman.png" alt="Absolute Batman cover">
					</a>
					<figcaption>Absolute Batman</figcaption>
				</figure>
				<figure>
					<a href="https://en.wikipedia.org/wiki/Transformers_(Skybound_Entertainment)" target="_blank" rel="noopener">
						<img src="https://raw.githubusercontent.com/ellabnch/01-profile-card-html/main/Transformers.png" alt="Transformers Skybound cover">
					</a>
					<figcaption>Transformers Skybound</figcaption>
				</figure>
				<figure>
					<a href="https://en.wikipedia.org/wiki/Absolute_Martian_Manhunter" target="_blank" rel="noopener">
						<img src="https://raw.githubusercontent.com/ellabnch/01-profile-card-html/main/img/Martian.png" alt="Absolute Martian Manhunter cover">
					</a>
					<figcaption>Absolute Martian Manhunter</figcaption>
				</figure>
			</div>

			<footer class="site-footer">
				<div class="footer-content">
					<p>Contact: u1534075@utah.edu &nbsp;|&nbsp; @801-664-4645</p>
				</div>
			</footer>
		</main>
		<script src="script.js" defer></script>
	</body>
</html>