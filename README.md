<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ibrahim Ahmed Galib | MERN Stack Developer</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        // Matching your GitHub README #38BDF8
                        primary: '#38BDF8', 
                        primary_hover: '#0EA5E9',
                        dark: '#0f172a',      // Slate 900 (Tokyonight-ish)
                        darker: '#020617',    // Slate 950
                        surface: '#1e293b',   // Slate 800
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        mono: ['Fira Code', 'monospace'],
                    },
                    animation: {
                        'float': 'float 4s ease-in-out infinite',
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0)' },
                            '50%': { transform: 'translateY(-10px)' },
                        }
                    }
                }
            }
        }
    </script>
    
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Fira+Code:wght@400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #020617; }
        ::-webkit-scrollbar-thumb { background: #38BDF8; border-radius: 4px; }
    </style>
</head>
<body class="bg-darker text-slate-200 overflow-x-hidden">

    <nav class="fixed w-full z-50 px-4 sm:px-6 lg:px-16 py-4 bg-darker/90 backdrop-blur-md border-b border-slate-800">
        <div class="flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <div class="relative">
                    <img src="https://github.com/galibhub.png" alt="Ibrahim Ahmed Galib" class="w-10 h-10 rounded-full border-2 border-primary">
                    <span class="absolute bottom-0 right-0 w-3 h-3 bg-green-500 border-2 border-darker rounded-full"></span>
                </div>
                <span class="text-xl font-bold tracking-wide text-white">Galib<span class="text-primary">.Dev</span></span>
            </div>

            <div class="hidden lg:flex items-center space-x-8 text-slate-400 font-medium">
                <a href="#home" class="hover:text-primary transition-colors">Home</a>
                <a href="#about" class="hover:text-primary transition-colors">About</a>
                <a href="#skills" class="hover:text-primary transition-colors">Skills</a>
                <a href="#portfolio" class="hover:text-primary transition-colors">Portfolio</a>
                <a href="#contact" class="hover:text-primary transition-colors">Contact</a>
            </div>

            <div class="hidden lg:block">
                <a href="https://github.com/galibhub" target="_blank" class="px-6 py-2 border border-slate-700 text-slate-300 hover:border-primary hover:text-primary rounded-full transition-all font-medium text-sm">
                    <i class="fa-brands fa-github mr-2"></i>GitHub
                </a>
            </div>

            <button class="lg:hidden text-2xl text-white focus:outline-none" id="menu-toggle">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>
        
        <div class="lg:hidden hidden mt-4 bg-surface rounded-xl shadow-2xl p-4 border border-slate-700 absolute w-[90%] left-[5%]" id="mobile-menu">
            <div class="flex flex-col space-y-4 text-center">
                <a href="#home" class="text-slate-300 hover:text-white py-2 mobile-link">Home</a>
                <a href="#about" class="text-slate-300 hover:text-white py-2 mobile-link">About</a>
                <a href="#portfolio" class="text-slate-300 hover:text-white py-2 mobile-link">Portfolio</a>
                <a href="#contact" class="text-slate-300 hover:text-white py-2 mobile-link">Contact</a>
            </div>
        </div>
    </nav>

    <section id="home" class="pt-32 pb-20 px-4 sm:px-6 lg:px-16 flex flex-col lg:flex-row items-center justify-between min-h-screen relative overflow-hidden">
        <div class="absolute top-0 left-0 w-full h-full bg-gradient-to-br from-[#0f172a] via-[#020617] to-[#020617] -z-10"></div>
        <div class="absolute top-20 right-20 w-72 h-72 bg-primary/10 blur-[100px] rounded-full"></div>

        <div class="lg:w-1/2 text-center lg:text-left z-10 order-2 lg:order-1">
            <div class="inline-block px-3 py-1 mb-4 rounded-full border border-primary/30 bg-primary/10">
                <span class="text-primary text-xs font-mono font-semibold tracking-wider">MERN STACK SPECIALIST</span>
            </div>
            <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold mb-6 leading-tight text-white">
                Ibrahim Ahmed <br>
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-blue-500">Galib</span>
            </h1>
            
            <div class="h-8 mb-6 font-mono text-primary/80 text-sm sm:text-base">
                &gt; Building_Scalable_Web_Apps<span class="animate-pulse">_</span>
            </div>

            <p class="text-slate-400 text-lg max-w-2xl mx-auto lg:mx-0 mb-8 leading-relaxed">
                Based in <span class="text-white">Dhaka, Bangladesh</span>. Engineering large-scale MERN applications and exploring <span class="text-white">AI & Machine Learning</span>.
            </p>
            
            <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">
                <a href="#contact" class="px-8 py-3 bg-primary text-darker hover:bg-white font-bold rounded-full transition-all shadow-lg shadow-primary/20">
                    Hire Me
                </a>
                <a href="#portfolio" class="px-8 py-3 border border-slate-600 text-slate-300 hover:border-white hover:text-white rounded-full transition-all font-medium">
                    View Projects
                </a>
            </div>
            
            <div class="mt-10 flex justify-center lg:justify-start gap-6 text-slate-400">
                <a href="https://www.linkedin.com/in/ibrahim-ahmed-galib/" target="_blank" class="hover:text-[#0A66C2] transition-colors text-2xl"><i class="fa-brands fa-linkedin"></i></a>
                <a href="mailto:ibrahimgalib00@gmail.com" class="hover:text-[#D14836] transition-colors text-2xl"><i class="fa-solid fa-envelope"></i></a>
                <a href="https://github.com/galibhub" target="_blank" class="hover:text-white transition-colors text-2xl"><i class="fa-brands fa-github"></i></a>
            </div>
        </div>

        <div class="lg:w-1/2 relative flex justify-center z-0 mt-12 lg:mt-0 order-1 lg:order-2">
            <div class="relative w-[300px] h-[300px] sm:w-[400px] sm:h-[400px]">
                <div class="absolute inset-0 bg-gradient-to-tr from-primary to-blue-600 rounded-full blur-2xl opacity-20 animate-pulse"></div>
                <div class="w-full h-full rounded-full bg-slate-800 relative overflow-hidden border-[4px] border-slate-700/50 shadow-2xl z-10">
                    <img src="https://github.com/galibhub.png" alt="Ibrahim Ahmed Galib" class="w-full h-full object-cover">
                </div>
                
                <div class="absolute -top-4 -left-4 p-3 bg-surface rounded-xl border border-slate-700 shadow-lg animate-float z-20">
                    <i class="devicon-react-original text-[#61DAFB] text-3xl"></i>
                </div>
                <div class="absolute bottom-8 -right-4 p-3 bg-surface rounded-xl border border-slate-700 shadow-lg animate-float z-20" style="animation-delay: 1.5s">
                    <i class="devicon-mongodb-plain text-green-500 text-3xl"></i>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-20 px-4 sm:px-6 lg:px-16 bg-dark border-y border-slate-800">
        <div class="max-w-7xl mx-auto">
            <div class="grid lg:grid-cols-2 gap-12">
                <div>
                    <span class="text-primary font-bold tracking-wider uppercase text-sm">About Me</span>
                    <h2 class="text-3xl lg:text-4xl font-bold mb-6 mt-2 text-white">My Journey</h2>
                    <p class="text-slate-400 mb-6 leading-relaxed">
                        I am a <strong>MERN Stack Developer</strong> with a strong CS foundation from Daffodil International University. Unlike just following tutorials, I specialize in building scalable digital experiences.
                    </p>
                    
                    <div class="bg-surface border border-slate-700 rounded-2xl p-6 mb-6">
                        <h3 class="text-white font-bold mb-4 flex items-center gap-2"><i class="fa-solid fa-bullseye text-primary"></i> Career Objectives</h3>
                        <ul class="space-y-3 text-slate-300 text-sm">
                            <li class="flex gap-3"><i class="fa-solid fa-check text-green-400"></i> Become a Job-Ready MERN Developer</li>
                            <li class="flex gap-3"><i class="fa-solid fa-check text-green-400"></i> Build Scalable, Production-Grade Systems</li>
                            <li class="flex gap-3"><i class="fa-solid fa-check text-green-400"></i> Contribute to Open Source Projects</li>
                        </ul>
                    </div>
                </div>

                <div>
                    <h3 class="text-white font-bold mb-6 mt-8 lg:mt-0">Continuous Learning</h3>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mb-8">
                        <div class="bg-surface p-4 rounded-xl border border-slate-700">
                            <i class="fa-solid fa-layer-group text-primary text-xl mb-2"></i>
                            <h4 class="font-bold text-white">System Design</h4>
                            <p class="text-xs text-slate-400">Mastering Architecture</p>
                        </div>
                        <div class="bg-surface p-4 rounded-xl border border-slate-700">
                            <i class="fa-solid fa-robot text-purple-400 text-xl mb-2"></i>
                            <h4 class="font-bold text-white">AI & ML</h4>
                            <p class="text-xs text-slate-400">Exploring Fundamentals</p>
                        </div>
                    </div>

                    <div class="bg-[#0D1117] p-4 rounded-xl border border-slate-700">
                        <p class="text-xs text-slate-500 mb-2 font-mono">Run: github-stats --user=galibhub</p>
                        <div class="flex gap-2 text-sm">
                            <span class="text-primary">Commits: 500+</span>
                            <span class="text-yellow-400">PRs: 25+</span>
                            <span class="text-green-400">Issues: 12</span>
                        </div>
                        <div class="w-full bg-slate-800 h-1.5 rounded-full mt-3 overflow-hidden">
                            <div class="bg-primary h-full w-[75%]"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="py-20 px-4 sm:px-6 lg:px-16 bg-darker text-center">
        <h2 class="text-3xl lg:text-4xl font-bold mb-12 text-white">Professional Tech Stack</h2>
        
        <div class="flex flex-wrap justify-center gap-6 max-w-4xl mx-auto">
            <div class="group p-4 bg-surface rounded-2xl border border-slate-700 hover:border-primary transition-all">
                <i class="devicon-react-original colored text-4xl"></i>
            </div>
            <div class="group p-4 bg-surface rounded-2xl border border-slate-700 hover:border-primary transition-all">
                <i class="devicon-nextjs-plain text-white text-4xl"></i>
            </div>
            <div class="group p-4 bg-surface rounded-2xl border border-slate-700 hover:border-primary transition-all">
                <i class="devicon-tailwindcss-plain colored text-4xl"></i>
            </div>
            <div class="group p-4 bg-surface rounded-2xl border border-slate-700 hover:border-primary transition-all">
                <i class="devicon-nodejs-plain colored text-4xl"></i>
            </div>
            <div class="group p-4 bg-surface rounded-2xl border border-slate-700 hover:border-primary transition-all">
                <i class="devicon-mongodb-plain colored text-4xl"></i>
            </div>
            <div class="group p-4 bg-surface rounded-2xl border border-slate-700 hover:border-primary transition-all">
                <i class="devicon-firebase-plain colored text-4xl"></i>
            </div>
            <div class="group p-4 bg-surface rounded-2xl border border-slate-700 hover:border-primary transition-all">
                <i class="devicon-git-plain colored text-4xl"></i>
            </div>
        </div>
    </section>

    <section id="portfolio" class="py-20 px-4 sm:px-6 lg:px-16 bg-dark relative">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl lg:text-4xl font-bold mb-12 text-white text-center">Featured Projects</h2>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-surface rounded-2xl overflow-hidden border border-slate-700 hover:border-primary transition-all group">
                    <div class="h-40 bg-gradient-to-br from-blue-900 to-slate-900 flex items-center justify-center">
                        <i class="fa-solid fa-graduation-cap text-5xl text-white/20 group-hover:text-white/40 transition-all"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">E-Tutor Platform</h3>
                        <p class="text-primary text-xs font-mono mb-3">MERN Stack • Auth • JWT</p>
                        <p class="text-slate-400 text-sm mb-4">Tuition management system with authentication & roles.</p>
                        <a href="https://github.com/galibhub/e-tuitor-client" target="_blank" class="text-white hover:text-primary text-sm font-bold flex items-center gap-2">
                            View Code <i class="fa-solid fa-arrow-right"></i>
                        </a>
                    </div>
                </div>

                <div class="bg-surface rounded-2xl overflow-hidden border border-slate-700 hover:border-primary transition-all group">
                    <div class="h-40 bg-gradient-to-br from-cyan-900 to-slate-900 flex items-center justify-center">
                        <i class="fa-solid fa-truck-fast text-5xl text-white/20 group-hover:text-white/40 transition-all"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Export-Import Sys</h3>
                        <p class="text-primary text-xs font-mono mb-3">React • Tailwind</p>
                        <p class="text-slate-400 text-sm mb-4">Client-side workflow automation for businesses.</p>
                        <a href="https://github.com/galibhub/export-import-client" target="_blank" class="text-white hover:text-primary text-sm font-bold flex items-center gap-2">
                            View Code <i class="fa-solid fa-arrow-right"></i>
                        </a>
                    </div>
                </div>

                <div class="bg-surface rounded-2xl overflow-hidden border border-slate-700 hover:border-primary transition-all group">
                    <div class="h-40 bg-gradient-to-br from-yellow-900/50 to-slate-900 flex items-center justify-center">
                        <i class="fa-solid fa-mask text-5xl text-white/20 group-hover:text-white/40 transition-all"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-2">Hero App</h3>
                        <p class="text-primary text-xs font-mono mb-3">JS (ES6) • Frontend UI</p>
                        <p class="text-slate-400 text-sm mb-4">Interactive JavaScript frontend concept project.</p>
                        <a href="https://github.com/galibhub/hero-app" target="_blank" class="text-white hover:text-primary text-sm font-bold flex items-center gap-2">
                            View Code <i class="fa-solid fa-arrow-right"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-24 px-4 sm:px-6 lg:px-16 bg-darker relative border-t border-slate-800">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl lg:text-4xl font-bold mb-6 text-white">Let's Connect</h2>
            <p class="text-slate-400 mb-8">
                Consistency compounds over time. Keep building 🚀
            </p>
            
            <div class="flex flex-col sm:flex-row justify-center gap-6">
                <a href="mailto:ibrahimgalib00@gmail.com" class="flex items-center gap-3 px-6 py-4 bg-surface border border-slate-700 rounded-xl hover:border-primary transition-all group">
                    <i class="fa-solid fa-envelope text-2xl text-red-500 group-hover:scale-110 transition-transform"></i>
                    <div class="text-left">
                        <span class="block text-xs text-slate-500">Email Me</span>
                        <span class="font-bold text-white">ibrahimgalib00@gmail.com</span>
                    </div>
                </a>
                
                <a href="https://www.linkedin.com/in/ibrahim-ahmed-galib/" target="_blank" class="flex items-center gap-3 px-6 py-4 bg-surface border border-slate-700 rounded-xl hover:border-primary transition-all group">
                    <i class="fa-brands fa-linkedin text-2xl text-[#0A66C2] group-hover:scale-110 transition-transform"></i>
                    <div class="text-left">
                        <span class="block text-xs text-slate-500">Connect on</span>
                        <span class="font-bold text-white">LinkedIn</span>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <footer class="bg-black py-8 border-t border-slate-900 text-center">
        <p class="text-slate-600 text-sm">
            © 2026 Ibrahim Ahmed Galib • Built with ☕ and Code
        </p>
    </footer>

    <script>
        const menuToggle = document.getElementById('menu-toggle');
        const mobileMenu = document.getElementById('mobile-menu');
        const mobileLinks = document.querySelectorAll('.mobile-link');
        menuToggle.addEventListener('click', () => mobileMenu.classList.toggle('hidden'));
        mobileLinks.forEach(link => link.addEventListener('click', () => mobileMenu.classList.add('hidden')));
    </script>
</body>
</html>
