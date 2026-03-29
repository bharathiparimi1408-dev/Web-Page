#HTML
<!DOCTYPE html>
<html>
<head>
    <title>Bharathi Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Navbar -->
<nav>
    <h2>Bharathi</h2>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- Header -->
<header>
    <h1>Welcome to My Portfolio</h1>
    <p>2nd Year B.Tech Student</p>
</header>

<!-- About Section -->
<section id="about">
    <h2>About Me</h2>
    <p>I am Bharathi, a B.Tech student interested in Python, SQL, and Web Development.</p>
</section>

<!-- Projects Section -->
<section id="projects">
    <h2>My Projects</h2>
    <ul>
        <li>Library Management System (Python + PostgreSQL)</li>
        <li>Portfolio Website (HTML + CSS)</li>
    </ul>
</section>

<!-- Contact Section -->
<section id="contact">
    <h2>Contact</h2>
    <p>Email: bharathiparimi1408@gmail.com</p>
</section>

<!-- Footer -->
<footer>
    <p>© 2026 Bharathi</p>
</footer>

</body>
</html>


#CSS
body {
    font-family: Arial;
    margin: 0;
    padding: 0;
}

/* Navbar */
nav {
    background: #333;
    color: white;
    display: flex;
    justify-content: space-between;
    padding: 15px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 10px;
}

nav a {
    color: white;
    text-decoration: none;
}

/* Header */
header {
    text-align: center;
    padding: 50px;
    background: #4CAF50;
    color: white;
}

/* Sections */
section {
    padding: 20px;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
