<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jean Manuel | Portfolio</title>
    <style>
        /* Reset & basic styles */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Arial', sans-serif; line-height: 1.6; color: #333; }
        a { text-decoration: none; color: inherit; }
        section { padding: 60px 20px; }
        h1, h2, h3 { color: #0A3D62; }
        .container { max-width: 1100px; margin: auto; }
        .nav { display: flex; justify-content: space-between; align-items: center; padding: 20px; background: #fff; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 4px rgba(0,0,0,0.1);}
        .nav a { margin-left: 20px; color: #0A3D62; font-weight: bold; }
        .hero { display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; min-height: 80vh; background: #f4f4f4; }
        .btn { display: inline-block; padding: 10px 20px; margin-top: 20px; background: #0A3D62; color: #fff; border-radius: 5px; transition: 0.3s; }
        .btn:hover { background: #062F4A; }
        .skills, .experience, .portfolio { display: flex; flex-wrap: wrap; gap: 20px; }
        .card { background: #fff; padding: 20px; border-radius: 8px; flex: 1 1 300px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);}
        footer { text-align: center; padding: 20px; background: #0A3D62; color: #fff;}
        @media(max-width:768px){ .skills, .experience, .portfolio { flex-direction: column; } }
    </style>
</head>
<body>

<!-- Navigation -->
<nav class="nav container">
    <div class="logo"><strong>Jean Manuel</strong></div>
    <div class="nav-links">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#experience">Experience</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<!-- Hero Section -->
<section class="hero">
    <h1>Jean Manuel</h1>
    <h2>Electrical Engineer | Technical Advisor | Admin & Virtual Assistant</h2>
    <p>📍 Mandaluyong City, Philippines</p>
    <a href="Jean_Manuel_Resume.docx" class="btn">Download Resume</a>
</section>

<!-- About Section -->
<section id="about">
    <div class="container">
        <h2>About Me</h2>
        <p>Results-driven Electrical Engineer and Technical Advisor with 5+ years of experience in design, QA/QC, and administrative support. Skilled in project management, technical advising, and virtual assistance.</p>
    </div>
</section>

<!-- Skills Section -->
<section id="skills" style="background:#f4f4f4;">
    <div class="container">
        <h2>Skills</h2>
        <div class="skills">
            <div class="card">
                <h3>Technical Skills</h3>
                <ul>
                    <li>Electrical Design</li>
                    <li>QA/QC</li>
                    <li>Site Supervision</li>
                    <li>Technical Advising</li>
                </ul>
            </div>
            <div class="card">
                <h3>Admin / VA Skills</h3>
                <ul>
                    <li>Google Suite</li>
                    <li>Microsoft Office</li>
                    <li>Trello, Asana, ClickUp</li>
                    <li>Canva, Slack, Zoom, Skype</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<!-- Experience Section -->
<section id="experience">
    <div class="container">
        <h2>Experience</h2>
        <div class="experience">
            <div class="card">
                <h3>Mitsubishi Hitachi Power Systems Technical Services Corp. | 2019–2023</h3>
                <ul>
                    <li>Electrical SV & Technical Advisor</li>
                    <li>QA/QC</li>
                    <li>Managed technical documentation and ensured compliance with standards</li>
                </ul>
            </div>
            <div class="card">
                <h3>Admin / Virtual Assistant Roles</h3>
                <ul>
                    <li>Collaboration proposals</li>
                    <li>Follow-ups, reminders</li>
                    <li>Meeting coordination</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<!-- Portfolio Section -->
<section id="portfolio" style="background:#f4f4f4;">
    <div class="container">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <div class="card">
                <h3>Confidential Project</h3>
                <p>Handled electrical design and QA/QC for confidential client projects (details withheld).</p>
            <
