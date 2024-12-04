# Codsoft-task-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunil Karajol- Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Sunil Karajol</h1>
            <p>Web Developer & Designer</p>
            <a href="#contact" class="btn">Get in Touch</a>
        </div>
    </header>

    <!-- Navigation -->
    <nav>
        <ul class="container">
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Main Content -->
    <main>
        <!-- About Section -->
        <section id="about" class="container">
            <div class="about-content">
                <img src="D:\OneDrive\Pictures\Saved Pictures\sk.jpg" alt="">
                <div>
                    <h2>About Me</h2>
                    <p>I am a creative web developer with a strong focus on building responsive, visually appealing user interfaces. My passion lies in creating digital experiences that engage users and deliver results.</p>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="container">
            <h2>Skills</h2>
            <div class="skills-grid">
                <div>HTML</div>
                <div>CSS</div>
                <div>JavaScript</div>
                <div>Python</div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="container">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project">
                    <h3>Online Car Rental System</h3>
                    <p>A responsive web application built using PHP, MySQL, HTML, and CSS for booking cars online.</p>
                    <a href="D:\OneDrive\Pictures\Screenshots\Car rental.jpg" target="_blank">View Project</a>
                </div>
                
            </div>
        </section>

        <!-- Resume Section -->
        <section id="resume" class="container">
            <h2>Resume</h2>
            <a href="D:\OneDrive\sunil resume.pdf" download class="btn">Download Resume</a>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Sunil Karajol. All Rights Reserved.</p>
            <div class="social-links">
                <a href="mailto:sunilskarjol@gmail.com">Email</a>
                <a href="tel:+8310023269">Call</a>
                <a href="https://linkedin.com" target="_blank">LinkedIn</a>
                <a href="https://github.com" target="_blank">GitHub</a>
            </div>
        </div>
    </footer>
</body>
</html>

#CSS CODE
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background: #f9f9f9;
    color: #333;
}

/* Header */
header {
    background: linear-gradient(120deg, #3a1c71, #d76d77, #ffaf7b);
    color: #fff;
    text-align: center;
    padding: 100px 20px;
}

header h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

header .btn {
    background: #fff;
    color: #3a1c71;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background 0.3s ease, color 0.3s ease;
}

header .btn:hover {
    background: #3a1c71;
    color: #fff;
}

/* Navigation */
nav {
    background: #3a1c71;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 15px 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1rem;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Sections */
.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 40px 0;
}

.about-content {
    display: flex;
    align-items: center;
    gap: 20px;
    flex-wrap: wrap;
}

.about-content img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    text-align: center;
}

.skills-grid div {
    background: #3a1c71;
    color: #fff;
    padding: 15px;
    border-radius: 5px;
    font-weight: bold;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

/* Projects */
.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.project {
    background: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    text-align: center;
}

.project h3 {
    color: #3a1c71;
    margin-bottom: 10px;
}

.project a {
    color: #d76d77;
    text-decoration: none;
    font-weight: bold;
}

.project a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    background: #3a1c71;
    color: #fff;
    text-align: center;
    padding: 20px;
}

footer .social-links a {
    color: #ffaf7b;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bold;
}

footer .social-links a:hover {
    text-decoration: underline;
}
