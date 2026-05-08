<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Binalonan</title>

<style>

li a {
    display: block;
    padding: 10px;
}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f5f5f5;
    color: #222;
}

header {
    background: #f3efe6;
    padding: 15px 40px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    display: flex;
    list-style: none;
    gap: 25px;
}

nav a {
    text-decoration: none;
    color: #333;
}

.login-btn {
    background: #1f6f5d;
    color: white;
    padding: 8px 18px;
    border-radius: 20px;
    border: none;
}

.hero {
    height: 80vh;
    background: url('474148563_939584034993399_1830678561438388496_n.jpg') center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
    position: relative;
}

.hero::after {
    content: "";
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.3);
}

.hero-content {
    position: relative;
    z-index: 2;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.search-box {
    margin-top: 20px;
}

.search-box input {
    padding: 12px;
    width: 250px;
    border-radius: 20px;
    border: none;
}

.search-box button {
    padding: 12px 20px;
    border-radius: 20px;
    border: none;
    background: #1f6f5d;
    color: white;
}

/* FEATURES */
.features {
    background: white;
    margin: -40px auto 40px;
    width: 80%;
    padding: 20px;
    border-radius: 40px;
    display: flex;
    justify-content: space-around;
    box-shadow: 0 5px 20px rgba(0,0,0,0.1);
}

.features div {
    text-align: center;
}

.property {
    width: 80%;
    margin: auto;
    margin-bottom: 50px;
}

.property-top {
    display: flex;
    gap: 20px;
    font-size: 30px;;
}

.property-top img {
    width: 50%;
    border-radius: 15px;
}

.property-info {
    flex: 1;
}

.gallery {
    display: flex;
    gap: 15px;
    margin-top: 15px;
}

.gallery img {
    width: 100%;
    height: 250px;        
    object-fit: cover; 
    border-radius: 15px;
}

/* HIGHLIGHT */
.highlight {
    width: 80%;
    margin: auto;
    display: flex;
    gap: 30px;
    align-items: center;
    margin-bottom: 60px;
}

.highlight img {
    width: 50%;
    border-radius: 15px;
}

.highlight button {
    margin-top: 15px;
    padding: 10px 20px;
    border-radius: 20px;
    background: #1f6f5d;
    color: white;
    border: none;
}
.hero {
     width: 80%;
    margin: auto;
    margin-bottom: 50px;
}

.hero-video {
    width: 50%;
    border-radius: 15px;
}

.hero-content {
     flex: 1;
}
.about-title h1 {
      font-size: 2.5rem;
      color: #1f6f5d;
      margin-bottom: 10px;
}
/* FOOTER */
footer {
    background: #1f6f5d;
    color: white;
    text-align: center;
    padding: 20px;
}
</style>

</head>

<body>

<header>
    <nav>
        <h2>Binalonan Ang Galing!</h2>
        <ul>
            <li><a href="Home.html">Home</a></li>
            <li><a href="Attrations.html">Attraction</a></li>
            <li><a href="About.html">About</a></li>

        </ul>
        <a href="Profile.html">Profile</a>
        <a href="Login.html" class="login-btn">Login</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Welcome to Binalonan</h1>
        <p>Discover the unique of Binalonan</p>
</section>

<section class="features">
    <div>Come and enjoy the tour while youre in the binalonan</div>
</section>

<section class="property">
    <div class="property-top">
        <video autoplay muted loop playsinline class="hero-video">
        <source src="AQN-QAOIy8bfb7pnUGIwoXhTnw1ONTPj_4AOFLXIyOLoZB8Mp5HdTTY39C6H2Ra8N3JxHt402LzQ2Zn1dArirF9wyMNhtWOhBmhqsCFsbQ.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <div class="hero-content">
            <h2>Binalonan</h2>
            <p>Binalonan is a first-class municipality in the province of Pangasinan, Philippines. It is located in the eastern part of the province, about 51 kilometers from Lingayen and 190 kilometers from Manila. Binalonan is known for its rich history and culture, as well as its natural beauty. The municipality is home to the Sto. Nino Church, which was built in 1841. Binalonan is also known for its century-old acacia trees, which are a natural heritage.</p>
        </div>
    </div>

    <div class="gallery">
        <img src="671941893_1659074781803183_5691286557846648703_n.jpg">
        <img src="672579648_2443679442719490_404897053223261624_n.jpg">
        <img src="BIN_7474-1080x675.jpg">
    </div>
</section>

<section class="highlight">
    <img src="294380383_2384496355031018_5846108178235146437_n-1.jpg">
    <div>
        <h2>Explore the beauty of Binalonan</h2>
        <p>Theres have a something that use didnt know that it has.</p>
        <button>Our Blog</button>
    </div>
</section>

<footer>
    <p>© 2026 Binalonan Ang Galing</p>
</footer>

</body>
</html>
