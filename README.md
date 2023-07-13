<!DOCTYPE html>
<html lang="en">
<head>
  <style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    font-size: 16px;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

#banner {
    background-image: url('banner-image.jpg');
    background-size: cover;
    background-position: center;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
}

#banner h2 {
    font-size: 48px;
    color: #fff;
    text-align: center;
    margin-bottom: 20px;
}

#banner p {
    font-size: 24px;
    color: #fff;
    text-align: center;
}

section {
    padding: 50px 0;
}

section h2 {
    font-size: 36px;
    margin-bottom: 20px;
    text-align: center;
}

section p {
    font-size: 18px;
    margin-bottom: 20px;
    text-align: center;
}

section ul {
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
}

section ul li {
    margin-right: 20px;
    font-size: 24px;
    font-weight: bold;
}

.work-item {
    margin-bottom: 50px;
}

.work-item img {
    width: 100%;
    height: auto;
    margin-bottom: 20px;
}

.work-item h3 {
    font-size: 24px;
    margin-bottom: 10px;
}

.work-item p {
    font-size: 18px;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form label {
    font-size: 24px;
    margin-bottom: 10px;
}

form input,
form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: none;
    border-radius: 3px;
}

form button {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 3px;
    font-size: 18px;
    cursor: pointer;
}

form button:hover {
    background-color: #666;
}

.social-media {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
}

.social-media a {
    color: #333;
    margin: 0 10px;
    font-size: 24px;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

footer p {
    font-size: 16px;
}
  </style>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>My Portfolio</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#work">Work</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="banner">
        <div class="container">
            <h2>Welcome to My Portfolio</h2>
            <p>Here you can find my latest projects and experience in web development.</p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hi, I'm John Doe. I'm a web developer with 5 years of experience in front-end development.</p>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>React</li>
            </ul>
        </div>
    </section>

    <section id="work">
        <div class="container">
            <h2>My Work</h2>
            <div class="work-item">
                <img src="work-image-1.jpg" alt="Work Image 1">
                <h3>Project 1</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sed enim vel lectus tincidunt.</p>
            </div>
            <div class="work-item">
                <img src="work-image-2.jpg" alt="Work Image 2">
                <h3>Project 2</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sed enim vel lectus tincidunt.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="message">Message:</label>
                <textarea id="message" name="message"></textarea>
                <button type="submit">Send</button>
            </form>
            <div class="social-media">
                <a href="https://www.linkedin.com/in/johndoe"><i class="fa fa-linkedin"></i></a>
                <a href="https://www.twitter.com/johndoe"><i class="fa fa-twitter"></i></a>
                <a href="https://www.github.com/johndoe"><i class="fa fa-github"></i></a>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 My Portfolio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
