<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zeeshan Ramzan | Full-Stack Developer</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: #0f172a;
            color: #e5e7eb;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(135deg, #1e293b, #020617);
        }

        header h1 {
            font-size: 2.8rem;
            font-weight: 700;
            color: #38bdf8;
        }

        header p {
            margin-top: 10px;
            font-size: 1.2rem;
            color: #cbd5f5;
        }

        section {
            padding: 60px 10%;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #38bdf8;
        }

        .about p {
            max-width: 800px;
        }

        .skills, .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: #020617;
            padding: 20px;
            border-radius: 12px;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(56,189,248,0.2);
        }

        .card i {
            font-size: 2rem;
            color: #38bdf8;
            margin-bottom: 10px;
        }

        .projects a {
            color: #38bdf8;
            text-decoration: none;
            font-weight: 500;
        }

        footer {
            text-align: center;
            padding: 30px;
            background: #020617;
        }

        footer a {
            color: #38bdf8;
            margin: 0 10px;
            font-size: 1.3rem;
        }

        footer p {
            margin-top: 15px;
            font-size: 0.9rem;
            color: #94a3b8;
        }
    </style>
</head>
<body>

<header>
    <h1>Zeeshan Ramzan</h1>
    <p>Full-Stack Web Developer | Frontend & Backend Specialist</p>
</header>

<section class="about">
    <h2>About Me</h2>
    <p>
        I am a passionate Full-Stack Web Developer with experience in building
        responsive, modern, and scalable web applications. I enjoy turning ideas
        into real products using clean and efficient code.
    </p>
</section>

<section>
    <h2>Tech Stack</h2>
    <div class="skills">
        <div class="card"><i class="fa-brands fa-html5"></i><p>HTML5</p></div>
        <div class="card"><i class="fa-brands fa-css3-alt"></i><p>CSS3</p></div>
        <div class="card"><i class="fa-brands fa-bootstrap"></i><p>Bootstrap</p></div>
        <div class="card"><i class="fa-brands fa-js"></i><p>JavaScript</p></div>
        <div class="card"><i class="fa-brands fa-react"></i><p>React JS</p></div>
        <div class="card"><i class="fa-brands fa-php"></i><p>PHP</p></div>
        <div class="card"><i class="fa-solid fa-database"></i><p>MySQL</p></div>
        <div class="card"><i class="fa-brands fa-git-alt"></i><p>Git & GitHub</p></div>
    </div>
</section>

<section>
    <h2>Featured Projects</h2>
    <div class="projects">
        <div class="card">
            <h3>Eventify (Full Stack)</h3>
            <a href="https://github.com/zees123-svg/Eventify" target="_blank">View Project</a>
        </div>
        <div class="card">
            <h3>React E-Learning</h3>
            <a href="https://github.com/zees123-svg/E-Learning-React-Project" target="_blank">View Project</a>
        </div>
        <div class="card">
            <h3>Netflix UI Clone</h3>
            <a href="https://github.com/zees123-svg/Netflix-F.E-Project" target="_blank">View Project</a>
        </div>
        <div class="card">
            <h3>Tic Tac Toe Game</h3>
            <a href="https://github.com/zees123-svg/tic-tac-toe-project" target="_blank">View Project</a>
        </div>
    </div>
</section>

<footer>
    <a href="mailto:versatilezeeshan1708@gmail.com"><i class="fa-solid fa-envelope"></i></a>
    <a href="https://wa.me/923216850363" target="_blank"><i class="fa-brands fa-whatsapp"></i></a>
    <a href="https://github.com/zees123-svg" target="_blank"><i class="fa-brands fa-github"></i></a>

    <p>© 2026 Zeeshan Ramzan | All Rights Reserved</p>
</footer>

</body>
</html>
