<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdulrahman Alnahari - Resume</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h1>Abdulrahman Alnahari</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is Abdulrahman Ahmed Alnahari.</p>
        <p>I am a 21-year-old cybersecurity student at the University of Jeddah, with a passion for digital security and a desire to expand my knowledge.</p>
    </section>

    <section id="education" style="display: flex; align-items: flex-start;">
        <div style="flex: 1;">
            <h2>Education</h2>
            <ul>
                <li>Bachelor's Degree in Cybersecurity, University of Jeddah</li>
                <li>Degree: 4.70</li>
                <li>Started: 2022</li>
                <li>Expected Graduation: 2026</li>
            </ul>
        </div>
        <div style="flex: 1; text-align: center;">
            <img src="certificate.png" alt="Certificate of Achievement" style="max-width: 80%; height: auto; border: 1px solid #ddd; border-radius: 5px;">
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div>
            <h3>Employee Record Management System</h3>
            <p>This project, built with Java, manages employee records using a linked list. It supports insertion, deletion, updates, and salary management.</p>
            <a href="data_structures_project.pdf" target="_blank">View Project PDF</a>
        </div>
        <div>
            <h3>Project PowerPoint</h3>
            <p>Project about Direct and Physical Social Engineering.</p>
            <p>This is a PowerPoint presentation summarizing the key aspects of my project.</p>
            <a href="Project_powerpoint.pptx" target="_blank">View PowerPoint Presentation</a>
        </div>
    </section>

    <section id="contact" style="padding-bottom: 60px;">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:abbdulrahman7404@gmail.com">abbdulrahman7404@gmail.com</a></p>
        <p>Phone: <a href="tel:+966550790442">+966 55 079 0442</a></p>

        <h3>Send Me a Message</h3>
        <form action="#" method="post" style="display: flex; flex-direction: column; width: 300px; margin: auto;">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit" style="margin-top: 10px;">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Abdulrahman Alnahari. All rights reserved.</p>
    </footer>
</body>
</html>
