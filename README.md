git add index.html
git commit -m "Update portfolio with LinkedIn About details and new Education section"
git push origin main

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selomie Yohanes Hadera - Portfolio</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; color: #333; }
        header { background-color: #333; color: #fff; padding: 20px; text-align: center; }
        h1 { margin: 0; font-size: 2.5em; }
        nav { background-color: #444; padding: 10px; }
        nav ul { list-style: none; margin: 0; padding: 0; display: flex; justify-content: center; }
        nav li { margin: 0 15px; }
        nav a { color: #fff; text-decoration: none; font-weight: bold; transition: color 0.3s; }
        nav a:hover { color: #ccc; }
        section { padding: 40px 20px; max-width: 1200px; margin: 0 auto; }
        #about { background-color: #fff; text-align: center; }
        #about img { max-width: 200px; border-radius: 50%; margin-bottom: 20px; }
        #education, #skills, #projects, #contact { background-color: #e9e9e9; }
        ul { list-style-type: disc; padding-left: 20px; }
        footer { background-color: #333; color: #fff; text-align: center; padding: 10px; }
        /* Responsive design */
        @media (max-width: 768px) {
            nav ul { flex-direction: column; }
            nav li { margin: 10px 0; }
            h1 { font-size: 2em; }
            section { padding: 20px 10px; }
            #about img { max-width: 150px; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Selomie Yohanes Hadera</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <img src="profile-photo.jpg" alt="Selomie Yohanes Hadera Profile Photo"> <!-- Upload your photo to the repo and rename if needed -->
        <p> Master’s student in Management Science and Engineering | Passionate about Data-Driven Decision Making | Beihang University Scholar</p>
        <p> Currently pursuing a Master’s degree at Beihang University in Beijing, China, with a focus on Business Data Analytics, Operations Research, Supply Chain Management, Operation Management, and Project Management. Dedicated to solving real-world problems by leveraging Advanced AI techniques and scientific methodologies.</p>
        <p> My expertise spans Accounting, programming (Python and R), business data analysis, and optimization techniques. I specialize in applying data-driven approaches to enhance operational efficiency, optimize business operations and projects, and develop models for smarter decision-making.</p>
        <p>Join me in exploring innovative solutions to complex challenges and shaping a data-driven future. Let’s connect!</p>
    </section>
    <section id="education">
        <h2>Education</h2>
        <ul>
            <li><strong>Master’s in Management Science and Engineering</strong> - Beihang University, Beijing, China (Current)</li>
            <!-- Add more education details if available -->
        </ul>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>R</li>
            <li>Accounting</li>
            <li>Business Data Analysis</li>
            <li>Optimization Techniques</li>
            <li>Operations Research</li>
            <li>Supply Chain Management</li>
            <li>Operation Management</li>
            <li>Project Management</li>
            <li>Advanced AI Techniques</li>
            <li>Git & GitHub</li>
            <li>Responsive Design</li>
        </ul>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><strong>Project 1:</strong> A personal blog built with HTML and CSS.</li>
            <li><strong>Project 2:</strong> An interactive portfolio using JavaScript.</li>
            <!-- Add real projects here based on your experience -->
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>📞 Contact me:</p>
        <p>📧 Email: soliyohannes4@gmail.com</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/selomie-yohanes-5012071a2">linkedin.com/in/selomie-yohanes-5012071a2</a></p>
    </section>
    <footer>
        <p>&copy; 2025 Selomie Yohanes Hadera. All rights reserved.</p>
    </footer>
</body>
</html>

