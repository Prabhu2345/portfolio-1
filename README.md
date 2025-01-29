<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background: #333; color: white; padding: 15px; text-align: center; }
        nav { text-align: center; margin: 20px; }
        nav a { margin: 0 15px; text-decoration: none; color: #333; font-weight: bold; }
        section { padding: 20px; text-align: center; }
        .projects { display: flex; justify-content: center; flex-wrap: wrap; }
        .project { margin: 10px; padding: 15px; border: 1px solid #ddd; }
        footer { background: #333; color: white; text-align: center; padding: 10px; position: fixed; width: 100%; bottom: 0; }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate developer skilled in web technologies.</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>Project 1</h3>
                <p>Description of project 1.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>Description of project 2.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: example@example.com</p>
    </section>
    <footer>
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
