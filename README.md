<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kevin J. Sandke - Software Engineer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #111827; /* Tailwind gray-900 */
            color: #d1d5db; /* Tailwind gray-300 */
        }
        .section-title {
            @apply text-3xl font-bold text-white mb-8 text-center;
        }
        .accent-color {
            color: #38bdf8; /* Tailwind sky-400 */
        }
        .card {
            @apply bg-gray-800 p-6 rounded-xl shadow-lg transition-transform duration-300 hover:transform hover:-translate-y-2;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header & Navigation -->
    <header class="bg-gray-800/80 backdrop-blur-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold text-white">Kevin J. Sandke</a>
            <div class="hidden md:flex space-x-6 items-center">
                <a href="#about" class="hover:text-sky-400 transition-colors">About</a>
                <a href="#skills" class="hover:text-sky-400 transition-colors">Skills</a>
                <a href="#projects" class="hover:text-sky-400 transition-colors">Projects</a>
                <a href="#blog" class="hover:text-sky-400 transition-colors">Course Project</a>
                <a href="#education" class="hover:text-sky-400 transition-colors">Education</a>
                <a href="#contact" class="bg-sky-500 text-white px-4 py-2 rounded-md hover:bg-sky-600 transition-colors">Contact</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-white">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4">
            <a href="#about" class="block py-2 hover:text-sky-400">About</a>
            <a href="#skills" class="block py-2 hover:text-sky-400">Skills</a>
            <a href="#projects" class="block py-2 hover:text-sky-400">Projects</a>
            <a href="#blog" class="block py-2 hover:text-sky-400">Course Project</a>
            <a href="#education" class="block py-2 hover:text-sky-400">Education</a>
            <a href="#contact" class="block py-2 hover:text-sky-400">Contact</a>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">

        <!-- Homepage / Hero Section -->
        <section id="home" class="text-center min-h-[60vh] flex flex-col justify-center items-center">
            <h1 class="text-4xl md:text-6xl font-extrabold text-white leading-tight">
                Kevin J. Sandke
            </h1>
            <p class="mt-4 text-xl md:text-2xl text-sky-400">
                Software Engineer with a Passion for AI & Machine Learning
            </p>
            <p class="mt-6 max-w-3xl text-lg text-gray-400">
                A software engineering intern with robust experience in mobile game development and CI/CD optimization. Proven ability to build scalable, high-performance systems and rapidly learn new technologies.
            </p>
            <div class="mt-8 flex justify-center gap-4">
                <a href="#projects" class="bg-sky-500 text-white px-6 py-3 rounded-md text-lg font-semibold hover:bg-sky-600 transition-colors">View My Work</a>
                <a href="/KEVIN J. SANDKE_2025 SWE.pdf" download="Kevin_Sandke_Resume.pdf" class="bg-gray-700 text-white px-6 py-3 rounded-md text-lg font-semibold hover:bg-gray-600 transition-colors">Download CV</a>
            </div>
        </section>

        <!-- About Me / Career Goals -->
        <section id="about" class="py-20">
            <h2 class="section-title">About Me</h2>
            <div class="max-w-4xl mx-auto text-lg text-center leading-relaxed">
                <p class="mb-4">
                    I am a highly motivated software engineer currently pursuing an Applied Computer Science degree with a specialization in Artificial Intelligence and Machine Learning. My background in Cognitive and Behavioral Neuroscience gives me a unique perspective on creating user-centric and intelligent systems.
                </p>
                <p class="mb-4">
                    My career goal is to become a Machine Learning Engineer, where I can leverage my skills in MLOps to manage the entire lifecycle of ML systems. I'm passionate about the engineering practices required to make AI models deployable, scalable, and maintainable in real-world applications. I thrive in collaborative environments, demonstrated by my experience using Agile and Scrum methodologies to enhance team efficiency and project outcomes.
                </p>
            </div>
        </section>

        <!-- Technical Skills -->
        <section id="skills" class="py-20 bg-gray-900 rounded-2xl">
            <h2 class="section-title">Technical Skills</h2>
            <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 text-gray-300">
                
                <div class="card">
                    <h3 class="text-xl font-bold text-sky-400 mb-4">Machine Learning & AI</h3>
                    <ul class="space-y-2 list-disc list-inside">
                        <li>NLP & LLMs</li>
                        <li>Deep Learning & Computer Vision</li>
                        <li>PyTorch, TensorFlow, scikit-learn</li>
                        <li>Hugging Face, Transformers, BERT</li>
                    </ul>
                </div>

                <div class="card">
                    <h3 class="text-xl font-bold text-sky-400 mb-4">Programming Languages</h3>
                     <ul class="space-y-2 list-disc list-inside">
                        <li>Python, C/C++</li>
                        <li>Swift, JavaScript</li>
                        <li>Java, C#</li>
                    </ul>
                </div>

                <div class="card">
                    <h3 class="text-xl font-bold text-sky-400 mb-4">Frameworks & Libraries</h3>
                     <ul class="space-y-2 list-disc list-inside">
                        <li>Flask</li>
                        <li>SpriteKit, SwiftUI</li>
                        <li>Unity Engine, Unreal Engine</li>
                    </ul>
                </div>

                <div class="card">
                    <h3 class="text-xl font-bold text-sky-400 mb-4">Tools & DevOps</h3>
                     <ul class="space-y-2 list-disc list-inside">
                        <li>Git & Full-Stack Development</li>
                        <li>Docker, CI/CD, Unit Testing, QA</li>
                        <li>Agile & Scrum</li>
                        <li>API Development</li>
                    </ul>
                </div>

                <div class="card">
                    <h3 class="text-xl font-bold text-sky-400 mb-4">Databases</h3>
                     <ul class="space-y-2 list-disc list-inside">
                        <li>PostgreSQL</li>
                        <li>SQL</li>
                    </ul>
                </div>

                 <div class="card">
                    <h3 class="text-xl font-bold text-sky-400 mb-4">Relevant Coursework</h3>
                     <ul class="space-y-2 list-disc list-inside">
                        <li>Artificial Intelligence</li>
                        <li>Machine Learning</li>
                        <li>Cognitive & Behavioral Neuroscience</li>
                        <li>Professional Development 3112</li>
                    </ul>
                </div>

            </div>
        </section>

        <!-- Portfolio / Projects -->
        <section id="projects" class="py-20">
            <h2 class="section-title">Projects & Experience</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <div class="card col-span-1 md:col-span-2 lg:col-span-3 bg-sky-900/50">
                    <h3 class="text-2xl font-bold text-sky-300">Featured: MLOps Pipeline for Recommender System</h3>
                    <p class="mt-2 text-gray-300">Developed a full MLOps pipeline, including automated CI/CD with GitHub Actions, Docker containerization, and a Flask REST API. Managed data and model versioning with Hugging Face for reproducibility.</p>
                    <a href="#blog" class="inline-block mt-4 text-sky-400 font-semibold hover:text-sky-300">Read the Project Blog &rarr;</a>
                </div>

                <div class="card">
                    <h3 class="text-xl font-bold text-white">Mobile Game Development</h3>
                    <p class="text-sm text-sky-400 mb-2">Software Engineer Intern @ Hyel Inc.</p>
                    <p class="mt-2 text-gray-400">Developed a mobile game using Swift, SwiftUI, and SpriteKit from concept to deployment, increasing user engagement by 30%. Engineered a CI/CD pipeline that reduced QA time by 35%.</p>
                </div>
                
                <div class="card">
                    <h3 class="text-xl font-bold text-white">NLP Legal Document Simplifier</h3>
                    <p class="text-sm text-sky-400 mb-2">Personal Project</p>
                    <p class="mt-2 text-gray-400">Developed a Python application to classify, summarize, and simplify legal documents using a fine-tuned Pegasus model trained with PyTorch and scikit-learn.</p>
                </div>

                <div class="card">
                    <h3 class="text-xl font-bold text-white">OpenAI Car Racing Agent</h3>
                    <p class="text-sm text-sky-400 mb-2">Personal Project</p>
                    <p class="mt-2 text-gray-400">Developed an AI Agent that navigates a racetrack using a CNN for computer vision and Proximal Policy Optimization for learning with PyTorch. Achieved scores over 900/1000.</p>
                </div>

                 <div class="card">
                    <h3 class="text-xl font-bold text-white">Natural Language Model Developer</h3>
                    <p class="text-sm text-sky-400 mb-2">Developer @ ChatOwl Inc.</p>
                    <p class="mt-2 text-gray-400">Annotated over 10,000 sentences for NLP training, achieving 99% accuracy. Proposed architectural improvements that increased conversational accuracy by 15%.</p>
                </div>
                
            </div>
        </section>

        <!-- Course Project Blog -->
        <section id="blog" class="py-20 bg-gray-900 rounded-2xl">
            <h2 class="section-title">Course Project Deep Dive</h2>
            <div class="max-w-4xl mx-auto card bg-gray-800">
                <h3 class="text-2xl font-bold text-sky-400 mb-4">MLOps Pipeline for a Recommender System</h3>
                
                <div class="space-y-6 text-gray-300 leading-relaxed">
                    <div>
                        <h4 class="font-bold text-lg text-white">Vision Statement</h4>
                        <p>To design, develop, and deploy a foundational recommender system incorporating core Machine Learning Operations (MLOps) practices.</p>
                    </div>

                    <div>
                        <h4 class="font-bold text-lg text-white">Project Motivation</h4>
                        <p>This project was crucial for my career goal of becoming a Machine Learning Engineer. It provided hands-on experience with not just model-building, but also the critical MLOps skills required to manage the entire lifecycle of ML systems, from version control and API development to containerization and CI/CD.</p>
                    </div>

                    <div>
                        <h4 class="font-bold text-lg text-white">Key Goals & Learning Objectives</h4>
                        <ul class="list-disc list-inside space-y-2 pl-4">
                            <li><strong>Develop a Functional Recommender System:</strong> Implement a core recommender algorithm, preprocess a public dataset, and achieve a measurable baseline performance.</li>
                            <li><strong>Implement Core MLOps:</strong> Version control code (Git), data/models (Hugging Face), develop a REST API (Flask), and containerize the application (Docker).</li>
                            <li><strong>Establish Basic CI/CD:</strong> Set up a GitHub Actions workflow for automated code linting, testing, and Docker image building.</li>
                            <li><strong>Documentation:</strong> Maintain a project portfolio with weekly updates and a final report.</li>
                        </ul>
                    </div>
                     <div>
                        <h4 class="font-bold text-lg text-white">Risks & Mitigation</h4>
                        <p>A key challenge was learning new tools like Docker and REST APIs within the project timeline. I mitigated this by relying on official documentation and utilizing LLMs for rapid learning. To avoid scope creep, I adhered strictly to the MVP outlined in the project proposal. To manage long training times, I was methodical in dataset selection and training efficiency.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Education -->
        <section id="education" class="py-20">
            <h2 class="section-title">Education</h2>
            <div class="max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="card text-center">
                    <h3 class="text-xl font-bold text-white">University of Colorado Boulder</h3>
                    <p class="text-sky-400 font-semibold mt-1">B.S., Applied Computer Science</p>
                    <p class="text-gray-400 mt-2">Expected Aug 2025</p>
                    <p class="text-gray-400">GPA: 3.5</p>
                    <p class="mt-2 bg-sky-900/50 text-sky-300 rounded-full py-1 px-3 inline-block text-sm">Specialization: Artificial Intelligence / Machine Learning</p>
                </div>
                 <div class="card text-center">
                    <h3 class="text-xl font-bold text-white">University of California San Diego</h3>
                    <p class="text-sky-400 font-semibold mt-1">B.S., Cognitive and Behavioral Neuroscience</p>
                    <p class="text-gray-400 mt-2">Graduated Sep 2022</p>
                    <p class="text-gray-400">GPA: 3.6</p>
                     <p class="mt-2 bg-green-900/50 text-green-300 rounded-full py-1 px-3 inline-block text-sm">Provost Honors</p>
                </div>
            </div>
        </section>

        <!-- Contact Information -->
        <section id="contact" class="py-20 text-center">
            <h2 class="section-title">Get In Touch</h2>
            <p class="max-w-2xl mx-auto text-lg text-gray-400 mb-8">
                I'm currently seeking new opportunities and would love to connect. Feel free to reach out via email or connect with me on social media.
            </p>
            <a href="mailto:kevinsandke7@gmail.com" class="text-2xl font-bold text-sky-400 hover:text-sky-300 transition-colors">
                kevinsandke7@gmail.com
            </a>
            <div class="flex justify-center items-center gap-6 mt-8">
                <a href="https://github.com/KSandke" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white transition-colors">
                    <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.477 2 12c0 4.418 2.865 8.168 6.839 9.492.5.092.682-.217.682-.482 0-.237-.009-.868-.014-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.031-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.378.203 2.398.1 2.651.64.7 1.03 1.595 1.03 2.688 0 3.848-2.338 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.001 10.001 0 0022 12c0-5.523-4.477-10-10-10z" clip-rule="evenodd" /></svg>
                    <span class="sr-only">GitHub</span>
                </a>
                <a href="#" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white transition-colors"> <!-- Replace # with your LinkedIn URL -->
                    <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                    <span class="sr-only">LinkedIn</span>
                </a>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 border-t border-gray-700">
        <div class="container mx-auto px-6 py-4 text-center text-gray-400">
            <p>&copy; <span id="current-year"></span> Kevin J. Sandke. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        // JavaScript for mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Set current year in footer
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Close mobile menu when a link is clicked
        const menuLinks = document.querySelectorAll('#mobile-menu a');
        menuLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
