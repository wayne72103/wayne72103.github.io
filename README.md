<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Wayne | Grade 11 STEM Student</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: linear-gradient(to right, #dfe9f3, #ffffff);
            color: #333;
        }

        header {
            background-color: #0a3d62;
            padding: 20px;
            text-align: center;
            color: white;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #82ccdd;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        .home {
            background-color: #f1f9ff;
        }

        .card-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            width: 250px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        footer {
            background-color: #0a3d62;
            color: white;
            text-align: center;
            padding: 15px;
        }

        @media(max-width: 768px){
            .card-container{
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Wayne</h1>
    <p>Grade 11 STEM Student</p>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="home">
    <h2>Hello! 👋</h2>
    <p>I am a passionate STEM student who loves science, mathematics, and technology.</p>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am currently a Grade 11 STEM student in the Philippines. 
        I enjoy exploring scientific ideas, conducting research, and solving real-world problems. 
        My goal is to pursue a career in a STEM-related field and contribute to innovation and society.
    </p>
</section>

<section id="skills">
    <h2>My Skills</h2>
    <div class="card-container">
        <div class="card">
            <h3>Academic</h3>
            <p>Mathematics, Research Writing, Critical Thinking</p>
        </div>
        <div class="card">
            <h3>Technical</h3>
            <p>Basic HTML & CSS, Microsoft Office, Google Workspace</p>
        </div>
        <div class="card">
            <h3>Soft Skills</h3>
            <p>Leadership, Teamwork, Communication</p>
        </div>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="card-container">
        <div class="card">
            <h3>Research Project</h3>
            <p>Natural plant-based alternatives for sustainability research.</p>
        </div>
        <div class="card">
            <h3>Upcoming Projects</h3>
            <p>More STEM innovations coming soon!</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Email: yourname@email.com</p>
    <p>GitHub: github.com/wayne72103</p>
</section>

<footer>
    <p>© 2026 Wayne | Grade 11 STEM Student</p>
</footer>

</body>
</html>
