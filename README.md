<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fardaus Taohyd - GitHub Profile</title>
  <!-- Load Inter font from Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <!-- Load Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Custom CSS for futuristic feel -->
  <style>
    /* Use a cool, futuristic font */
    body {
      font-family: 'Inter', sans-serif;
    }
    /* Gradient text effect for the title */
    .title-gradient {
      background: linear-gradient(90deg, #6a4c9c 0%, #17a2b8 50%, #6a4c9c 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    /* A subtle, animating background glow */
    .hero-glow {
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      z-index: -1;
      background: radial-gradient(circle, rgba(106, 76, 156, 0.1) 0%, rgba(2, 6, 23, 0) 70%);
      animation: pulse-glow 5s infinite ease-in-out;
    }
    @keyframes pulse-glow {
      0% { transform: scale(1); opacity: 0.5; }
      50% { transform: scale(1.1); opacity: 0.8; }
      100% { transform: scale(1); opacity: 0.5; }
    }
  </style>
</head>

<!-- Main container with dark background and centered content -->
<body class="bg-slate-950 text-slate-100 min-h-screen flex flex-col items-center justify-center p-4 md:p-8">

  <!-- A container for the main content with padding and rounded corners -->
  <div class="relative max-w-4xl w-full mx-auto p-6 md:p-12 bg-slate-900 rounded-3xl shadow-2xl overflow-hidden">
    <!-- Background glow element -->
    <div class="hero-glow"></div>

    <!-- Main Profile Section -->
    <div class="text-center mb-12">
      <!-- Title with a cool gradient effect -->
      <h1 class="text-5xl md:text-6xl font-extrabold title-gradient">✨ Fardaus Taohyd</h1>
      <p class="mt-4 text-xl md:text-2xl font-light text-slate-400">Designer of Ideas · Builder of Interfaces · Explorer of AI</p>

      <!-- Badge Section -->
      <div class="flex flex-wrap justify-center mt-6 gap-3">
        <span class="px-4 py-2 bg-purple-700/50 rounded-full text-sm font-semibold text-purple-200">Product Design &middot; UX/UI</span>
        <span class="px-4 py-2 bg-blue-700/50 rounded-full text-sm font-semibold text-blue-200">Frontend Dev &middot; React/Tailwind</span>
        <span class="px-4 py-2 bg-lime-700/50 rounded-full text-sm font-semibold text-lime-200">AI + UX &middot; XAI/NLP/3D</span>
      </div>
    </div>

    <!-- Separator line with a cool gradient -->
    <div class="h-0.5 w-full bg-gradient-to-r from-purple-500 via-blue-500 to-lime-500 mb-12"></div>

    <!-- Section: Who Am I? -->
    <section class="mb-12">
      <h2 class="text-3xl font-bold mb-4">🚀 Who Am I?</h2>
      <p class="text-lg text-slate-300 leading-relaxed">
        Hey there! I'm Taohyd — a curious mind at the crossroads of design, code, and AI. I believe the future of products lies in <strong class="text-white">intentional UX</strong>, <strong class="text-white">clear systems</strong>, and <strong class="text-white">human-centered AI</strong>.
      </p>
      <ul class="list-disc list-inside mt-4 text-slate-400">
        <li class="mb-2">🧠 Merging UX, AI, and 3D to push boundaries</li>
        <li class="mb-2">🔍 Researching <strong class="text-white">Explainable AI (XAI)</strong> for ethical decision-making</li>
        <li class="mb-2">💡 Designing real-world impact through side projects and case studies</li>
        <li>🌱 Always experimenting, always evolving</li>
      </ul>
    </section>

    <!-- Section: Building With -->
    <section class="mb-12">
      <h2 class="text-3xl font-bold mb-4">🛠️ Building With</h2>
      <div class="flex flex-wrap gap-4">
        <img src="https://img.shields.io/badge/Figma-black?style=flat-square&logo=figma&logoColor=white" alt="Figma" class="rounded-lg shadow-md hover:scale-105 transition-transform duration-200">
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" class="rounded-lg shadow-md hover:scale-105 transition-transform duration-200">
        <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white" alt="TailwindCSS" class="rounded-lg shadow-md hover:scale-105 transition-transform duration-200">
        <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white" alt="Three.js" class="rounded-lg shadow-md hover:scale-105 transition-transform duration-200">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" class="rounded-lg shadow-md hover:scale-105 transition-transform duration-200">
      </div>
    </section>

    <!-- Section: Spotlight Projects -->
    <section class="mb-12">
      <h2 class="text-3xl font-bold mb-4">📌 Spotlight Projects</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Project Card 1 -->
        <div class="p-6 bg-slate-800 rounded-xl border border-slate-700 shadow-md hover:bg-slate-700 transition-colors duration-200">
          <h3 class="text-xl font-semibold text-white">🪙 MetalCard</h3>
          <p class="mt-2 text-slate-400">Fintech innovation meets Islamic finance. Gold-backed debit concept with live metal rates and educational tools.</p>
        </div>
        <!-- Project Card 2 -->
        <div class="p-6 bg-slate-800 rounded-xl border border-slate-700 shadow-md hover:bg-slate-700 transition-colors duration-200">
          <h3 class="text-xl font-semibold text-white">🧠 Phishing XAI</h3>
          <p class="mt-2 text-slate-400">Research-driven phishing detection using explainable models for better cybersecurity transparency.</p>
        </div>
        <!-- Project Card 3 -->
        <div class="p-6 bg-slate-800 rounded-xl border border-slate-700 shadow-md hover:bg-slate-700 transition-colors duration-200">
          <h3 class="text-xl font-semibold text-white">🐾 PawHouse</h3>
          <p class="mt-2 text-slate-400">UX case study for a smart pet ecosystem — blending monitoring, health discovery, and local relevance.</p>
        </div>
        <!-- Project Card 4 -->
        <div class="p-6 bg-slate-800 rounded-xl border border-slate-700 shadow-md hover:bg-slate-700 transition-colors duration-200">
          <h3 class="text-xl font-semibold text-white">📱 HandyHub</h3>
          <p class="mt-2 text-slate-400">Swiss-army-style mobile app for quick access to utilities: translator, compass, weather, and more.</p>
        </div>
      </div>
    </section>

    <!-- Section: What Drives Me -->
    <section class="mb-12">
      <h2 class="text-3xl font-bold mb-4">🧭 What Drives Me</h2>
      <ul class="list-disc list-inside mt-4 text-slate-400">
        <li class="mb-2">✨ Designing for delight, not just usability</li>
        <li class="mb-2">🧬 Making AI accessible and understandable to real people</li>
        <li class="mb-2">🌍 Working with mindful, remote-first global teams</li>
        <li>🧰 Turning prototypes into purposeful products</li>
      </ul>
    </section>

    <!-- Section: Core Belief -->
    <section class="mb-12 text-center p-8 bg-slate-800 rounded-xl border border-slate-700 shadow-md">
      <p class="text-2xl font-medium italic text-slate-300 leading-relaxed">
        <span class="text-4xl font-extrabold text-blue-500">“</span>Technology should feel like magic — but work like truth.<span class="text-4xl font-extrabold text-blue-500">”</span>
      </p>
    </section>

    <!-- Section: Let's Connect -->
    <section class="mb-12">
      <h2 class="text-3xl font-bold mb-4">📬 Let's Connect</h2>
      <div class="flex flex-wrap gap-4 items-center">
        <a href="https://fardaustaohyd.github.io/fardaustaohyd-portfolio/" class="flex items-center gap-2 text-blue-400 hover:text-blue-300 transition-colors duration-200">
          <span class="text-2xl">🔗</span> Portfolio Website
        </a>
        <a href="https://www.behance.net/fardaustaohyd" class="flex items-center gap-2 text-blue-400 hover:text-blue-300 transition-colors duration-200">
          <span class="text-2xl">🎨</span> Behance
        </a>
        <a href="mailto:fardaustaohyd31@gmail.com" class="flex items-center gap-2 text-blue-400 hover:text-blue-300 transition-colors duration-200">
          <span class="text-2xl">✉️</span> fardaustaohyd31@gmail.com
        </a>
        <a href="https://drive.google.com/file/d/1YCgtftijuIcdhgDGWn_JOuKZNAy3tzIV/view?usp=drive_link" class="flex items-center gap-2 px-4 py-2 bg-blue-600 rounded-full font-semibold text-white shadow-lg hover:bg-blue-500 transition-colors duration-200">
          <img src="https://img.shields.io/badge/Download-CV-blue?style=for-the-badge&logo=adobeacrobat&logoColor=white" alt="Download CV" class="h-6"> Download CV
        </a>
      </div>
    </section>

    <!-- Final Tagline -->
    <div class="text-center mt-12 text-lg text-slate-400">
      <p><b>Curious. Focused. Future-facing.</b></p>
      <p class="mt-2 italic">Let’s create something meaningful together.</p>
    </div>
  </div>

</body>
</html>
