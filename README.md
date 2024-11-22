<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Arun Acharya - Full Stack Developer</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/animejs@3.2.1/lib/anime.min.js"></script>
    <style>
        body { 
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #e0e0e0;
        }
        .skill-badge {
            transition: all 0.3s ease;
            transform-origin: center;
        }
        .skill-badge:hover {
            transform: scale(1.1) rotate(5deg);
            box-shadow: 0 0 15px rgba(255,255,255,0.3);
        }
        .gradient-text {
            background: linear-gradient(45deg, #00f5a0, #00d9f5);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="min-h-screen">
    <div class="container mx-auto px-4 py-16 max-w-6xl">
        <!-- Header -->
        <header class="text-center mb-16">
            <h1 class="text-6xl font-bold gradient-text mb-4 animate-pulse">
                Arun Acharya
            </h1>
            <p class="text-3xl text-blue-200 typing-effect">
                Full Stack Developer | Tech Innovator
            </p>
        </header>

        <!-- Comprehensive Skills Section -->
        <section class="bg-gray-800 rounded-2xl p-10 shadow-2xl mb-16">
            <h2 class="text-4xl font-semibold text-center mb-10 text-blue-300">🚀 Tech Ecosystem</h2>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Programming Languages -->
                <div>
                    <h3 class="text-2xl font-bold mb-6 text-blue-200">Programming Languages</h3>
                    <div class="flex flex-wrap gap-3">
                        <span class="skill-badge bg-blue-900 px-4 py-2 rounded-full">Python</span>
                        <span class="skill-badge bg-yellow-700 px-4 py-2 rounded-full">JavaScript</span>
                        <span class="skill-badge bg-gray-700 px-4 py-2 rounded-full">TypeScript</span>
                    </div>
                </div>

                <!-- Frontend Technologies -->
                <div>
                    <h3 class="text-2xl font-bold mb-6 text-blue-200">Frontend Stack</h3>
                    <div class="flex flex-wrap gap-3">
                        <span class="skill-badge bg-blue-600 px-4 py-2 rounded-full">React.js</span>
                        <span class="skill-badge bg-teal-600 px-4 py-2 rounded-full">Next.js</span>
                        <span class="skill-badge bg-blue-400 px-4 py-2 rounded-full">Tailwind CSS</span>
                        <span class="skill-badge bg-purple-600 px-4 py-2 rounded-full">Redux</span>
                        <span class="skill-badge bg-gray-700 px-4 py-2 rounded-full">HTML5</span>
                        <span class="skill-badge bg-red-600 px-4 py-2 rounded-full">CSS3</span>
                    </div>
                </div>

                <!-- Backend & Database -->
                <div>
                    <h3 class="text-2xl font-bold mb-6 text-blue-200">Backend & Database</h3>
                    <div class="flex flex-wrap gap-3">
                        <span class="skill-badge bg-green-600 px-4 py-2 rounded-full">Node.js</span>
                        <span class="skill-badge bg-green-800 px-4 py-2 rounded-full">MongoDB</span>
                        <span class="skill-badge bg-blue-900 px-4 py-2 rounded-full">MySQL</span>
                        <span class="skill-badge bg-red-700 px-4 py-2 rounded-full">Firebase</span>
                    </div>
                </div>
            </div>

            <!-- Additional Tools & Technologies -->
            <div class="mt-10">
                <h3 class="text-2xl font-bold mb-6 text-blue-200 text-center">🛠 Additional Tools & Technologies</h3>
                <div class="flex flex-wrap justify-center gap-4">
                    <span class="skill-badge bg-gray-700 px-4 py-2 rounded-full">Git</span>
                    <span class="skill-badge bg-black px-4 py-2 rounded-full">GitHub</span>
                    <span class="skill-badge bg-blue-800 px-4 py-2 rounded-full">Vercel</span>
                    <span class="skill-badge bg-green-700 px-4 py-2 rounded-full">Netlify</span>
                    <span class="skill-badge bg-purple-700 px-4 py-2 rounded-full">Figma</span>
                    <span class="skill-badge bg-blue-500 px-4 py-2 rounded-full">Bootstrap</span>
                </div>
            </div>
        </section>

        <!-- Project Showcase -->
        <section class="bg-gray-800 rounded-2xl p-10 shadow-2xl mb-16">
            <h2 class="text-4xl font-semibold text-center mb-10 text-blue-300">🌟 Featured Projects</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-gray-700 p-6 rounded-xl hover:bg-gray-600 transition-all">
                    <h3 class="text-2xl font-bold mb-4 text-blue-300">ThinkBridge Blog App</h3>
                    <p>Full-stack blog application with ReactJS, AppWrite, Redux</p>
                    <div class="mt-4 flex space-x-3">
                        <span class="bg-blue-600 text-white px-3 py-1 rounded-full">React</span>
                        <span class="bg-purple-600 text-white px-3 py-1 rounded-full">Redux</span>
                    </div>
                </div>
                <div class="bg-gray-700 p-6 rounded-xl hover:bg-gray-600 transition-all">
                    <h3 class="text-2xl font-bold mb-4 text-blue-300">Food Booking Platform</h3>
                    <p>Dynamic food booking web app with advanced state management</p>
                    <div class="mt-4 flex space-x-3">
                        <span class="bg-green-600 text-white px-3 py-1 rounded-full">Redux Toolkit</span>
                        <span class="bg-blue-600 text-white px-3 py-1 rounded-full">React</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact & Social Links -->
        <footer class="text-center">
            <div class="flex justify-center space-x-8 mb-8">
                <a href="https://github.com/arunacharya1603" class="text-blue-300 hover:text-blue-100 text-2xl">
                    GitHub
                </a>
                <a href="https://www.linkedin.com/in/arunacharya1603/" class="text-blue-300 hover:text-blue-100 text-2xl">
                    LinkedIn
                </a>
                <a href="mailto:arunacharya1603@gmail.com" class="text-blue-300 hover:text-blue-100 text-2xl">
                    Contact
                </a>
            </div>
            <p class="text-gray-400 text-lg">Transforming ideas into digital solutions 💡</p>
        </footer>
    </div>

    <script>
        // Typing effect
        const typingEffect = document.querySelector('.typing-effect');
        typingEffect.innerHTML = typingEffect.textContent.replace(/\S/g, "<span class='inline-block'>$&</span>");
        
        anime.timeline({loop: true})
            .add({
                targets: '.typing-effect span',
                scale: [0, 1],
                opacity: [0, 1],
                translateZ: 0,
                easing: "easeOutExpo",
                duration: 950,
                delay: (el, i) => 70*i
            }).add({
                targets: '.typing-effect span',
                opacity: 0,
                duration: 1000,
                easing: "easeOutExpo",
                delay: 1100
            });
    </script>
</body>
</html>
