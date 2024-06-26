<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nico Short's Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
            position: relative;
        }

        header {
            background-color: #e0e0e0;
            padding: 20px;
            text-align: center;
            position: relative;
            z-index: 1;
        }

        header h1 {
            margin: 0;
            color: #4a4a4a;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #d0d0d0;
            padding: 10px;
            position: relative;
            z-index: 1;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #666;
        }

        nav a:hover {
            color: #000;
        }

        section {
            padding: 20px;
            position: relative;
            z-index: 1;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #e0e0e0;
            position: relative;
            z-index: 1;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            position: relative;
            z-index: 1;
        }

        .background-blocks {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
        }

        .block {
            position: absolute;
            width: 250px;
            height: 400px;
            border-radius: 20%;
            z-index: -1;
            border: none; /* removed white borders */
        }

        .block1 {
            background-color: #b2dfdb;
            top: -100px;
            left: -100px;
        }

        .block2 {
            background-color: #ffccbc;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        .block3 {
            background-color: #c5cae9;
            bottom: -100px;
            right: -100px;
        }

        .block4 {
            background-color: #ffecb3;
            top: 10%;
            right: 10%;
            width: 300px;
        }

        .block5 {
            background-color: #e6ee9c;
            bottom: 20%;
            left: 20%;
            width: 300px;
        }

        .block6 {
            background-color: #f8bbd0;
            top: 70%;
            left: 10%;
        }

        .block7 {
            background-color: #80cbc4;
            bottom: 60%;
            right: 20%;
        }

        .block8 {
            background-color: #ffd180;
            top: 40%;
            left: 40%;
            width: 400px;
        }

        .block9 {
            background-color: #b39ddb;
            bottom: 10%;
            right: 5%;
            height: 300px;
        }

        .block10 {
            background-color: #90caf9;
            top: 80%;
            left: 80%;
            height: 300px;
        }

        .block11 {
            background-color: #ffab91;
            bottom: 30%;
            right: 30%;
            width: 350px;
        }

        .block12 {
            background-color: #80deea;
            top: 20%;
            left: 70%;
            width: 200px;
        }

        .block13 {
            background-color: #e0e0e0;
            bottom: 50%;
            right: 70%;
        }

        .block14 {
            background-color: #c5e1a5;
            top: 90%;
            left: 20%;
        }
    </style>
</head>
<body>
    <div class="background-blocks">
        <div class="block block1"></div>
        <div class="block block2"></div>
        <div class="block block3"></div>
        <div class="block block4"></div>
        <div class="block block5"></div>
        <div class="block block6"></div>
        <div class="block block7"></div>
        <div class="block block8"></div>
        <div class="block block9"></div>
        <div class="block block10"></div>
        <div class="block block11"></div>
        <div class="block block12"></div>
        <div class="block block13"></div>
        <div class="block block14"></div>
    </div>
    <header>
        <h1>Nico Short</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! My name is Nico Short. Welcome to my personal webpage. Here you can learn more about my projects and how to get in touch with me.</p>
        </div>
    </section>
    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <p>Here are some of the projects I've worked on:</p>
            <ul>
                <li><strong>Project 1:</strong> Description of project 1.</li>
                <li><strong>Project 2:</strong> Description of project 2.</li>
                <li><strong>Project 3:</strong> Description of project 3.</li>
            </ul>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <p>If you'd like to get in touch, please contact me at:</p>
            <p class="muted-text">email@example.com</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Nico Short</p>
    </footer>
</body>
</html>
