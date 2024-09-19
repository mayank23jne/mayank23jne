<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Layout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1c1c1c;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        .profile-container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        .profile-header {
            display: flex;
            align-items: center;
        }
        .profile-pic img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-right: 20px;
        }
        .profile-info {
            max-width: 500px;
        }
        .profile-info h1 {
            margin: 0;
        }
        .achievements {
            margin-top: 10px;
        }
        .skills-container {
            margin-top: 30px;
        }
        .skills-section {
            margin-bottom: 20px;
        }
        .skills-section h2 {
            margin-bottom: 10px;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 10px;
        }
        .skill {
            background-color: #444;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="profile-container">
        <div class="profile-header">
            <div class="profile-pic">
                <img src="profile.jpg" alt="Profile Picture">
            </div>
            <div class="profile-info">
                <h1>Luis Naveda</h1>
                <p>I have over 7 years of extensive experience in website development, specializing in ASP.NET MVC, MERN Stack, and Mobile applications.</p>
                <div class="achievements">
                    <p>Achievements: 🏆 GraphQL Expert</p>
                </div>
            </div>
        </div>

        <div class="skills-container">
            <div class="skills-section">
                <h2>Languages</h2>
                <div class="skills-grid">
                    <div class="skill">C Programming</div>
                    <div class="skill">C#</div>
                    <div class="skill">Java</div>
                    <div class="skill">JavaScript</div>
                    <div class="skill">HTML</div>
                    <div class="skill">CSS</div>
                    <div class="skill">TypeScript</div>
                    <div class="skill">Python</div>
                </div>
            </div>

            <div class="skills-section">
                <h2>Frontend</h2>
                <div class="skills-grid">
                    <div class="skill">Angular</div>
                    <div class="skill">Babel</div>
                    <div class="skill">Bulma</div>
                    <div class="skill">GatsbyJS</div>
                    <div class="skill">ReactJS</div>
                    <div class="skill">Redux</div>
                    <div class="skill">JQuery</div>
                    <div class="skill">Webpack</div>
                    <div class="skill">Vue</div>
                    <div class="skill">NextJS</div>
                </div>
            </div>

            <div class="skills-section">
                <h2>Backend</h2>
                <div class="skills-grid">
                    <div class="skill">Node.js</div>
                    <div class="skill">D3.js</div>
                    <div class="skill">Express</div>
                    <div class="skill">Spring IOC</div>
                    <div class="skill">Spring Boot</div>
                    <div class="skill">GraphQL</div>
                    <div class="skill">NestJS</div>
                    <div class="skill">Nginx</div>
                </div>
            </div>

            <div class="skills-section">
                <h2>Database</h2>
                <div class="skills-grid">
                    <div class="skill">PostgreSQL</div>
                    <div class="skill">Redis</div>
                    <div class="skill">SQLite</div>
                    <div class="skill">MongoDB</div>
                    <div class="skill">MySQL</div>
                </div>
            </div>

            <div class="skills-section">
                <h2>Cloud & Hosting</h2>
                <div class="skills-grid">
                    <div class="skill">Azure</div>
                    <div class="skill">Firebase</div>
                    <div class="skill">Netlify</div>
                    <div class="skill">Heroku</div>
                </div>
            </div>

            <div class="skills-section">
                <h2>Version Control & CI/CD</h2>
                <div class="skills-grid">
                    <div class="skill">Git</div>
                    <div class="skill">GitHub</div>
                    <div class="skill">Docker</div>
                    <div class="skill">Jenkins</div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
