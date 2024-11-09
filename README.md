<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        .project {
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        a {
            color: #333;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>My Portfolio</h1>
    <p>Welcome to my personal portfolio website!</p>
</header>

<div class="container">
    <section>
        <h2>About Me</h2>
        <p>Hello! I'm a web developer with a passion for creating beautiful and functional websites. I love coding and learning new technologies.</p>
    </section>

    <section>
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of project 1. <a href="#">View Project</a></p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of project 2. <a href="#">View Project</a></p>
        </div>
        <div class="project">
            <h3>Project 3</h3>
            <p>Description of project 3. <a href="#">View Project</a></p>
        </div>
    </section>

    <section>
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Node.js</li>
        </ul>
    </section>

    <section>
        <h2>Contact Me</h2>
        <p>If you'd like to get in touch, feel free to reach out via email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
    </section>
</div>

<footer>
    <p>&copy; 2023 My Portfolio</p>
</footer>

</body>
</html>
