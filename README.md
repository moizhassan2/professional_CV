<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional CV -Moiz Hassan Jaffery</title>
        <link rel="stylesheet" href="style.css">
</head>
<style>
/* Global Styles */
body {
    font-family: 'Verdana', 'sans-serif';
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

/* CV Layout */
.cv-container {
    display: flex;
    width: 80%;
    max-width: 1100px;
    margin: 30px auto;
    background: rgb(143, 135, 135);
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    overflow: hidden;
}

/* Sidebar */
.sidebar {
    width: 30%;
    background: #776769;
    color: white;
    padding: 30px;
    text-align: center;
}

.sidebar .profile img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid white;
    object-fit: cover;
}

.sidebar h1 {
    font-size: 22px;
    margin: 10px 0;
}

.sidebar p {
    font-size: 14px;
    opacity: 0.8;
}

.sidebar h2 {
    font-size: 18px;
    margin-top: 20px;
    border-bottom: 1px solid white;
    padding-bottom: 5px;
}

.sidebar ul {
    list-style-type: none;
    padding: 0;
}

.sidebar ul li {
    font-size: 14px;
    padding: 5px 0;
}

.sidebar a {
    color: #1abc9c;
    text-decoration: none;
}

.sidebar a:hover {
    text-decoration: underline;
}

/* Main Content */
.main-content {
    width: 70%;
    padding: 40px;
}

.main-content h2 {
    font-size: 22px;
    color: #2c3e50;
    border-bottom: 2px solid #257436;
    padding-bottom: 5px;
    margin-bottom: 15px;
}

.main-content p {
    font-size: 16px;
    line-height: 1.6;
}

.main-content .job {
    margin-bottom: 20px;
}

.main-content h3 {
    font-size: 18px;
    margin: 5px 0;
}

.main-content ul {
    list-style-type: square;
    padding-left: 20px;
}

@media screen and (max-width: 768px) {
    .cv-container {
        flex-direction: column;
    }
    .sidebar {
        width: 100%;
        padding: 20px;
    }
    .main-content {
        width: 100%;
        padding: 20px;
    }
}

</style>
<body>

    <div class="cv-container">
        <!-- Sidebar Section -->
        <aside class="sidebar">
            <div class="profile">
                <img src="c:\Users\Xmart\Downloads\WhatsApp Image 2025-04-06 at 1.57.34 PM.jpeg" >
                <h1>Moiz Hassan Jaffery</h1>
                <p>Software Engineer | Web Developer</p>
            </div>

            <div class="contact-info">
                <h2>Contact</h2>
                <p>📍 Karachi, Pakistan</p>
                <p>📞 0346-0079778</p>
                <p>✉️ moiz.62224@iqra.edu.pk</p>
                <p>🔗 <a href="#">linkedin.com/in/moizhassanjaffery</a></p>
                <p>🔗 <a href="#">github.com/moizhassanjaffery</a></p>
            </div>

            <div class="skills">
                <h2>Skills</h2>
                <ul>
                    <li>HTML, CSS, JavaScript</li>
                    <li>React.js, Node.js</li>
                    <li>Java, Python</li>
                    <li>SQL, MongoDB</li>
                    <li>Git, Agile Methodologies</li>
                </ul>
            </div>

            <div class="languages">
                <h2>Languages</h2>
                <ul>
                    <li>Urdu (Native)</li>
                    <li>English (Fluent)</li>
                </ul>
            </div>
        </aside>

        <!-- Main Content Section -->
        <main class="main-content">
            <section>
                <h2>About Me</h2>
                <p>I am a dedicated Software Engineer with experience in web and mobile development. Passionate about problem-solving, innovation, and building scalable applications.</p>
            </section>

            <section>
                <h2>Education</h2>
                <p><strong>BS Software Engineering</strong> – IQRA University, Karachi (2022-2025)</p>
            </section>

            <section>
                <h2>Experience</h2>
                <div class="job">
                    <h3>Software Engineer</h3>
                    <p><em>Netsol technologies, Karachi (2023)</em></p>
                    <ul>
                        <li>Developed and maintained web applications using React and Node.js.</li>
                        <li>Worked on REST API integration and backend services.</li>
                    </ul>
                </div>

                <div class="job">
                    <h3>Intern</h3>
                    <p><em>XYZ Technologies, Karachi (Summer 2022)</em></p>
                    <ul>
                        <li>Assisted in developing a mobile app using Flutter.</li>
                        <li>Collaborated with a team of developers to enhance UI/UX.</li>
                    </ul>
                </div>
            </section>

            <section>
                <h2>Projects</h2>
                <ul>
                    <li><strong>Online Voting System</strong> – Developed a secure voting platform.</li>
                    <li><strong>Restaurant Management System</strong> – Designed a customer-friendly ordering system.</li>
                </ul>
            </section>
        </main>
    </div>

</body>
</html>
