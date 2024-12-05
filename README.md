# Deyn.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Your Name</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>Hi, I'm [Your Name]. I'm a web developer, designer, or any profession you like. I specialize in [Your skills]. This is a placeholder text. You can update it later with more information about yourself.</p>
        </div>
    </section>

    <section id="portfolio" class="section">
        <div class="container">
            <h2>My Portfolio</h2>
            <div class="portfolio-gallery">
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/300" alt="Project 1">
                    <p>Project 1</p>
                </div>
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/300" alt="Project 2">
                    <p>Project 2</p>
                </div>
                <div class="portfolio-item">
                    <img src="https://via.placeholder.com/300" alt="Project 3">
                    <p>Project 3</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="#" method="post">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Your Name. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
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

section {
    padding: 60px 0;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.portfolio-gallery {
    display: flex;
    justify-content: space-between;
    gap: 20px;
}

.portfolio-item {
    text-align: center;
}

.portfolio-item img {
    max-width: 100%;
    height: auto;
}

form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

form label {
    font-size: 1.1rem;
}

form input,
form textarea {
    padding: 10px;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1.1rem;
}

form button:hover {
    background-color: #555;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer p {
    font-size: 1rem;
}
