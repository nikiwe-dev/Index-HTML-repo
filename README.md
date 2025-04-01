# Index-HTML-repo

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nikiwe Nzimela - Portfolio</title>
     
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            display: flex;
            justify-content: space-between;
            padding: 10px 20px;
            background: #333;
            color: white;
            align-items: center;
        }
        .logo {
            font-size: 20px;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
        }
        .hero {
            background: #f4f4f4;
            padding: 50px;
            height: 300px;
        }
        .about {
            display: flex;
            justify-content: space-around;
            padding: 50px;
        }
        .about .text {
            width: 50%;
        }
        .about .image img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
        }
        footer {
            background: #333;
            color: white;
            padding: 20px;
        }
        .map {
            margin-top: 10px;
            padding: 10px;
            background: #555;
        }
        .content {
            display: none;
        }
        .active {
            display: block;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Nikiwe Nzimela</div>
        <nav>
            <ul>
                <li><a href="#" onclick="showPage('home')">Home</a></li>
                <li><a href="#" onclick="showPage('about')">About Me</a></li>
                <li><a href="#" onclick="showPage('contact')">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="content active">
        <div class="hero">
            <h2>Welcome to My Portfolio!</h2>
            <p>Your go-to source for my work and journey. </p>
            <h2>BIO</H2>
           <P> Nikiwe Nzimela is an aspiring front end developer with strong foundation in bcom law and data analysis.With coding experience from SheCodes and Coursera ,Nikiwe crafts responsive web applications that blend design with funationality. A natural problem solver , leverages her analytical skills to create seamless digital experiences. </p>
        </div>
    </section>
    <section id="about" class="content">
        <div class="about">
            <div class="text">
                <h2>About Me</h2>
               
                <p><strong>Nikiwe Nzimela:</strong></p><p>I'm Nikiwe Nzimela ,a tech enthusiast with background in Bcom Law and data an alysis. I combine analytical thinking with creative problem solving to build intuitive , user friendly experiences. Lets Create Something Great Together !</p>
                <p>An aspiring front-end developer with a strong foundation in BCom law and data analysis. With coding experience from SheCodes and Coursera, Nikiwe specializes in crafting responsive web applications that blend design with functionality. A natural problem solver, she leverages her analytical skills to create seamless digital experiences. Passionate about technology and continuous learning.</p>
            </div>
            <div class="image">
                <img src="https://via.placeholder.com/200" alt="Your Image">
            </div>
        </div>
    </section>
    <section id="contact" class="content">
        <h2>Contact Me</h2>
        <p> Email: nzimelanikiwe25@gmail.com</p>
        <p>Phone: 0631885957</p>
        <p>Follow me on:</p>
        <div class="social-links">
            <a href="https://instagram.com">Instagram</a>
            <a href="https://facebook.com">Facebook</a>
            <a href="https://tiktok.com">TikTok</a>
        </div>
    </section>
    <footer>
        <p>Address: 779 Tsoaing Street, Chiawelo</p>
        <div class="map">Nzimelanikiwe25@gmail.com</div>
    </footer>
    <script>
        function showPage(pageId) {
            document.querySelectorAll('.content').forEach(section => {
                section.classList.remove('active');
            });
            document.getElementById(pageId).classList.add('active');
        }
    </script>
</body>
</
