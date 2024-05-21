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
            border-radius: 20%;
            z-index: -1;
        }

        .block1, .block2, .block3, .block4, .block5, .block6, .block7, .block8, .block9, .block10, .block11, .block12, .block13, .block14, .block15, .block16 {
            border: none;
        }

        .block1 {
            background-color: #b2dfdb;
            width: 300px;
            height: 50px;
            top: -100px;
            left: -100px;
        }

        .block2 {
            background-color: #ffccbc;
            width: 200px;
            height: 400px;
            top: 10%;
            left: 10%;
        }

        .block3 {
            background-color: #c5cae9;
            width: 50px;
            height: 300px;
            bottom: -100px;
            right: -100px;
        }

        .block4 {
            background-color: #ffecb3;
            width: 150px;
            height: 150px;
            top: 20%;
            right: 20%;
        }

        .block5 {
            background-color: #e6ee9c;
            width: 200px;
            height: 250px;
            bottom: 20%;
            left: 20%;
        }

        .block6 {
            background-color: #f8bbd0;
            width: 100px;
            height: 200px;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        .block7 {
            background-color: #80cbc4;
            width: 350px;
            height: 100px;
            bottom: 30%;
            right: 30%;
        }

        .block8 {
            background-color: #ffab91;
            width: 250px;
            height: 150px;
            top: 40%;
            right: -100px;
        }

        .block9 {
            background-color: #c5e1a5;
            width: 100px;
            height: 250px;
            bottom: -100px;
            left: 50%;
            transform: translateX(-50%);
        }

        .block10 {
            background-color: #90caf9;
            width: 150px;
            height: 300px;
            top: 10%;
            right: -50px;
        }

        .block11 {
            background-color: #bcaaa4;
            width: 50px;
            height: 200px;
            bottom: 10%;
            left: 10%;
        }

        .block12 {
            background-color: #ffcc80;
            width: 250px;
            height: 100px;
            top: 80%;
            left: -50px;
        }

        .block13 {
            background-color: #ce93d8;
            width: 200px;
            height: 150px;
            bottom: 40%;
            right: 10%;
        }

        .block14 {
            background-color: #9fa8da;
            width: 100px;
            height: 350px;
            top: -50px;
            left: 80%;
        }

        .block15 {
            background-color: #ff8a65;
            width: 150px;
            height: 200px;
            bottom: 80%;
            right: 20%;
        }

        .block16 {
            background-color: #80deea;
            width: 300px;
            height: 80px;
            top: 90%;
            left: 10%;
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
        <div class="block block15"></div>
        <div class="block block16"></div>
    </div>
    <header>
        <h1>Nico Short</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href
