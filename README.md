<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Akkouh | Full-Stack Web Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
        .card {
            background-color: #ffffff;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 2.5rem;
            border: 1px solid #e5e7eb;
        }
        .project-card {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="p-4 sm:p-8">
    <main class="max-w-5xl mx-auto space-y-8">
        <!-- Header & Socials Card -->
        <header class="text-center card">
            <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-900 leading-tight mb-2">
                Hi 👋, I'm Mohamed Akkouh
            </h1>
            <h3 class="text-xl sm:text-2xl font-semibold text-gray-700 mb-6">
                Full-Stack Web Developer & IT Management
            </h3>
            
            <div class="flex flex-wrap justify-center gap-4 mb-4">
                <a href="https://github.com/mohamed-ako" target="_blank" class="hover:scale-105 transition-transform">
                    <img src="https://img.shields.io/badge/GitHub-mohamed--ako-181717?style=flat&logo=github&logoColor=white" alt="GitHub Profile" class="rounded-lg"/>
                </a>
                <a href="mailto:mohamedakkouh07@gmail.com" class="hover:scale-105 transition-transform">
                    <img src="https://img.shields.io/badge/Email-mohamedakkouh07@gmail.com-red?style=flat&logo=gmail&logoColor=white" alt="Email Address" class="rounded-lg"/>
                </a>
            </div>
        </header>

        <!-- About Section -->
        <section class="card space-y-4 text-gray-800">
            <h2 class="text-2xl font-bold text-gray-900 mb-4">About Me</h2>
            <p class="flex items-center gap-2">
                <span class="text-lg font-medium">🎓</span> I have completed my **Bachelor’s in IT (Distance learning)** from SUPMTI, Rabat.
            </p>
            <p class="flex items-center gap-2">
                <span class="text-lg font-medium">📘</span> I hold a **Specialized Technician Diploma** in Web Full-Stack Development from ISTA Al-Hoceima.
            </p>
            <p class="flex items-center gap-2">
                <span class="text-lg font-medium">💼</span> I’ve built a variety of applications including **e-commerce**, **real estate**, and **clinic websites** using modern tech stacks.
            </p>
        </section>

        <!-- Projects Section -->
        <section class="card">
            <h2 class="text-2xl font-bold text-gray-900 mb-6">💼 Notable Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-6">
                <div class="project-card border border-gray-200 p-6 rounded-xl space-y-2">
                    <h3 class="text-lg font-bold text-gray-800">☕ Coffee Shop POS System</h3>
                    <p class="text-gray-600">
                        A full-stack POS system built with React, Express.js, and SQLite3, featuring user authentication and real-time sales analytics.
                    </p>
                    <a href="https://github.com/mohamed-ako/SmartRif-Cafe" class="text-blue-600 hover:underline font-medium">View on GitHub →</a>
                </div>
                <div class="project-card border border-gray-200 p-6 rounded-xl space-y-2">
                    <h3 class="text-lg font-bold text-gray-800">🎬 Intelligent Movie Recommender</h3>
                    <p class="text-gray-600">
                        Developed a hybrid movie recommender using Flask, React, and MongoDB, incorporating TF-IDF and cosine similarity for personalization.
                    </p>
                    <a href="https://github.com/mohamed-ako/Intelligent-Movie-Recommendation-Website" class="text-blue-600 hover:underline font-medium">View on GitHub →</a>
                </div>
                <div class="project-card border border-gray-200 p-6 rounded-xl space-y-2">
                    <h3 class="text-lg font-bold text-gray-800">🛒 Dropshipping E-commerce Store</h3>
                    <p class="text-gray-600">
                        Engineered a full dropshipping e-commerce store using the MERN stack with integrated data scraping and product management.
                    </p>
                    <a href="#" class="text-blue-600 hover:underline font-medium">View Project →</a>
                </div>
                <div class="project-card border border-gray-200 p-6 rounded-xl space-y-2">
                    <h3 class="text-lg font-bold text-gray-800">🏠 Real Estate Platform</h3>
                    <p class="text-gray-600">
                        Built a full-stack real estate platform for property rentals and sales using Laravel, React.js, and MySQL.
                    </p>
                    <a href="#" class="text-blue-600 hover:underline font-medium">View Project →</a>
                </div>
                 <div class="project-card border border-gray-200 p-6 rounded-xl space-y-2">
                    <h3 class="text-lg font-bold text-gray-800">🏥 Ali Allach Blood Filter Center Website</h3>
                    <p class="text-gray-600">
                        Created a website for a blood filter center using React.js and Express.js, providing a digital presence for a health organization.
                    </p>
                    <a href="#" class="text-blue-600 hover:underline font-medium">View Project →</a>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section class="card">
            <h2 class="text-2xl font-bold text-gray-900 mb-6">🛠️ Technologies & Tools</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <div>
                    <h4 class="text-lg font-semibold text-gray-700 mb-2">Front-End:</h4>
                    <div class="flex flex-wrap gap-2">
                        <img src="https://img.shields.io/badge/-React-20232A?logo=react&logoColor=61DAFB&style=flat" alt="React" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-React_Native-61DAFB?logo=react&logoColor=black&style=flat" alt="React Native" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Redux-764ABC?logo=redux&logoColor=white&style=flat" alt="Redux" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Next.js-000000?logo=next.js&logoColor=white&style=flat" alt="Next.js" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat" alt="JavaScript" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-jQuery-0769AD?logo=jquery&logoColor=white&style=flat" alt="jQuery" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Tailwind-38B2AC?logo=tailwind-css&logoColor=white&style=flat" alt="TailwindCSS" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Bootstrap-563D7C?logo=bootstrap&logoColor=white&style=flat" alt="Bootstrap" class="rounded-lg"/>
                    </div>
                </div>
                <div>
                    <h4 class="text-lg font-semibold text-gray-700 mb-2">Back-End:</h4>
                    <div class="flex flex-wrap gap-2">
                        <img src="https://img.shields.io/badge/-Node.js-43853D?logo=node.js&logoColor=white&style=flat" alt="Node.js" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white&style=flat" alt="Express" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Laravel-E74430?logo=laravel&logoColor=white&style=flat" alt="Laravel" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white&style=flat" alt="Flask" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Firebase-FFCA28?logo=firebase&logoColor=black&style=flat" alt="Firebase" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-PHP-777BB4?logo=php&logoColor=white&style=flat" alt="PHP" class="rounded-lg"/>
                    </div>
                </div>
                <div>
                    <h4 class="text-lg font-semibold text-gray-700 mb-2">Databases:</h4>
                    <div class="flex flex-wrap gap-2">
                        <img src="https://img.shields.io/badge/-MongoDB-4DB33D?logo=mongodb&logoColor=white&style=flat" alt="MongoDB" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-MySQL-00758F?logo=mysql&logoColor=white&style=flat" alt="MySQL" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Microsoft_SQL_Server-CC2927?logo=microsoft-sql-server&logoColor=white&style=flat" alt="Microsoft SQL Server" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-PL%2FSQL-FF0000?logo=oracle&logoColor=white&style=flat" alt="PL/SQL" class="rounded-lg"/>
                    </div>
                </div>
                <div>
                    <h4 class="text-lg font-semibold text-gray-700 mb-2">Cloud & DevOps:</h4>
                    <div class="flex flex-wrap gap-2">
                        <img src="https://img.shields.io/badge/-Azure-0078D4?logo=azure&logoColor=white&style=flat" alt="Azure" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white&style=flat" alt="AWS" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=flat" alt="Git" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=flat" alt="GitHub" class="rounded-lg"/>
                    </div>
                </div>
                <div>
                    <h4 class="text-lg font-semibold text-gray-700 mb-2">Other Tools:</h4>
                    <div class="flex flex-wrap gap-2">
                        <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat" alt="Python" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Active_Directory-0078D4?logo=microsoft&logoColor=white&style=flat" alt="Active Directory" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Microsoft_Office-D83B01?logo=microsoft-office&logoColor=white&style=flat" alt="Microsoft Office" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black&style=flat" alt="Linux" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Figma-F24E1E?logo=figma&logoColor=white&style=flat" alt="Figma" class="rounded-lg"/>
                        <img src="https://img.shields.io/badge/-Jira-0052CC?logo=jira&logoColor=white&style=flat" alt="Jira" class="rounded-lg"/>
                    </div>
                </div>
            </div>
        </section>

        <!-- GitHub Stats Section -->
        <section class="card">
            <h2 class="text-2xl font-bold text-gray-900 mb-4">📊 GitHub Stats</h2>
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <img src="https://github-readme-stats.vercel.app/api?username=mohamed-ako&show_icons=true&theme=radical" alt="GitHub Stats" class="w-full sm:w-1/2 rounded-lg shadow-md"/>
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohamed-ako&layout=compact&theme=radical" alt="Top Languages" class="w-full sm:w-1/2 rounded-lg shadow-md"/>
            </div>
        </section>
        
        <!-- Education & Certifications -->
        <section class="card">
            <h2 class="text-2xl font-bold text-gray-900 mb-4">📌 Education</h2>
            <ul class="space-y-4 text-gray-800 list-disc list-inside">
                <li>
                    **Bachelor’s in IT** (SUPMTI, Rabat) | 2024
                </li>
                <li>
                    **Specialized Technician Diploma in Web Full-Stack Development** (ISTA, Al-Hoceima) | 2022 - 2024
                </li>
                <li>
                    **Bachelor's in Private Law** (Abdelmalek Essaâdi University) | 2017-2020
                </li>
            </ul>

            <h2 class="text-2xl font-bold text-gray-900 mt-8 mb-4">Certifications</h2>
            <ul class="space-y-4 text-gray-800 list-disc list-inside">
                 <li>
                    **Foundation of Digital Marketing** (UDACITY) | 2025
                 </li>
                 <li>
                    **Entrepreneurial Innovation: From Idea to Project** (ISTA) | 2024
                 </li>
                 <li>
                    **Full-Stack Web Development Certificate** (UDACITY) | 2021
                 </li>
            </ul>
        </section>

        <!-- Languages & Quote -->
        <footer class="text-center italic text-gray-600 py-4">
            <h2 class="text-2xl font-bold text-gray-900 mb-2 not-italic">🌐 Languages</h2>
            <p>🗣️ Arabic (Native), Tarifit (Native) | 🌍 English (Intermediate), French (Beginner)</p>
            <p class="mt-4">💡 "I’m passionate about building useful digital tools and growing in the fields of AI, Web Development, and Data Analysis."</p>
        </footer>
    </main>
</body>
</html>
