---
layout: default
title: Process Management Portfolio
---

<script src="https://cdn.tailwindcss.com"></script>
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link rel="shortcut icon" type="image/png" href="https://github.com/wero-git/Winston_Engamba/blob/main/favicon-32x32.png?raw=true">

<style>
  /* Theme*/
  body {
    background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 50%, #0f172a 100%) !important;
    color: #f8fafc !important;
  }
  /* (Glassmorphism) */
  .glass-card {
    background: rgba(255, 255, 255, 0.03);
    backdrop-filter: blur(12px);
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
  }
</style>

<header class="pt-24 pb-16 px-6 max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-8 border-b border-white/10">
  <div class="flex-1 space-y-4 text-center md:text-left" data-aos="fade-right">
    <h1 class="text-4xl md:text-5xl font-extrabold tracking-tight text-white text-center md:text-center">
       <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">Hi, I'm Winston Engamba</span>
    </h1>
    <p class="text-xl font-medium text-cyan-400 text-center md:text-center">Process Management | Digitization | Optimization</p> 
    <p class="text-slate-300 text-base max-w-xl leading-relaxed text-justify mx-auto md:mx-auto">
      Welcome to my Portfolio. I am a results-driven student with a passion for industrial efficiency, focusing on bridging the gap between traditional operations and digital innovation.
    </p>
  </div>
  
  <div class="flex-1 flex justify-center" data-aos="fade-left">
    <img src="https://github.com/wero-git/Winston_Engamba/blob/main/images/tech_dna_process_fusion.png?raw=true" alt="Process DNA" class="w-full max-w-sm rounded-2xl drop-shadow-[0_0_25px_rgba(6,182,212,0.25)]">
  </div>
</header>

<main class="py-12 px-6 max-w-6xl mx-auto space-y-12">

  <div class="grid md:grid-cols-2 gap-8">
    <section class="glass-card p-6 rounded-xl space-y-3" data-aos="fade-up">
      <h3 class="text-xl font-bold flex items-center gap-2">
        <i class="fa-solid fa-user text-cyan-400"></i>
        <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">About Me</span>
      </h3>
      <p class="text-slate-200 text-sm leading-relaxed text-justify">
        My objective is to master the tools that transform raw data into optimized workflows. Focused on Lean Manufacturing, Supply Chain Optimization, and Advanced Process Modeling.
      </p>
    </section>
    <section class="glass-card p-6 rounded-xl space-y-3" data-aos="fade-up" data-aos-delay="100">
      <h3 class="text-xl font-bold flex items-center gap-2">
        <i class="fa-solid fa-screwdriver-wrench text-teal-400"></i>
        <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">Toolbox</span>
      </h3>
      <div class="text-sm space-y-1.5 text-slate-200 text-justify">
        <p><strong>Optimization:</strong> Docker, Value Stream Mapping (VSM).</p>
        <p><strong>Modeling:</strong> BPMN 2.0 (Bizagi / Signavio).</p>
        <p><strong>Technical:</strong> Python for Data, Excel VBA, SQL basics.</p>
      </div>
    </section>
  </div>

  <section class="space-y-6">
    <h3 class="text-2xl font-bold text-center text-white" data-aos="fade-up">Explore My Work</h3>   
    <div class="grid md:grid-cols-3 gap-6">
      <div class="glass-card p-6 rounded-xl space-y-3 flex flex-col justify-between" data-aos="zoom-in">
        <div>
          <span class="text-3xl text-cyan-400"><i class="fa-solid fa-network-wired"></i></span>
          <h4 class="text-lg font-bold mt-2">
            <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">Process Digitization</span>
          </h4>
          <p class="text-slate-300 text-xs leading-relaxed mt-1 text-justify">Transitioning to automated, paperless, and synchronized operational workflows.</p>
        </div>
        <a href="./numerisation.html" class="inline-block text-xs font-semibold text-cyan-400 hover:underline pt-2">View Projects →</a>
      </div>
      <div class="glass-card p-6 rounded-xl space-y-3 flex flex-col justify-between" data-aos="zoom-in" data-aos-delay="100">
        <div>
          <span class="text-3xl text-emerald-400"><i class="fa-solid fa-chart-line"></i></span>
          <h4 class="text-lg font-bold mt-2">
            <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">Process Optimization</span>
          </h4>
          <p class="text-slate-300 text-xs leading-relaxed mt-1 text-justify">Applying Lean methodologies, removing waste, and accelerating process execution.</p>
        </div>
        <a href="./optimization.html" class="inline-block text-xs font-semibold text-emerald-400 hover:underline pt-2">View Case Studies →</a>
      </div>
      <div class="glass-card p-6 rounded-xl space-y-3 flex flex-col justify-between" data-aos="zoom-in" data-aos-delay="200">
        <div>
          <span class="text-3xl text-yellow-400"><i class="fa-solid fa-chart-pie"></i></span>
          <h4 class="text-lg font-bold mt-2">
            <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">Data Analysis</span>
          </h4>
          <p class="text-slate-300 text-xs leading-relaxed mt-1 text-justify">Turning raw industrial and shop floor data into sharp, actionable business insights.</p>
        </div>
        <a href="./data_analysis.html" class="inline-block text-xs font-semibold text-yellow-400 hover:underline pt-2">View Insights →</a>
      </div>
    </div>
  </section>
