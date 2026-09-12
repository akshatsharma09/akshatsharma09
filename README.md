<!DOCTYPE html>
<html lang="en" class="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Akshat Sharma — Modern Developer Portfolio & GitHub Profile</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: {
              cyan: '#38bdf8',
              blue: '#6366f1',
              emerald: '#10b981',
              dark: '#0B0F17',
              card: '#111726',
              border: '#1E293B',
              muted: '#94A3B8'
            }
          },
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
            mono: ['JetBrains Mono', 'Fira Code', 'monospace']
          }
        }
      }
    }
  </script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #080C14;
      color: #E2E8F0;
      font-family: 'Inter', sans-serif;
    }
    .code-badge {
      font-family: 'JetBrains Mono', monospace;
      font-size: 0.75rem;
    }
    .grid-bg {
      background-size: 40px 40px;
      background-image: 
        linear-gradient(to right, rgba(255, 255, 255, 0.025) 1px, transparent 1px),
        linear-gradient(to bottom, rgba(255, 255, 255, 0.025) 1px, transparent 1px);
    }
    .custom-scroll::-webkit-scrollbar {
      width: 6px;
    }
    .custom-scroll::-webkit-scrollbar-thumb {
      background: #1E293B;
      border-radius: 4px;
    }
  </style>
</head>
<body class="min-h-screen text-slate-200 antialiased selection:bg-sky-500/30 selection:text-sky-200">
  
  <!-- Subtle Top Banner Status -->
  <header class="border-b border-slate-800/80 bg-slate-950/60 backdrop-blur sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 h-14 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="w-2.5 h-2.5 rounded-full bg-emerald-400 animate-pulse ring-4 ring-emerald-400/20"></div>
        <span class="text-xs font-mono text-slate-300">akshat-sharma / <span class="text-white font-semibold">README.md</span></span>
      </div>

      <div class="flex items-center gap-2 sm:gap-4 text-xs font-mono">
        <span class="hidden md:inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-slate-900 border border-slate-800 text-slate-400">
          <span class="w-1.5 h-1.5 rounded-full bg-sky-400"></span> Available for AI/ML & SDE Roles
        </span>
        <button onclick="navigator.clipboard.writeText('Building intelligent systems. Solving problems. Learning in public.'); alert('Tagline copied!')" 
                class="px-2.5 py-1 rounded bg-slate-800/80 hover:bg-slate-700 text-slate-200 transition border border-slate-700/60 flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"></path></svg>
          <span class="hidden sm:inline">Copy Tagline</span>
        </button>
      </div>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-4 sm:px-6 py-8 md:py-12 space-y-12">

    <!-- HERO SECTION -->
    <section class="relative rounded-2xl border border-slate-800/90 bg-gradient-to-b from-[#0E1524] to-[#0A0E18] p-6 sm:p-10 overflow-hidden shadow-2xl">
      <!-- Glow effect -->
      <div class="absolute -top-24 -right-24 w-96 h-96 bg-sky-500/10 rounded-full blur-3xl pointer-events-none"></div>
      <div class="absolute -bottom-24 -left-24 w-96 h-96 bg-indigo-500/10 rounded-full blur-3xl pointer-events-none"></div>

      <div class="relative z-10 flex flex-col md:flex-row md:items-start justify-between gap-8">
        <div class="space-y-4 max-w-2xl">
          <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-slate-900/90 border border-sky-500/30 text-sky-400 text-xs font-mono">
            <span class="animate-ping w-1.5 h-1.5 rounded-full bg-sky-400"></span>
            Building intelligent systems. Solving problems. Learning in public.
          </div>

          <div class="space-y-1">
            <h1 class="text-3xl sm:text-4xl lg:text-5xl font-bold tracking-tight text-white flex items-center gap-3">
              Akshat Sharma
              <span class="text-xs px-2 py-0.5 rounded bg-slate-800 text-slate-300 font-mono font-normal border border-slate-700">HE/HIM</span>
            </h1>
            <p class="text-lg sm:text-xl font-medium text-slate-300">
              AI/ML Developer <span class="text-sky-400">·</span> Software Engineer <span class="text-sky-400">·</span> Problem Solver
            </p>
          </div>

          <p class="text-slate-400 text-sm sm:text-base leading-relaxed">
            I engineer practical machine learning pipelines and resilient full-stack web applications. Passionate about solving complex algorithmic challenges, analyzing security datasets, and exploring modern architectures across the MERN stack and applied AI.
          </p>

          <!-- Quick Action Links -->
          <div class="pt-2 flex flex-wrap items-center gap-3 font-mono text-xs">
            <a href="https://github.com" target="_blank" class="inline-flex items-center gap-2 px-3.5 py-2 rounded-lg bg-slate-800/90 hover:bg-slate-700 border border-slate-700 text-white transition">
              <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
              github.com/akshat-sharma
            </a>
            <a href="https://leetcode.com" target="_blank" class="inline-flex items-center gap-2 px-3.5 py-2 rounded-lg bg-amber-500/10 hover:bg-amber-500/20 border border-amber-500/30 text-amber-300 transition">
              <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M13.483 0a1.374 1.374 0 0 0-.961.438L7.116 6.226l-3.854 4.126a5.266 5.266 0 0 0-1.209 2.104 5.35 5.35 0 0 0-.125.513 5.527 5.527 0 0 0 .062 2.362 5.83 5.83 0 0 0 .349 1.017 5.938 5.938 0 0 0 4.818 3.535 5.925 5.925 0 0 0 3.344-.658l6.777-4.108a1.375 1.375 0 0 0 .285-2.223 1.376 1.376 0 0 0-1.938.285l-6.78 4.108a3.18 3.18 0 0 1-1.79.352 3.193 3.193 0 0 1-2.593-1.902 3.167 3.167 0 0 1-.225-1.282 3.16 3.16 0 0 1 .632-1.892l3.854-4.126 5.406-5.788A1.374 1.374 0 0 0 13.483 0zm-2.88 7.283a1.374 1.374 0 0 0-.97 2.348l3.854 4.126a1.374 1.374 0 1 0 2.007-1.874l-3.854-4.126a1.374 1.374 0 0 0-1.037-.474z"/></svg>
              LeetCode (300+ Solved)
            </a>
            <a href="https://linkedin.com" target="_blank" class="inline-flex items-center gap-2 px-3.5 py-2 rounded-lg bg-sky-500/10 hover:bg-sky-500/20 border border-sky-500/30 text-sky-300 transition">
              <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
              LinkedIn Profile
            </a>
          </div>
        </div>

        <!-- Quick Summary Metrics Card -->
        <div class="w-full md:w-72 bg-slate-900/80 rounded-xl p-4 border border-slate-800 font-mono text-xs space-y-3">
          <div class="flex items-center justify-between pb-2 border-b border-slate-800 text-slate-400">
            <span>// PROFILE_INDEX</span>
            <span class="text-sky-400">v2.4_2025</span>
          </div>
          <div class="space-y-2 text-slate-300">
            <div class="flex justify-between">
              <span class="text-slate-500">Focus:</span>
              <span class="text-white font-medium">AI/ML + Full Stack</span>
            </div>
            <div class="flex justify-between">
              <span class="text-slate-500">DSA Stack:</span>
              <span class="text-emerald-400">Java (300+ solved)</span>
            </div>
            <div class="flex justify-between">
              <span class="text-slate-500">Research:</span>
              <span class="text-slate-200">MNNIT Allahabad</span>
            </div>
            <div class="flex justify-between">
              <span class="text-slate-500">Academics:</span>
              <span class="text-amber-300">Rank 2 (B.Tech Y1)</span>
            </div>
          </div>
          <div class="pt-2 border-t border-slate-800 text-[11px] text-slate-400 leading-tight">
            ⚡ Exploring MERN stack integration with applied machine learning pipelines.
          </div>
        </div>
      </div>
    </section>

    <!-- CURRENT FOCUS PILLS -->
    <section class="space-y-3">
      <div class="flex items-center gap-2 text-xs font-mono text-slate-400 uppercase tracking-wider">
        <span class="text-sky-400 font-bold">#</span> 01. Domain Focus & Specialties
      </div>
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3">
        <div class="p-3.5 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-sky-500/40 transition">
          <div class="text-sky-400 mb-1 text-sm">🤖</div>
          <div class="font-semibold text-sm text-slate-200">AI & Applied ML</div>
          <div class="text-xs text-slate-500 mt-1 font-mono">Scikit-learn, RDKit, CV</div>
        </div>
        <div class="p-3.5 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-indigo-500/40 transition">
          <div class="text-indigo-400 mb-1 text-sm">⚡</div>
          <div class="font-semibold text-sm text-slate-200">Full-Stack Web</div>
          <div class="text-xs text-slate-500 mt-1 font-mono">FastAPI, React, MERN</div>
        </div>
        <div class="p-3.5 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-emerald-500/40 transition">
          <div class="text-emerald-400 mb-1 text-sm">🧠</div>
          <div class="font-semibold text-sm text-slate-200">DSA & Algorithms</div>
          <div class="text-xs text-slate-500 mt-1 font-mono">Java, 300+ LeetCode</div>
        </div>
        <div class="p-3.5 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-amber-500/40 transition">
          <div class="text-amber-400 mb-1 text-sm">🔬</div>
          <div class="font-semibold text-sm text-slate-200">ML Research</div>
          <div class="text-xs text-slate-500 mt-1 font-mono">NIDS, SMOTE, Class Imbalance</div>
        </div>
        <div class="p-3.5 rounded-xl bg-slate-900/60 border border-slate-800 hover:border-purple-500/40 transition">
          <div class="text-purple-400 mb-1 text-sm">☁️</div>
          <div class="font-semibold text-sm text-slate-200">Cloud & Tooling</div>
          <div class="text-xs text-slate-500 mt-1 font-mono">Azure, Git, Linux</div>
        </div>
      </div>
    </section>

    <!-- FEATURED PROJECTS -->
    <section class="space-y-4">
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-2 text-xs font-mono text-slate-400 uppercase tracking-wider">
          <span class="text-sky-400 font-bold">#</span> 02. Featured Engineering Work
        </div>
        <span class="text-xs font-mono text-slate-500">4 Featured Systems</span>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-5">

        <!-- Project 1: Yojana Darpan -->
        <div class="rounded-xl border border-slate-800 bg-[#0D1322] p-5 flex flex-col justify-between hover:border-slate-700 transition group">
          <div class="space-y-3">
            <div class="flex items-start justify-between gap-4">
              <div>
                <span class="text-xs font-mono text-sky-400">Public Policy AI Engine</span>
                <h3 class="text-lg font-bold text-white group-hover:text-sky-300 transition">Yojana Darpan</h3>
              </div>
              <span class="px-2 py-0.5 rounded text-[11px] font-mono bg-sky-950 text-sky-400 border border-sky-800">Production Ready</span>
            </div>
            <p class="text-xs font-mono text-slate-400">Problem: Complex government criteria make discovering citizen eligibility inefficient and error-prone.</p>
            <p class="text-slate-300 text-sm leading-relaxed">
              Engineered an intelligent eligibility determination system using fast multi-attribute evaluation algorithms. Evaluates demographic, socioeconomic, and regional qualifiers to deliver instant policy recommendations and benefit breakdowns.
            </p>
            <div class="flex flex-wrap gap-1.5 pt-2">
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">FastAPI</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">React</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Tailwind CSS</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Python</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Scikit-learn</span>
            </div>
          </div>
          <div class="pt-5 mt-4 border-t border-slate-800/80 flex items-center justify-between text-xs font-mono">
            <a href="#" class="text-slate-300 hover:text-white flex items-center gap-1.5 transition">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"/></svg>
              View Repository
            </a>
            <span class="text-slate-500">REST API · AI Engine</span>
          </div>
        </div>

        <!-- Project 2: DrugSafe -->
        <div class="rounded-xl border border-slate-800 bg-[#0D1322] p-5 flex flex-col justify-between hover:border-slate-700 transition group">
          <div class="space-y-3">
            <div class="flex items-start justify-between gap-4">
              <div>
                <span class="text-xs font-mono text-emerald-400">Cheminformatics & Healthcare</span>
                <h3 class="text-lg font-bold text-white group-hover:text-emerald-300 transition">DrugSafe</h3>
              </div>
              <span class="px-2 py-0.5 rounded text-[11px] font-mono bg-emerald-950 text-emerald-400 border border-emerald-800">ML Classifier</span>
            </div>
            <p class="text-xs font-mono text-slate-400">Problem: Polypharmacy adverse interactions are hard to diagnose without molecular modeling.</p>
            <p class="text-slate-300 text-sm leading-relaxed">
              Developed a predictive drug-drug interaction and severity analysis system. Utilizes molecular fingerprint extraction via RDKit to compute chemical similarity matrices and forecast contraindication hazard levels before prescription execution.
            </p>
            <div class="flex flex-wrap gap-1.5 pt-2">
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">RDKit</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Scikit-learn</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">FastAPI</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">React JS</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Pandas</span>
            </div>
          </div>
          <div class="pt-5 mt-4 border-t border-slate-800/80 flex items-center justify-between text-xs font-mono">
            <a href="#" class="text-slate-300 hover:text-white flex items-center gap-1.5 transition">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"/></svg>
              View Repository
            </a>
            <span class="text-slate-500">Cheminformatics · ML</span>
          </div>
        </div>

        <!-- Project 3: Sign Language Detection -->
        <div class="rounded-xl border border-slate-800 bg-[#0D1322] p-5 flex flex-col justify-between hover:border-slate-700 transition group">
          <div class="space-y-3">
            <div class="flex items-start justify-between gap-4">
              <div>
                <span class="text-xs font-mono text-purple-400">Computer Vision · Edge AI</span>
                <h3 class="text-lg font-bold text-white group-hover:text-purple-300 transition">Sign Language Detection</h3>
              </div>
              <span class="px-2 py-0.5 rounded text-[11px] font-mono bg-purple-950 text-purple-400 border border-purple-800">Azure AI Intern Project</span>
            </div>
            <p class="text-xs font-mono text-slate-400">Problem: Communication barrier for speech and hearing impaired individuals in digital spaces.</p>
            <p class="text-slate-300 text-sm leading-relaxed">
              Spatial landmark tracking and gesture recognition model built during an Azure AI internship. Tracks multi-frame hand kinematic joints to classify sign gestures in real time with low latency inference.
            </p>
            <div class="flex flex-wrap gap-1.5 pt-2">
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Computer Vision</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Azure AI</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Python</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">OpenCV</span>
            </div>
          </div>
          <div class="pt-5 mt-4 border-t border-slate-800/80 flex items-center justify-between text-xs font-mono">
            <a href="#" class="text-slate-300 hover:text-white flex items-center gap-1.5 transition">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"/></svg>
              View Repository
            </a>
            <span class="text-slate-500">Vision Pipeline</span>
          </div>
        </div>

        <!-- Project 4: Vulnerability Scanner -->
        <div class="rounded-xl border border-slate-800 bg-[#0D1322] p-5 flex flex-col justify-between hover:border-slate-700 transition group">
          <div class="space-y-3">
            <div class="flex items-start justify-between gap-4">
              <div>
                <span class="text-xs font-mono text-amber-400">Cybersecurity · Network Auditing</span>
                <h3 class="text-lg font-bold text-white group-hover:text-amber-300 transition">Vulnerability Scanner</h3>
              </div>
              <span class="px-2 py-0.5 rounded text-[11px] font-mono bg-amber-950 text-amber-400 border border-amber-800">Hackathon Build</span>
            </div>
            <p class="text-xs font-mono text-slate-400">Problem: Unmonitored attack surfaces and stale port configurations expose network infrastructure.</p>
            <p class="text-slate-300 text-sm leading-relaxed">
              Automated penetration testing utility that probes open ports, inspects protocol banner headers, and matches detected service versions against common CVE indices to identify attack vectors.
            </p>
            <div class="flex flex-wrap gap-1.5 pt-2">
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Python</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Network Sockets</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">Security Audit</span>
              <span class="px-2 py-0.5 rounded bg-slate-800/80 text-slate-300 text-xs font-mono">CVE Matching</span>
            </div>
          </div>
          <div class="pt-5 mt-4 border-t border-slate-800/80 flex items-center justify-between text-xs font-mono">
            <a href="#" class="text-slate-300 hover:text-white flex items-center gap-1.5 transition">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"/></svg>
              View Repository
            </a>
            <span class="text-slate-500">Network Security</span>
          </div>
        </div>

      </div>
    </section>

    <!-- RESEARCH & INTERNSHIP -->
    <section class="rounded-xl border border-slate-800 bg-[#0B101D] p-6 sm:p-8 space-y-6">
      <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 border-b border-slate-800 pb-4">
        <div>
          <div class="flex items-center gap-2 text-xs font-mono text-sky-400 uppercase tracking-wider">
            <span>#</span> 03. Research Experience
          </div>
          <h2 class="text-xl font-bold text-white mt-1">Machine Learning for Intrusion Detection Systems</h2>
          <p class="text-xs font-mono text-slate-400">Motilal Nehru National Institute of Technology (MNNIT) Allahabad · Research Intern</p>
        </div>
        <span class="px-3 py-1 rounded-full text-xs font-mono bg-sky-950/70 text-sky-300 border border-sky-800 w-fit">
          Datasets: CICIDS2017 & CSE-CICIDS2018
        </span>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="p-4 rounded-lg bg-slate-900/80 border border-slate-800/90 space-y-2">
          <div class="text-xs font-mono text-sky-400">01 / Imbalance Mitigation</div>
          <h4 class="font-semibold text-slate-200 text-sm">SMOTE & Resampling</h4>
          <p class="text-xs text-slate-400 leading-relaxed">
            Evaluated skewed minority-class network intrusion instances using ADASYN, SMOTE, and SMOTE-Tomek to preserve boundary decision margins without overfitting.
          </p>
        </div>

        <div class="p-4 rounded-lg bg-slate-900/80 border border-slate-800/90 space-y-2">
          <div class="text-xs font-mono text-indigo-400">02 / Architecture Benchmarking</div>
          <h4 class="font-semibold text-slate-200 text-sm">Random Forest & CNN</h4>
          <p class="text-xs text-slate-400 leading-relaxed">
            Trained ensemble decision trees against 1D Convolutional Neural Networks, measuring latency-accuracy trade-offs across packet capture payloads.
          </p>
        </div>

        <div class="p-4 rounded-lg bg-slate-900/80 border border-slate-800/90 space-y-2">
          <div class="text-xs font-mono text-emerald-400">03 / Transfer Generalization</div>
          <h4 class="font-semibold text-slate-200 text-sm">Cross-Dataset Validation</h4>
          <p class="text-xs text-slate-400 leading-relaxed">
            Investigated cross-environment domain shifts between CICIDS2017 and CSE-CICIDS2018 to ensure real-world intrusion resilience beyond a single simulated topology.
          </p>
        </div>
      </div>
    </section>

    <!-- TECH STACK & PROBLEM SOLVING TWO-COLUMN -->
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">

      <!-- Tech Stack (7 cols) -->
      <section class="lg:col-span-7 rounded-xl border border-slate-800 bg-[#0B101D] p-6 space-y-5">
        <div class="flex items-center justify-between">
          <div class="flex items-center gap-2 text-xs font-mono text-slate-400 uppercase tracking-wider">
            <span class="text-sky-400 font-bold">#</span> 04. Technical Toolchain
          </div>
          <span class="text-xs font-mono text-slate-500">Categorized</span>
        </div>

        <div class="space-y-4 text-xs font-mono">
          <!-- Languages -->
          <div>
            <div class="text-slate-400 mb-2 flex items-center gap-1.5">
              <span class="w-1.5 h-1.5 rounded-full bg-sky-400"></span> Languages
            </div>
            <div class="flex flex-wrap gap-2">
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">C</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">C++</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-emerald-500/40 text-emerald-300 font-semibold">Java (DSA Main)</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-sky-500/40 text-sky-300">Python</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">JavaScript (ES6+)</span>
            </div>
          </div>

          <!-- AI / ML -->
          <div>
            <div class="text-slate-400 mb-2 flex items-center gap-1.5">
              <span class="w-1.5 h-1.5 rounded-full bg-indigo-400"></span> AI & Machine Learning
            </div>
            <div class="flex flex-wrap gap-2">
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">Scikit-learn</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">Pandas</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">NumPy</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">RDKit</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">Data Analysis</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">Model Evaluation</span>
            </div>
          </div>

          <!-- Web & Frameworks -->
          <div>
            <div class="text-slate-400 mb-2 flex items-center gap-1.5">
              <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span> Web & Backend
            </div>
            <div class="flex flex-wrap gap-2">
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">React JS</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-sky-500/40 text-sky-300">FastAPI</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">Tailwind CSS</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">Node / Express</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">REST APIs</span>
            </div>
          </div>

          <!-- Tools & Cloud -->
          <div>
            <div class="text-slate-400 mb-2 flex items-center gap-1.5">
              <span class="w-1.5 h-1.5 rounded-full bg-amber-400"></span> Cloud & Developer Tools
            </div>
            <div class="flex flex-wrap gap-2">
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">Git</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">GitHub</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-sky-500/40 text-sky-300">Microsoft Azure</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">VS Code</span>
              <span class="px-2.5 py-1 rounded bg-slate-900 border border-slate-800 text-slate-200">Linux / Shell</span>
            </div>
          </div>
        </div>
      </section>

      <!-- Problem Solving & DSA (5 cols) -->
      <section class="lg:col-span-5 rounded-xl border border-slate-800 bg-[#0B101D] p-6 space-y-5 flex flex-col justify-between">
        <div>
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-2 text-xs font-mono text-slate-400 uppercase tracking-wider">
              <span class="text-emerald-400 font-bold">#</span> 05. Algorithmic Mastery
            </div>
            <span class="text-xs font-mono text-emerald-400">300+ Solved</span>
          </div>

          <div class="mt-4 space-y-4">
            <div class="p-4 rounded-lg bg-slate-900/90 border border-slate-800">
              <div class="flex items-center justify-between text-xs font-mono mb-2">
                <span class="text-slate-400">Primary Language:</span>
                <span class="text-emerald-400 font-semibold">Java</span>
              </div>
              <div class="flex items-center justify-between text-xs font-mono mb-2">
                <span class="text-slate-400">Platforms:</span>
                <span class="text-white">LeetCode · GeeksforGeeks</span>
              </div>
              <div class="flex items-center justify-between text-xs font-mono">
                <span class="text-slate-400">Focus:</span>
                <span class="text-sky-300">Graphs, DP & Optimization</span>
              </div>
            </div>

            <p class="text-xs text-slate-400 leading-relaxed">
              Consistently practicing data structures and algorithmic efficiency: graph traversal patterns, recursive state transitions, tree balancing, sliding window, and two-pointer optimizations.
            </p>
          </div>
        </div>

        <div class="pt-4 border-t border-slate-800/80">
          <a href="https://leetcode.com" target="_blank" class="w-full inline-flex items-center justify-center gap-2 px-3 py-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-700 text-xs font-mono text-slate-200 transition">
            Inspect Problem Solving Profile →
          </a>
        </div>
      </section>
    </div>

    <!-- HACKATHONS & ACHIEVEMENTS -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">

      <!-- Hackathons -->
      <section class="rounded-xl border border-slate-800 bg-[#0B101D] p-6 space-y-4">
        <div class="flex items-center gap-2 text-xs font-mono text-slate-400 uppercase tracking-wider">
          <span class="text-sky-400 font-bold">#</span> 06. Hackathons & Competitions
        </div>

        <ul class="space-y-3 text-xs font-mono">
          <li class="p-3 rounded-lg bg-slate-900/60 border border-slate-800/80 flex items-start justify-between gap-3">
            <div>
              <div class="font-semibold text-white">Smart India Hackathon (SIH)</div>
              <div class="text-slate-400 mt-0.5">National level government and public enterprise problem-solving.</div>
            </div>
            <span class="text-sky-400 text-[11px]">Participant</span>
          </li>
          <li class="p-3 rounded-lg bg-slate-900/60 border border-slate-800/80 flex items-start justify-between gap-3">
            <div>
              <div class="font-semibold text-white">Code for Bharat & Naukri Campus Contest</div>
              <div class="text-slate-400 mt-0.5">Applied engineering sprints and high-concurrency coding rounds.</div>
            </div>
            <span class="text-emerald-400 text-[11px]">Sprint</span>
          </li>
          <li class="p-3 rounded-lg bg-slate-900/60 border border-slate-800/80 flex items-start justify-between gap-3">
            <div>
              <div class="font-semibold text-white">Code Clash 2.0 & Season 2 Tech Masters India</div>
              <div class="text-slate-400 mt-0.5">Speed algorithms, bug squashing, and rapid prototype delivery.</div>
            </div>
            <span class="text-purple-400 text-[11px]">Finalist</span>
          </li>
        </ul>
      </section>

      <!-- Key Honors & Achievements -->
      <section class="rounded-xl border border-slate-800 bg-[#0B101D] p-6 space-y-4">
        <div class="flex items-center gap-2 text-xs font-mono text-slate-400 uppercase tracking-wider">
          <span class="text-amber-400 font-bold">#</span> 07. Honors & Milestones
        </div>

        <ul class="space-y-3 text-xs font-mono">
          <li class="p-3 rounded-lg bg-slate-900/60 border border-amber-500/30 flex items-start gap-3">
            <span class="text-amber-400 font-bold text-sm">01</span>
            <div>
              <div class="font-semibold text-white">Rank 2 — Department B.Tech 1st Year</div>
              <div class="text-slate-400 mt-0.5">Academic distinction across foundational engineering sciences.</div>
            </div>
          </li>
          <li class="p-3 rounded-lg bg-slate-900/60 border border-slate-800/80 flex items-start gap-3">
            <span class="text-sky-400 font-bold text-sm">02</span>
            <div>
              <div class="font-semibold text-white">Top 10 / 300+ Delegation Representative</div>
              <div class="text-slate-400 mt-0.5">Selected to represent UIT at the International Innovation Camp, AIT Bangkok.</div>
            </div>
          </li>
          <li class="p-3 rounded-lg bg-slate-900/60 border border-slate-800/80 flex items-start gap-3">
            <span class="text-emerald-400 font-bold text-sm">03</span>
            <div>
              <div class="font-semibold text-white">300+ Verified Algorithmic Solutions</div>
              <div class="text-slate-400 mt-0.5">Rigorous practice across data structures, optimizations, and DP.</div>
            </div>
          </li>
        </ul>
      </section>

    </div>

    <!-- CERTIFICATIONS & CREDENTIALS -->
    <section class="rounded-xl border border-slate-800 bg-[#0B101D] p-6 space-y-4">
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-2 text-xs font-mono text-slate-400 uppercase tracking-wider">
          <span class="text-sky-400 font-bold">#</span> 08. Verified Certifications
        </div>
        <span class="text-xs font-mono text-slate-500">Technical Credentials</span>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3 text-xs font-mono">
        <div class="p-3 rounded-lg bg-slate-900/80 border border-slate-800">
          <div class="text-slate-500 text-[10px]">NPTEL IIT Madras</div>
          <div class="font-semibold text-slate-200 mt-1">Machine Learning</div>
          <div class="text-[11px] text-sky-400 mt-1">Core Theory & Models</div>
        </div>
        <div class="p-3 rounded-lg bg-slate-900/80 border border-slate-800">
          <div class="text-slate-500 text-[10px]">IBM</div>
          <div class="font-semibold text-slate-200 mt-1">Generative AI</div>
          <div class="text-[11px] text-indigo-400 mt-1">Prompt Eng & LLM Apps</div>
        </div>
        <div class="p-3 rounded-lg bg-slate-900/80 border border-slate-800">
          <div class="text-slate-500 text-[10px]">Infosys Springboard</div>
          <div class="font-semibold text-slate-200 mt-1">Artificial Intelligence</div>
          <div class="text-[11px] text-emerald-400 mt-1">Applied Pipelines</div>
        </div>
        <div class="p-3 rounded-lg bg-slate-900/80 border border-slate-800">
          <div class="text-slate-500 text-[10px]">Google Cloud / Gemini</div>
          <div class="font-semibold text-slate-200 mt-1">Gemini & Study Jams</div>
          <div class="text-[11px] text-amber-400 mt-1">Cloud Architecture</div>
        </div>
      </div>
    </section>

    <!-- GITHUB METRICS MOCKUP (RESTRAINED) -->
    <section class="rounded-xl border border-slate-800 bg-[#0B101D] p-6 space-y-4">
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-2 text-xs font-mono text-slate-400 uppercase tracking-wider">
          <span class="text-sky-400 font-bold">#</span> 09. GitHub Telemetry & Stats
        </div>
        <span class="text-xs font-mono text-slate-500">Recruiter-Calibrated View</span>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4 font-mono text-xs">
        <div class="p-4 rounded-lg bg-slate-900 border border-slate-800/90 space-y-2">
          <span class="text-slate-500">PRIMARY REPOSITORIES</span>
          <div class="text-2xl font-bold text-white">18+</div>
          <p class="text-slate-400 text-[11px]">Focus on clean modular micro-services and ML research reproduction.</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-900 border border-slate-800/90 space-y-2">
          <span class="text-slate-500">TOTAL COMMITS (YTD)</span>
          <div class="text-2xl font-bold text-sky-400">450+</div>
          <p class="text-slate-400 text-[11px]">Regular commits across algorithmic repositories and full-stack builds.</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-900 border border-slate-800/90 space-y-2">
          <span class="text-slate-500">TOP LANGUAGES</span>
          <div class="text-sm font-semibold text-white space-y-1 mt-1">
            <div class="flex justify-between"><span>Java</span> <span class="text-emerald-400">42%</span></div>
            <div class="flex justify-between"><span>Python</span> <span class="text-sky-400">36%</span></div>
            <div class="flex justify-between"><span>JavaScript / React</span> <span class="text-amber-400">22%</span></div>
          </div>
        </div>
      </div>
    </section>

    <!-- FOOTER / CONNECT -->
    <footer class="pt-8 border-t border-slate-800 text-center space-y-4 font-mono">
      <div class="text-sm text-slate-400">
        <code>"Build. Break. Learn. Iterate."</code>
      </div>
      <div class="flex items-center justify-center gap-6 text-xs text-slate-400">
        <a href="https://github.com" target="_blank" class="hover:text-white transition">GitHub</a>
        <span>·</span>
        <a href="https://leetcode.com" target="_blank" class="hover:text-white transition">LeetCode</a>
        <span>·</span>
        <a href="https://linkedin.com" target="_blank" class="hover:text-white transition">LinkedIn</a>
      </div>
      <div class="text-[11px] text-slate-600">
        Designed for Akshat Sharma · Clean Engineering Portfolio Standard
      </div>
    </footer>

  </main>

</body>
</html>
