<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moein Ebrahimzade - GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #24292e;
            background-color: #ffffff;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Language Switcher */
        .language-switcher {
            text-align: center;
            margin-bottom: 30px;
            padding: 15px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 10px;
        }

        .language-switcher button {
            background-color: white;
            color: #667eea;
            border: none;
            padding: 10px 25px;
            margin: 0 10px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .language-switcher button:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .language-switcher button.active {
            background-color: #5a67d8;
            color: white;
        }

        /* Content Sections */
        .content-section {
            display: none;
        }

        .content-section.active {
            display: block;
            animation: fadeIn 0.5s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* RTL Support for Persian */
        .rtl {
            direction: rtl;
            text-align: right;
        }

        /* Headers */
        h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #2d3748;
        }

        h2 {
            font-size: 2em;
            margin-top: 30px;
            margin-bottom: 15px;
            color: #4a5568;
            border-bottom: 2px solid #667eea;
            padding-bottom: 10px;
        }

        h3 {
            font-size: 1.5em;
            margin-top: 20px;
            margin-bottom: 10px;
            color: #667eea;
        }

        /* Links */
        a {
            color: #667eea;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Lists */
        ul {
            margin-left: 20px;
            margin-bottom: 15px;
        }

        .rtl ul {
            margin-right: 20px;
            margin-left: 0;
        }

        li {
            margin-bottom: 8px;
        }

        /* Badges */
        img {
            max-width: 100%;
            height: auto;
            margin: 5px;
        }

        /* Code blocks */
        code {
            background-color: #f6f8fa;
            padding: 2px 6px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
        }

        /* Center aligned content */
        .center {
            text-align: center;
        }

        /* Dark mode support */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #0d1117;
                color: #c9d1d9;
            }

            h1, h2, h3 {
                color: #58a6ff;
            }

            code {
                background-color: #161b22;
            }
        }
    </style>