</main>

<footer id="contact" class="py-16 px-6 max-w-5xl mx-auto space-y-12 border-t border-white/10">
  <div class="text-center space-y-2" data-aos="zoom-in">
    <h2 class="text-3xl font-extrabold">
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">Get In Touch</span>
    </h2>
    <p class="text-slate-400 text-sm">Have an opportunity or want to discuss process automation? Let's connect!</p>
  </div>

  <div class="grid md:grid-cols-2 gap-8">
    <div class="glass-card p-6 rounded-xl flex flex-col justify-between space-y-6" data-aos="fade-right">
      <div>
        <h3 class="text-lg font-semibold mb-2 text-white">Connect with me</h3>
        <p class="text-sm text-slate-400 text-justify">Feel free to access my professional networks, check out active repositories, or drop an email regarding projects.</p>
      </div>
      <div class="flex space-x-6 text-3xl text-slate-300">
        <a href="https://github.com/wero-git" class="hover:text-cyan-400 transition"><i class="fab fa-github"></i></a>
        <a href="www.linkedin.com/in/winston-engamba-7b3489325" class="hover:text-blue-500 transition"><i class="fab fa-linkedin"></i></a>
        <a href="mailto:rodokomon24@gmail.com" class="hover:text-teal-400 transition"><i class="fas fa-envelope"></i></a>
      </div>
      <p class="text-xs text-slate-500 font-mono">Designed by Winston Engamba © 2026</p>
    </div>
    <form class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-left">
      <div>
        <label class="block text-xs uppercase text-slate-400 mb-1">Your Name</label>
        <input type="text" class="w-full bg-slate-900 border border-white/10 rounded p-2 text-sm focus:border-cyan-500 outline-none text-white">
      </div>
      <div>
        <label class="block text-xs uppercase text-slate-400 mb-1">Your Email</label>
        <input type="email" class="w-full bg-slate-900 border border-white/10 rounded p-2 text-sm focus:border-cyan-500 outline-none text-white">
      </div>
      <div>
        <label class="block text-xs uppercase text-slate-400 mb-1">Message</label>
        <textarea rows="3" class="w-full bg-slate-900 border border-white/10 rounded p-2 text-sm focus:border-cyan-500 outline-none text-white"></textarea>
      </div>
      <button type="submit" class="w-full py-2 rounded bg-gradient-to-r from-cyan-500 to-blue-600 hover:opacity-90 font-medium text-sm transition text-white">Send Message</button>
    </form>
  </div>
</footer>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>AOS.init({ duration: 800, once: true });</script>
