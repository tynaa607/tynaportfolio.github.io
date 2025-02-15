<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="section">
        <h1>Hey There!</h1>
        <p>It's me tyna, welcome to my portfolio.</p>
        <button onclick="scrollToSection('contact')">Contact Me</button>
    </section>

    <section id="about" class="section">
        <h2>About Me</h2>
        <img src="me.jpg" alt="Profile Picture" width="150" height="150" style="border-radius: 50%;">
        <p>Hi everyone, my name is Nur Auni Qistina or Tyna, and I am 19 years old. I am currently pursuing a Diploma in Digital Communication at UiTM Alor Gajah.

            I have a strong passion for media, communication, and digital content creation. My skills include video and photo editing, public speaking, and effective storytelling. I am a confident and hardworking individual who thrives in both independent and team-based environments. I always strive to improve my abilities and take on new challenges with enthusiasm.
             One of my key strengths is my ability to communicate in multiple languages, including Mandarin, which helps me connect with a diverse range of people. I believe that effective communication plays a crucial role in today’s digital era, and I am eager to explore opportunities that allow me to apply my skills in real-world scenarios. Feel free to reach out if you want to chat or collaborate on something exciting. Looking forward to getting to know you! </p>
    </section>

    <section id="portfolio" class="section">
        <h2>My Work</h2>
        <div class="portfolio-gallery">
            <img src="my room.png" alt="Adobe Illustrator Project" width="200">
            <p>Adobe Illustrator Project</p>
            <img src="DSC_0604.JPG" alt="Convocation Shoot" width="200">
            <p>Convocation Photoshoot</p>
            <img src="logo 1.jpg" alt="logo" width="200">
            <p>Cafe Logo Design 1</p>
            <img src="logo2.jpg" alt="logo2" width="200">
            <p>Cafe Logo Design 2</p>
            <img src="pokemon.jpg" alt="pokemon" width="200">
            <p>Character for pixel</p>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Me</h2>
        <div class="contact-container">
            <div class="contact-info">
                <a href="mailto:aunityna24@gmail.com"><img src="email.jpg" alt="Email"> aunityna24@gmail.com</a>
                <a href="tel:+60183944280"><img src="phone.png" alt="Phone"> +60 183944280</a>
                <a href="https://www.instagram.com/aunitynaa?igsh=MWh2cG93NzN3c3Z3Yw==" target="_blank"><img src="instargram.jpg" alt="Instagram"> aunitynaa</a>
                <a href="https://www.tiktok.com/@v4nill4gurl?_t=ZS-8tvYybtMu8N&_r=1" target="_blank"><img src="tiktok.png" alt="Tiktok"> @v4nill4gurl</a>
            </div>
            <div class="contact-form">
                <form>
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" required></textarea>
                    <button type="submit">Send</button>
                </form>
            </div>
        </div>
    </section>

    <script src="portfolio.js"></script>
</body>
</html>