</head>
<body>
    <!-- Language Switcher -->
    <div class="language-switcher">
        <button id="btn-en" class="active" onclick="switchLanguage('en')">
            🇬🇧 English
        </button>
        <button id="btn-fa" onclick="switchLanguage('fa')">
            🇮🇷 فارسی
        </button>
    </div>

    <!-- English Content -->
    <div id="content-en" class="content-section active">
        <h1 class="center">Hi there, I'm Moein Ebrahimzade! 👋</h1>
        
        <p class="center">
            🎯 <strong>Passionate Python Developer | AI Enthusiast | Open Source Contributor</strong>
        </p>

        <h2>🚀 About Me</h2>
        <ul>
            <li>🐍 Python developer with expertise in backend development and automation</li>
            <li>🤖 Exploring AI and machine learning, especially image generation</li>
            <li>🌱 Currently learning advanced algorithms and data structures</li>
            <li>💡 Love solving problems and building efficient solutions</li>
            <li>📫 How to reach me: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
        </ul>

        <h2>🛠️ Tech Stack</h2>
        
        <h3>Languages</h3>
        <p>
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
        </p>

        <h3>Frameworks & Libraries</h3>
        <p>
            <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
            <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
            <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
        </p>

        <h3>Tools & Platforms</h3>
        <p>
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
            <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code">
            <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
        </p>

        <h2>📊 GitHub Stats</h2>
        <p class="center">
            <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical" alt="GitHub Stats">
        </p>
        <p class="center">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=radical" alt="GitHub Streak">
        </p>

        <h2>🔥 Top Languages</h2>
        <p class="center">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=radical" alt="Top Languages">
        </p>

        <h2>🌟 Featured Projects</h2>
        <ul>
            <li>
                <strong><a href="https://github.com/yourusername/project1">Project 1</a></strong> - Brief description of your awesome project
            </li>
            <li>
                <strong><a href="https://github.com/yourusername/project2">Project 2</a></strong> - Another cool project you've worked on
            </li>
            <li>
                <strong><a href="https://github.com/yourusername/project3">Project 3</a></strong> - Yet another interesting project
            </li>
        </ul>

        <h2>📫 Connect with Me</h2>
        <p>
            <a href="https://linkedin.com/in/yourprofile">
                <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
            </a>
            <a href="https://twitter.com/yourhandle">
                <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
            </a>
            <a href="mailto:your.email@example.com">
                <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
            </a>
        </p>

        <h2>💡 Fun Facts</h2>
        <ul>
            <li>☕ Coffee enthusiast</li>
            <li>🎮 Gamer in free time</li>
            <li>📚 Always learning something new</li>
            <li>🌍 Love to travel and explore</li>
        </ul>

        <hr>
        <p class="center">
            <em>⭐️ From <a href="https://github.com/yourusername">Moein Ebrahimzade</a></em>
        </p>
    </div>

    <!-- Persian Content -->
    <div id="content-fa" class="content-section rtl">
        <h1 class="center">سلام، من معین ابراهیم‌زاده هستم! 👋</h1>
        
        <p class="center">
            🎯 <strong>توسعه‌دهنده پایتون | علاقه‌مند به هوش مصنوعی | مشارکت‌کننده متن‌باز</strong>
        </p>

        <h2>🚀 درباره من</h2>
        <ul>
            <li>🐍 توسعه‌دهنده پایتون با تخصص در توسعه بک‌اند و اتوماسیون</li>
            <li>🤖 کاوش در هوش مصنوعی و یادگیری ماشین، به‌ویژه تولید تصویر</li>
            <li>🌱 در حال یادگیری الگوریتم‌ها و ساختمان داده‌های پیشرفته</li>
            <li>💡 عاشق حل مسائل و ساخت راه‌حل‌های کارآمد</li>
            <li>📫 راه ارتباطی: <a href="mailto:your.email@example.com">your.email@example.com</a></li>
        </ul>

        <h2>🛠️ مهارت‌های فنی</h2>
        
        <h3>زبان‌های برنامه‌نویسی</h3>
        <p>
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
        </p>

        <h3>فریم‌ورک‌ها و کتابخانه‌ها</h3>
        <p>
            <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
            <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
            <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
        </p>

        <h3>ابزارها و پلتفرم‌ها</h3>
        <p>
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
            <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code">
            <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
        </p>

        <h2>📊 آمار گیت‌هاب</h2>
        <p class="center">
            <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical" alt="GitHub Stats">
        </p>
        <p class="center">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=radical" alt="GitHub Streak">
        </p>

        <h2>🔥 زبان‌های برتر</h2>
        <p class="center">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=radical" alt="Top Languages">
        </p>

        <h2>🌟 پروژه‌های برگزیده</h2>
        <ul>
            <li>
                <strong><a href="https://github.com/yourusername/project1">پروژه ۱</a></strong> - توضیح کوتاه درباره پروژه عالی شما
            </li>
            <li>
                <strong><a href="https://github.com/yourusername/project2">پروژه ۲</a></strong> - یک پروژه جالب دیگر که روی آن کار کرده‌اید
            </li>
            <li>
                <strong><a href="https://github.com/yourusername/project3">پروژه ۳</a></strong> - یک پروژه جذاب دیگر
            </li>
        </ul>

        <h2>📫 ارتباط با من</h2>
        <p>
            <a href="https://linkedin.com/in/yourprofile">
                <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
            </a>
            <a href="https://twitter.com/yourhandle">
                <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
            </a>
            <a href="mailto:your.email@example.com">
                <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
            </a>
        </p>

        <h2>💡 نکات جالب</h2>
        <ul>
            <li>☕ عاشق قهوه</li>
            <li>🎮 گیمر در اوقات فراغت</li>
            <li>📚 همیشه در حال یادگیری چیزهای جدید</li>
            <li>🌍 عاشق سفر و کاوش</li>
        </ul>

        <hr>
        <p class="center">
            <em>⭐️ از <a href="https://github.com/yourusername">معین ابراهیم‌زاده</a></em>
        </p>
    </div>

    <!-- JavaScript -->
    <script>
        // Language switcher function
        function switchLanguage(lang) {
            // Hide all content sections
            document.querySelectorAll('.content-section').forEach(section => {
                section.classList.remove('active');
            });

            // Remove active class from all buttons
            document.querySelectorAll('.language-switcher button').forEach(btn => {
                btn.classList.remove('active');
            });

            // Show selected language content
            document.getElementById('content-' + lang).classList.add('active');
            
            // Add active class to selected button
            document.getElementById('btn-' + lang).classList.add('active');

            // Update HTML lang attribute
            document.documentElement.lang = lang;

            // Save preference to localStorage
            localStorage.setItem('preferredLanguage', lang);
        }

        // Load saved language preference on page load
        window.addEventListener('DOMContentLoaded', () => {
            const savedLang = localStorage.getItem('preferredLanguage');
            if (savedLang && (savedLang === 'en' || savedLang === 'fa')) {
                switchLanguage(savedLang);
            }
        });
    </script>
</body>
</html>
