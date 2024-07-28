<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Homepage</title>
    <style>
        /* CSS styles can go here */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        .main {
            float: left;
            width: 70%;
        }
        .sidebar {
            float: left;
            width: 30%;
            background: #f0f0f0;
            padding: 10px;
        }
        .sidebar ul {
            list-style-type: none;
            padding: 0;
        }
        .sidebar ul li {
            padding: 8px;
            margin-bottom: 10px;
            background-color: #ccc;
            color: #333;
        }
        .sidebar ul li:hover {
            background-color: #555;
            color: #fff;
            cursor: pointer;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Homepage</h1>
    </header>
    <div class="container">
        <section class="main">
            <h2>About Me</h2>
            <p>This is where you can introduce yourself and provide some information about who you are.</p>
        </section>
        <aside class="sidebar">
            <h2>Navigation</h2>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </aside>
    </div>
    <footer>
        <p>&copy; 2024 My Homepage. All rights reserved.</p>
    </footer>
</body>
</html>
  </div>
</template>
