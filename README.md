<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rita Youssef - Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: url('./data/light_purple_gradient_background.jpg') no-repeat center center fixed;
            overflow-x: hidden;
            color: #5d45a0;
        }
        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 20px 40px;
            background: rgba(0, 0, 0, 0.2);
            color: #5d45a0;
        }
        header img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            border: 2px solid white;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            gap: 20px;     
        }
        nav a {
            text-decoration: none;
            color: #5d45a0;
            font-size: 2em;
            transition: opacity 0.3s;
        }
        nav a:hover {
            opacity: 0.7;
            color: #5d45a0;
        }
        .visitor-count {
            text-align: center;
            margin: 20px 0;
        }
        .visitor-count p {
            font-size: 1.2em;
        }
        .main {
            max-width: 1200px;
            margin: 40px auto;
            padding: 40px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
            color: #5d45a0;
        }
        .top-content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            align-items: flex-start;
            color: #5d45a0;
        }
        .about-me, .profile {
            flex: 1;
            min-width: 300px;
            color: #5d45a0;
        }
        .about-me h2 {
            font-size: 1.8em;
            margin-bottom: 10px;
            color: #5d45a0;
        }
        .about-me p {
            line-height: 1.8;
            font-size: 1.1em;
            color: #5d45a0;
        }
        .about-me a {
            color: #a6d4fa;
            text-decoration: none;
            color: #5d45a0;
        }
        .about-me a:hover {
            text-decoration: underline;
            color: #5d45a0;
        }
        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
            border: 2px solid white;
        }
        .profile h2 {
            margin: 0;
            font-size: 1.5em;
        }
        .details h2 {
            font-size: 1.8em;
            color: #5d45a0;
            margin-bottom: 10px;
        }
        .details ul {
            list-style: none;
            color: #5d45a0;
            padding: 0;
        }
        .details ul li {
            padding: 5px 0;
            font-size: 1.1em;
            color: #5d45a0;
        }
        .buttons {
            margin-top: 30px;           
        }
        .buttons a {
            display: inline-block;
            text-decoration: none;
            color: #5d45a0;
            background: white;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .buttons a:hover {
            background: #a6d4fa;
        }
        .stats-container {
            background: rgba(255, 255, 255, 0.2);
            color: #5d45a0;
            padding: 20px;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.3);
            font-size: 2em;
            color: #5d45a0;
        }
        footer a {
            color: #a6d4fa;
            text-decoration: none;
            color: #5d45a0;
        }
        footer a:hover {
            text-decoration: underline;
            color: #5d45a0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rita Youssef</h1>
        <img src="./data/profile.jpg" alt="Rita's Profile Picture">
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#education">Education</a>
            <a href="#stats">Stats</a>
        </nav>
    </header>
    <div class="visitor-count">
        <p><strong>Visitor Count</strong>  </p>
        <img src="https://profile-counter.glitch.me/ritayoussef/count.svg" alt="Visitor's Count" />
    </div>
    <div class="main">
        <div class="top-content">
            <div class="about-me" id="about">
                <h2>About Me</h2>
                <p>
                    📝 I love integrating my aesthetics and creativity into computer science projects.<br>
                    🎮 I have been a gamer since I was 6 years old.<br>
                    🎡 Fun fact: I still play Claw on my PC 🖥️.<br>
                    🌐 I'm currently creating my own website and developing a game using JavaScript.<br>
                    📚 I'm currently learning <strong>React.js</strong>.<br>
                    🚀 I will start my first internship in <strong>January 2025</strong> as a Web Developer.<br>
                    💬 Ask me about <strong>JavaScript, HTML/CSS, C#, SQL, Kotlin, Python</strong>, and more
                    <a href="https://github.com/ritayoussef/ritayoussef/issues" target="_blank">here</a>.<br>
                </p>
            </div>
            <div class="profile">
                <img src="./data/profile.jpg" alt="Profile Picture">
                <h2>Computer Science Student 👩🏽‍💻</h2>
            </div>
        </div>
        <div class="details">
            <section id="skills">
                <h2> 📝 Skills</h2>
                <ul>
                    <li>JavaScript</li>
                    <li>TypeScript</li>
                    <li>HTML/CSS</li>
                    <li>SQL</li>
                    <li>C#</li>
                    <li>Kotlin</li>
                    <li>Agile/Scrum</li>
                    <li>Jira</li>
                    <li>Visual Studio</li>
                    <li>VS Code</li>
                    <li>PyCharm</li>
                    <li>Android Studio</li>
                </ul>
            </section>
            <section id="education">
                <h2> 📚 Education</h2>
                <p>DEC in Computer Science 🖥️ - expected May 2025 👩🏽‍🎓 </p>
            </section>

<section id="stats" class="stats-container">
   <h2> ⚡️ Stats </h2> 

<br>

<div align=center>
  <img width=390 src="https://github-readme-stats.vercel.app/api?username=ritayoussef&theme=transparent&count_private=true&show_icons=true&rank_icon=github&locale=en" alt="ritayoussef's GitHub Stats" />
 
  <img width=325 src="https://github-readme-stats.vercel.app/api/top-langs?username=ritayoussef&theme=transparent&layout=donut&hide=css&langs_count=8&border_radius=10&show_icons=true&locale=en" alt="ritayoussef's Most Used Languages" />
</div>

<hr>
</section>
            <div class="buttons">
                <a href="/mnt/data/YoussefRita%202.pdf" download="Rita_Youssef_CV.pdf">Download CV</a>
                <a href="https://github.com/ritayoussef" target="_blank">GitHub</a>
            </div>
        </div>
    </div>
    <footer>
        <p> <strong> Connect with me on </strong> <a href="https://github.com/ritayoussef" target="_blank">GitHub</a> </p>
        <div align="center">
            <a href="mailto:youssef.rita14@gmail.com">
              <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
            </a>
            <a href="https://www.linkedin.com/in/rita-youssef-759965223/" target="_blank">
              <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
            </a>
          </div>
          <hr>
    </footer>
</body>
</html>
