---
layout: default
title: Data Analysis
---

<script src="https://cdn.tailwindcss.com"></script>
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
  body {
    background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 50%, #0f172a 100%) !important;
    color: #f8fafc !important;
    font-family: ui-sans-serif, system-ui, sans-serif !important;
  }
  .glass-card {
    background: rgba(255, 255, 255, 0.03);
    backdrop-filter: blur(12px);
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
  }
</style>

<div class="max-w-4xl mx-auto px-6 py-16 space-y-10">

  <div class="border-b border-white/10 pb-6" data-aos="fade-down">
    <h1 class="text-4xl font-extrabold tracking-tight">
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">📊 Data Analysis for Operations</span>
    </h1>
    <p class="text-slate-300 text-base mt-4 text-justify leading-relaxed">
      Data is the backbone of process optimization. My approach focuses on transforming raw operational data into strategic insights.
    </p>
  </div>

  <section class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-up">
    <h2 class="text-xl font-bold">
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">🔬 Analytical Skills</span>
    </h2>
    <ul class="space-y-3 text-sm md:text-base text-slate-200 text-justify">
      <li class="flex items-start gap-2">
        <span class="text-yellow-400 mt-1">▪</span>
        <span><strong>Descriptive Analytics:</strong> Visualizing historical performance (KPIs).</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-yellow-400 mt-1">▪</span>
        <span><strong>Root Cause Analysis:</strong> Using data to identify why bottlenecks occur.</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-yellow-400 mt-1">▪</span>
        <span><strong>Predictive Modeling:</strong> Forecasting demand and resource requirements.</span>
      </li>
    </ul>
  </section>

  <section class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-up" data-aos-delay="100">
    <h2 class="text-xl font-bold">
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">📁 Technical Projects</span>
    </h2>
    <ul class="space-y-2 text-sm text-slate-300">
      <li class="flex items-center gap-2 italic text-slate-400">
        <i class="fa-solid fa-hourglass-half text-yellow-400"></i> Inventory Analysis Script – A Python-based approach to stock optimization. (Coming Soon)
      </li>
      <li class="flex items-center gap-2 italic text-slate-400">
        <i class="fa-solid fa-hourglass-half text-yellow-400"></i> SQL Queries for Production – Database management for shop floor tracking. (Coming Soon)
      </li>
    </ul>
  </section>

  <div class="pt-4" data-aos="fade-up" data-aos-delay="200">
    <a href="./index.html" class="inline-flex items-center gap-2 text-sm font-semibold text-cyan-400 hover:underline transition">
      <i class="fa-solid fa-arrow-left-long"></i> Back to Home
    </a>
  </div>

</div>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>AOS.init({ duration: 800, once: true });</script>
