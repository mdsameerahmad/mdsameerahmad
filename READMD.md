<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Md Sameer Ahmad | Full Stack & Android</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #0a0a0a; color: #ededed; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .accent-gradient { background: linear-gradient(135deg, #3b82f6, #8b5cf6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
    </style>
</head>
<body class="p-4 md:p-10">

    <header class="max-w-6xl mx-auto mb-12 flex flex-col md:flex-row justify-between items-end gap-6">
        <div>
            <h1 class="text-5xl font-bold mb-2">Md Sameer <span class="accent-gradient">Ahmad</span></h1>
            <p class="text-xl text-gray-400">Full Stack + Android Developer | B.Tech ECE '27</p>
            <div class="mt-4 flex gap-4">
                <span class="px-3 py-1 glass rounded-full text-sm text-green-400 font-mono">● Building & Shipping ⚡</span>
                <span class="px-3 py-1 glass rounded-full text-sm text-blue-400 font-mono">📍 Bihar, India</span>
            </div>
        </div>
        <div class="text-right font-mono text-sm">
            <p class="text-gray-500">CGPA: <span class="text-white">7.63</span></p>
            <p class="text-gray-500">Solved: <span class="text-white">350+ DSA</span></p>
        </div>
    </header>

    <main class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-6">
        
        <section class="md:col-span-2 glass p-8 rounded-3xl">
            <h2 class="text-2xl font-bold mb-6 flex items-center gap-2">
                <i class="fas fa-briefcase text-blue-500"></i> Experience & Certs
            </h2>
            <div class="space-y-6">
                <div class="flex justify-between items-start border-l-2 border-blue-500 pl-4">
                    <div>
                        <h3 class="font-bold">Virtual Software Engineering</h3>
                        <p class="text-sm text-gray-400">JPMorgan Chase & Co. (Forage)</p>
                    </div>
                    <span class="text-xs font-mono text-gray-500">Oct 2025</span>
                </div>
                <div class="flex justify-between items-start border-l-2 border-purple-500 pl-4">
                    <div>
                        <h3 class="font-bold">AI-ML Intern</h3>
                        <p class="text-sm text-gray-400">AICTE EduSkills × AWS Academy</p>
                    </div>
                    <span class="text-xs font-mono text-gray-500">Apr–Jun 2025</span>
                </div>
                <div class="flex gap-4 mt-6">
                    <img src="https://img.shields.io/badge/NPTEL-IIT_Madras-orange?style=flat-square" alt="NPTEL">
                    <img src="https://img.shields.io/badge/NPTEL-IIT_Kharagpur-blue?style=flat-square" alt="NPTEL">
                </div>
            </div>
        </section>

        <section class="glass p-8 rounded-3xl flex flex-col justify-center items-center text-center">
            <h2 class="text-xl font-bold mb-4">Coding Prowess</h2>
            <div class="text-4xl font-bold text-yellow-500 mb-2">211+</div>
            <p class="text-sm text-gray-400 mb-6">LeetCode Solved</p>
            <div class="w-full bg-gray-800 rounded-full h-2 mb-4">
                <div class="bg-yellow-500 h-2 rounded-full" style="width: 70%"></div>
            </div>
            <p class="text-xs font-mono text-gray-500">Target: 500+ by 2026 Q2</p>
        </section>

        <section class="md:col-span-3 grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="glass p-6 rounded-3xl hover:border-blue-500 transition-all group">
                <div class="flex justify-between mb-4">
                    <span class="text-xs font-mono text-blue-400 uppercase tracking-widest">Fintech R&D</span>
                    <i class="fas fa-external-link-alt group-hover:text-blue-500 transition-colors"></i>
                </div>
                <h3 class="text-2xl font-bold mb-2">UPI Offline Mesh</h3>
                <p class="text-gray-400 text-sm mb-4">Idempotent settlement engine for UPI payments via mesh networking—no internet required.</p>
                <div class="flex gap-2">
                    <span class="text-[10px] bg-gray-800 px-2 py-1 rounded">Node.js</span>
                    <span class="text-[10px] bg-gray-800 px-2 py-1 rounded">Mesh Protocol</span>
                </div>
            </div>

            <div class="glass p-6 rounded-3xl hover:border-green-500 transition-all group">
                <div class="flex justify-between mb-4">
                    <span class="text-xs font-mono text-green-400 uppercase tracking-widest">Entertainment</span>
                    <i class="fas fa-external-link-alt group-hover:text-green-500 transition-colors"></i>
                </div>
                <h3 class="text-2xl font-bold mb-2">Gramflix</h3>
                <p class="text-gray-400 text-sm mb-4">Production streaming & referral platform live on custom domain with real user traffic.</p>
                <div class="flex gap-2">
                    <span class="text-[10px] bg-gray-800 px-2 py-1 rounded">React</span>
                    <span class="text-[10px] bg-gray-800 px-2 py-1 rounded">Firebase</span>
                </div>
            </div>
        </section>

        <section class="md:col-span-3 glass p-8 rounded-3xl">
            <h2 class="text-2xl font-bold mb-8">2025–2027 Strategic Roadmap</h2>
            <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
                <div class="p-4 bg-white/5 rounded-xl border-l-4 border-green-500">
                    <h4 class="font-bold text-sm">2025 H1</h4>
                    <p class="text-xs text-gray-500 mt-2">Shipping AI & Web Production Apps</p>
                </div>
                <div class="p-4 bg-white/5 rounded-xl border-l-4 border-blue-500">
                    <h4 class="font-bold text-sm">2025 H2</h4>
                    <p class="text-xs text-gray-500 mt-2">System Design & Open Source</p>
                </div>
                <div class="p-4 bg-white/5 rounded-xl border-l-4 border-gray-700">
                    <h4 class="font-bold text-sm">2026</h4>
                    <p class="text-xs text-gray-500 mt-2">SDE Internship & 500+ DSA</p>
                </div>
                <div class="p-4 bg-white/5 rounded-xl border-l-4 border-gray-700">
                    <h4 class="font-bold text-sm">2027</h4>
                    <p class="text-xs text-gray-500 mt-2">FAANG Grad Placement</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="max-w-6xl mx-auto mt-12 text-center text-gray-600 text-sm pb-10">
        "The best way to predict the future is to build it." — MD Sameer Ahmad
    </footer>
</body>
</html>
