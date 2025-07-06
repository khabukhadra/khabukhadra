<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kanaan - Software Developer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .header h1 {
            color: #333;
            margin: 20px 0;
        }
        
        .skills-section {
            margin-bottom: 30px;
        }
        
        .skills-section h3 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        
        .skills-category {
            margin-bottom: 25px;
        }
        
        .skills-category h4 {
            color: #34495e;
            margin-bottom: 15px;
            font-size: 1.1em;
        }
        
        .tech-icons {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .tech-icons img {
            width: 80px;
            height: 80px;
            object-fit: contain;
            transition: transform 0.3s ease;
        }
        
        .tech-icons img:hover {
            transform: scale(1.1);
        }
        
        .project-link {
            background: #3498db;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
            transition: background 0.3s ease;
        }
        
        .project-link:hover {
            background: #2980b9;
        }
        
        @media (max-width: 768px) {
            .tech-icons {
                justify-content: center;
            }
            
            .tech-icons img {
                width: 60px;
                height: 60px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" 
                 height="300" 
                 alt="Developer Animation" 
                 style="max-width: 100%; height: auto;" />
            <h1>Hi there, I'm Kanaan, Software Developer</h1>
        </div>
        
        <div class="skills-section">
            <h3>Technical Skills</h3>
            
            <div class="skills-category">
                <h4>Backend/Server</h4>
                <div class="tech-icons">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" alt="FastAPI" />
                </div>
            </div>
            
            <div class="skills-category">
                <h4>Programming Languages</h4>
                <div class="tech-icons">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-plain.svg" alt="C++" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-plain.svg" alt="JavaScript" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original-wordmark.svg" alt="Java" />
                </div>
            </div>
            
            <div class="skills-category">
                <h4>Databases</h4>
                <div class="tech-icons">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original.svg" alt="Redis" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" alt="MySQL" />
                </div>
            </div>
            
            <div class="skills-category">
                <h4>Web Development</h4>
                <div class="tech-icons">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/blazor/blazor-original.svg" alt="Blazor" />
                    <img src="https://raw.githubusercontent.com/souravpal01/souravpal01/master/img/web/ms/rest.png" alt="REST API" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="HTML5" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="CSS3" />
                </div>
            </div>
            
            <div class="skills-category">
                <h4>DevOps & Infrastructure</h4>
                <div class="tech-icons">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-plain.svg" alt="Docker" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azure/azure-original.svg" alt="Azure" />
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git" />
                    <img src="https://raw.githubusercontent.com/souravpal01/souravpal01/master/img/other/jira.png" alt="Jira" />
                </div>
            </div>
            
            <div class="skills-category">
                <h4>Architecture & Patterns</h4>
                <div class="tech-icons">
                    <img src="https://raw.githubusercontent.com/souravpal01/souravpal01/master/img/web/security/jwt.png" alt="JWT" />
                </div>
            </div>
        </div>
        
        <div style="text-align: center;">
            <a href="https://github.com/khabukhadra/PAF.Client" class="project-link" target="_blank">
                Check out 'Ping A Freelancer' SaaS Client App
            </a>
        </div>
    </div>
</body>
</html>
