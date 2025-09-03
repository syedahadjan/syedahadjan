<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Syed Arsalan Jan - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fadeIn {
            animation: fadeIn 1s ease-out forwards;
        }
        .hover-scale:hover {
            transform: scale(1.05);
            transition: transform 0.3s ease;
        }
    </style>
</head>
<body class="bg-gray-900 text-white font-sans">
    <div class="min-h-screen flex flex-col items-center justify-center p-4">
        <!-- Header Section -->
        <header class="text-center mb-12 animate-fadeIn">
            <img src="https://i.ibb.co/HX4gq6K/Gemini-Generated-Image-39n2tb39n2tb39n2.jpg" alt="Profile Picture" class="w-48 h-48 rounded-full mx-auto mb-4 border-4 border-blue-500 shadow-lg">
            <h1 class="text-5xl font-bold text-blue-400">SYED ARSALAN JAN</h1>
            <h2 class="text-2xl text-gray-300 mt-2">Founder of Code Commandos</h2>
        </header>

        <!-- Badges Section -->
        <section class="flex flex-wrap justify-center gap-4 mb-12 animate-fadeIn" style="animation-delay: 0.2s;">
            <img src="https://badges.pufler.dev/visits/syedahadjan/syedahadjan" alt="Profile Visits">
            <img src="https://badges.pufler.dev/repos/syedahadjan" alt="Repositories">
            <img src="https://badges.pufler.dev/commits/monthly/syedahadjan" alt="Monthly Commits">
        </section>

        <!-- Technology Stack Section -->
        <section class="text-center mb-12 animate-fadeIn" style="animation-delay: 0.4s;">
            <h2 class="text-3xl font-semibold text-blue-400 mb-6 flex items-center justify-center">
                Technology Stack
                <img src="https://github.com/arsalan307/arsalan307/blob/main/images/laptop.gif" alt="Laptop GIF" class="w-12 ml-2">
            </h2>
            <div class="flex flex-wrap justify-center gap-2">
                <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" class="hover-scale">
                <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3" alt="CSS3" class="hover-scale">
                <img src="https://img.shields.io/badge/-Bootstrap-563D7C?style=flat-square&logo=bootstrap" alt="Bootstrap" class="hover-scale">
                <img src="https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript" alt="JavaScript" class="hover-scale">
                <img src="https://img.shields.io/badge/-Nodejs-black?style=flat-square&logo=Node.js" alt="Node.js" class="hover-scale">
                <img src="https://img.shields.io/badge/-React-black?style=flat-square&logo=react" alt="React" class="hover-scale">
                <img src="https://img.shields.io/badge/-MongoDB-black?style=flat-square&logo=mongodb" alt="MongoDB" class="hover-scale">
                <img src="https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql" alt="MySQL" class="hover-scale">
                <img src="https://img.shields.io/badge/-Git-black?style=flat-square&logo=git" alt="Git" class="hover-scale">
                <img src="https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=github" alt="GitHub" class="hover-scale">
            </div>
        </section>

        <!-- Contact Section -->
        <section class="text-center mb-12 animate-fadeIn" style="animation-delay: 0.6s;">
            <h2 class="text-3xl font-semibold text-blue-400 mb-6 flex items-center justify-center">
                Reach Me Out
                <img src="https://media0.giphy.com/media/jqNPzdTTxQfOgOqpO4/source.gif" alt="Contact GIF" class="w-12 ml-2">
            </h2>
            <div class="flex justify-center gap-4">
                <a href="mailto:syedahad63@gmail.com" class="hover-scale">
                    <img src="https://img.shields.io/badge/-syedahad63@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white" alt="Email Syed Ahad">
                </a>
                <a href="https://www.linkedin.com/in/syed-arsalan-jan-725a09241/" class="hover-scale">
                    <img src="https://img.shields.io/badge/-syedarsalanjan-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn">
                </a>
            </div>
        </section>

        <!-- Contribution Graph Section -->
        <section class="text-center mb-12 animate-fadeIn" style="animation-delay: 0.8s;">
            <h2 class="text-3xl font-semibold text-blue-400 mb-6 flex items-center justify-center">
                My Contribution Graph
                <img src="https://media.giphy.com/media/xUA7aZeLE2e0P7Znz2/giphy.gif" alt="Contribution GIF" class="w-12 ml-2">
            </h2>
            <img src="https://github.com/syedarsalanjan/syedarsalanjan/raw/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Graph" class="mx-auto">
        </section>

        <!-- GitHub Stats Section -->
        <section class="text-center mb-12 animate-fadeIn" style="animation-delay: 1s;">
            <h2 class="text-3xl font-semibold text-blue-400 mb-6 flex items-center justify-center">
                My GitHub Stats
                <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" alt="Stats GIF" class="w-12 ml-2">
            </h2>
            <div class="flex flex-wrap justify-center gap-4">
                <img src="https://github-readme-stats.vercel.app/api?username=syedahadjan&show_icons=true&theme=radical&line_height=27" alt="GitHub Stats">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=syedahadjan&hide=html,css,java,shaderlab,kotlin,hlsl&theme=radical" alt="Top Languages">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=syedahadjan&show_icons=true&locale=en&layout=compact&theme=radical&line_height=0" alt="Streak Stats">
                <img src="https://activity-graph.herokuapp.com/graph?username=syedahadjan&theme=redical" alt="Activity Graph">
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center text-gray-400 mt-12">
            <p>If you like it, do fork 🍴 and star ⭐</p>
        </footer>
    </div>
</body>
</html>
