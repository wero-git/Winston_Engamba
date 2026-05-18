---
layout: default
title: End-to-End Claim Management Optimization
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

<div class="max-w-5xl mx-auto px-6 py-16 space-y-12">

  <div data-aos="fade-down">
    <a href="./optimization.html" class="inline-flex items-center gap-2 text-xs font-semibold text-emerald-400 hover:underline transition">
      <i class="fa-solid fa-arrow-left"></i> Back to Process Optimization
    </a>
  </div>

  <header class="border-b border-white/10 pb-8 space-y-4" data-aos="fade-down" data-aos-delay="100">
    <span class="px-3 py-1 rounded-full text-xs font-semibold bg-emerald-500/10 text-emerald-400 border border-emerald-500/20">
      Case Study Analysis
    </span>
    <h1 class="text-3xl md:text-4xl font-extrabold tracking-tight leading-tight">
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">
        End-to-End Claim Management Optimization
      </span>
    </h1>
    <p class="text-slate-400 text-sm md:text-base font-medium">
      Process Design, Structural Bottlenecks, and Automated Multi-Tiered Financial Reporting Engine
    </p>
  </header>
  
<nav class="sticky top-0 z-50 w-full backdrop-blur-md bg-slate-900/70 border-b border-b-white/10 main-container py-4">
    <div class="flex items-center justify-between px-4">
        <a href="#home" class="text-sm font-bold tracking-wider text-white hover:text-cyan-400 transition-colors uppercase">
            <span class="text-cyan-400">⚡</span> End-To-End Claims
        </a>       
        <div class="flex items-center gap-6 text-xs font-semibold uppercase tracking-wider">
            <a href="#problem-statement" class="text-slate-300 hover:text-cyan-400 transition-colors">Problem Statement</a>
            <a href="#bpmn-section" class="text-slate-300 hover:text-cyan-400 transition-colors">BPMN Process</a>
            <a href="#sql-section" class="text-slate-300 hover:text-cyan-400 transition-colors">SQL Database</a>
            <a href="#excel-section" class="text-slate-300 hover:text-cyan-400 transition-colors">Excel Results</a>
            <a href="#deliverables" class="text-slate-300 hover:text-cyan-400 transition-colors">Deliverables</a>
        </div>
    </div>
</nav>
<div id="home"></div>

  <section class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-up">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-circle-info text-cyan-400"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">Introduction & Process Description</span>
    </h2>
    <p class="text-slate-200 text-sm leading-relaxed text-justify">
      Throughout what follows, the process described is that of a customer return followed by a claim. Failures will be identified, modeled, and a proposed solution will be resolved.
    </p>
    <div class="p-4 bg-white/5 rounded-lg border border-white/5 space-y-3 text-xs md:text-sm text-slate-300 text-justify">
      <p>
        The customer submits a complaint to the company after receiving the package. Customer Service receives and reviews the claim, deciding either to initiate the return process or to escalate the matter to the Legal Department. In the event of legal action, the return procedure is immediately suspended. If the return is deemed legitimate, the customer receives an email requesting they ship the product back within 30 days; otherwise, the process is terminated and marked as aborted.
      </p>
      <p>
        Once the product is received, technicians perform a quality inspection to assess its condition. If the item is in good condition and the defect originated during production, the Accounting Department is notified to issue a full 100% refund. If the product was damaged by the customer, a notification is sent to Accounting to process a partial refund of 85%, or 70% if the product is severely damaged.
      </p>
      <p>
        Simultaneously, the technicians log the product details into the Excel database and store the item in the warehouse. Meanwhile, the accountant calculates the final refund amount and executes the payment, thus concluding the process.
      </p>
    </div>
  </section>

  <section class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-up" data-aos-delay="100">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-magnifying-glass-chart text-emerald-400"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">Interpretation of the Situation</span>
    </h2>
    <p class="text-slate-300 text-sm leading-relaxed text-justify">
      The process is structured around strict decision-making flows where technical and accounting actions are interdependent:
    </p>   
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-xs">
      <div class="p-4 rounded-lg bg-slate-900/60 border border-white/5 space-y-2">
        <span class="font-bold text-cyan-400 block"><i class="fa-solid fa-gavel"></i> Receipt & Validation</span>
        <p class="text-slate-300 text-justify"><strong>Case A (Legitimate):</strong> Initiation of the return procedure. The customer is notified and has a 30-day window to return the product.</p>
        <p class="text-slate-300 text-justify"><strong>Case B (Abusive/Slanderous):</strong> Immediate termination of the return flow and escalation to legal counsel for defamation proceedings.</p>
      </div>
      <div class="p-4 rounded-lg bg-slate-900/60 border border-white/5 space-y-2">
        <span class="font-bold text-emerald-400 block"><i class="fa-solid fa-calculator"></i> Business Rules for Refunds</span>
        <ul class="space-y-1 text-slate-300">
          <li>• <strong class="text-white">100% Refund:</strong> If the issue is a production defect OR if it's a customer defect AND the product is in good condition.</li>
          <li>• <strong class="text-white">85% Refund:</strong> If the issue is customer-related BUT the product is damaged.</li>
          <li>• <strong class="text-white">70% Refund:</strong> If the issue is customer-related AND the product is very damaged.</li>
        </ul>
      </div>
    </div>
    <p class="text-slate-400 text-xs italic"><i class="fa-solid fa-circle-exclamation"></i> Return Period Management: If the product is not received within the 30-day deadline, the procedure is permanently aborted.</p>
  </section>

  <section class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-up">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-triangle-exclamation text-yellow-500"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-yellow-400 to-orange-500">Problem Statement</span>
    </h2>
    <p class="text-slate-300 text-sm leading-relaxed text-justify">
      An audit of the current Excel-based system reveals several critical flaws regarding task synchronization and data integrity:
    </p>
    <div class="space-y-3 text-xs md:text-sm">
      <div class="p-3 rounded-lg bg-red-500/5 border border-red-500/10 text-justify">
        <strong class="text-red-400"><i class="fa-solid fa-ban"></i> Lack of Parallelism:</strong> Currently, the process relies on a linear ‘handover’—technicians fill out their reports, and accounting must then manually consult the file to perform calculations. This sequential workflow causes data reading errors and significant payment delays.
      </div>
      <div class="p-3 rounded-lg bg-red-500/5 border border-red-500/10 text-justify">
        <strong class="text-red-400"><i class="fa-solid fa-gears"></i> Business Rule Complexity:</strong> The multi-tiered refund structure (100%, 85%, 70%) based on the intersection of two variables (Issue Source vs. Product Condition) makes manual data entry in Excel extremely high-risk for financial inaccuracies.
      </div>
      <div class="p-3 rounded-lg bg-red-500/5 border border-red-500/10 text-justify">
        <strong class="text-red-400"><i class="fa-solid fa-eye-slash"></i> Invisibility of Legal Exceptions:</strong> Claims escalated to the Legal Department (e.g., defamation cases) often fall off the standard tracking radar, creating a disconnect between Customer Service and the Legal team.
      </div>
      <div class="p-3 rounded-lg bg-red-500/5 border border-red-500/10 text-justify">
        <strong class="text-red-400"><i class="fa-solid fa-clock"></i> Inefficient Deadline Management (Time-Outs):</strong> No automated alerts are generated at the 30-day mark (J+30). This forces a manual, line-by-line review to identify expired claims that should be aborted, leading to wasted operational hours.
      </div>
    </div>
  </section>

<div class="p-4 glass-card rounded-xl border border-white/10" data-aos="zoom-in">
  <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest"><span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">Process Flowchart (BPMN 2.0)</span></h3>
  <img src="./images/bpmn-claims.png" alt="BPMN Diagram" class="w-full rounded-lg border border-white/5 shadow-2xl">
  <p class="text-[10px] text-slate-400 mt-2 italic text-center">Visual representation of the initial decision-making flow.</p>
</div>

  <section class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-up" data-aos-delay="100">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-square-poll-horizontal text-emerald-400"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">The Optimized Process</span>
    </h2>
    <p class="text-slate-300 text-sm leading-relaxed text-justify">
      In this phase, I optimized the manual claim process by implementing a structured data model and automated calculation rules.
    </p>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 pt-2">
      <div class="space-y-3">
        <h3 class="text-sm font-bold text-white uppercase tracking-wider"><span class="text-emerald-400 font-bold">Key Improvements</span></h3>
        <ul class="space-y-2 text-xs text-slate-300 text-justify">
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-bolt text-emerald-400 mt-0.5"></i>
            <span><strong>Logic Automation:</strong> Replaced manual refund estimations with precise SQL-based logic (<span class="text-emerald-400 font-bold">CASE WHEN</span>) and Excel formulas.</span>
          </li>
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-shield-halved text-emerald-400 mt-0.5"></i>
            <span><strong>Financial Accuracy:</strong> Developed a calculation engine that automatically applies 70%, 85%, or 100% refund rates based on product condition and issue source.</span>
          </li>
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-hourglass-end text-emerald-400 mt-0.5"></i>
            <span><strong>Time-Fencing:</strong> Integrated a “30-day rule” to automatically flag or abort expired claims, protecting company cash flow.</span>
          </li>
        </ul>
      </div>
      <div class="space-y-3">
        <h3 class="text-sm font-bold text-white uppercase tracking-wider"><span class="text-emerald-400 font-bold">Tools & Implementation</span></h3>
        <ul class="space-y-2 text-xs text-slate-300 text-justify">
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-code text-cyan-400 mt-0.5"></i>
            <span><strong>SQL Implementation:</strong> Enforced strict business constraints using <span class="text-emerald-400 font-bold">ENUM</span> types and automated updates.</span>
          </li>
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-table text-cyan-400 mt-0.5"></i>
            <span><strong>Excel:</strong> Consolidated multiple fragmented data sources to create a unified reporting view.</span>
          </li>
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-calculator text-cyan-400 mt-0.5"></i>
            <span><strong>Formulas:</strong> Used nested <span class="text-emerald-400 font-bold">IF</span> and <span class="text-emerald-400 font-bold">AND</span> (<span class="text-emerald-400 font-bold">WENN/UND</span>) logic to ensure zero errors on edge cases (e.g., “Unknown” sources).</span>
          </li>
        </ul>
      </div>
    </div>
    <div class="mt-4 p-4 rounded-lg bg-emerald-500/10 border border-emerald-500/20 text-center flex items-center justify-center gap-3">
      <i class="fa-solid fa-circle-check text-2xl text-emerald-400"></i>
      <span class="text-sm font-semibold text-white">
        Result: Reduced manual processing time and human calculation errors.
      </span>
    </div>
  </section>
  
<div class="p-4 glass-card rounded-xl border border-white/10" data-aos="zoom-in">
  <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest"><span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">Process Flowchart (BPMN 2.0)</span></h3>
  <img src="./images/bpmn-claims-optimized.png" alt="BPMN Diagram" class="w-full rounded-lg border border-white/5 shadow-2xl">
  <p class="text-[10px] text-slate-400 mt-2 italic text-center">Visual representation of the optimized decision-making flow.</p>
</div>

  <section class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-up">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-database text-cyan-400"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">SQL Database Architecture</span>
    </h2>
    <p class="text-slate-300 text-sm leading-relaxed text-justify">
      Below is the comprehensive relational schema script, business validation logic constraints, and data reporting generation pipeline implemented to resolve the operational gaps:
    </p>
    <div class="p-5 bg-slate-950 rounded-xl border border-white/10 text-xs font-mono overflow-x-auto shadow-2xl space-y-1">
      <p class="text-emerald-500 font-semibold mb-2">-- 1. Table Creation with Strict Business Constraints</p>
      <p><span class="text-pink-400">CREATE TABLE</span> Claim_Management (</p>
      <p class="pl-4">claim_id <span class="text-cyan-400">INT PRIMARY KEY AUTO_INCREMENT</span>,</p>
      <p class="pl-4">customer_name <span class="text-cyan-400">VARCHAR(100) NOT NULL</span>,</p>
      <p class="pl-4">product_name <span class="text-cyan-400">VARCHAR(100) NOT NULL</span>,</p>
      <p class="pl-4">product_price <span class="text-cyan-400">DECIMAL(10,2) NOT NULL</span>,</p>
      <p class="pl-4">claim_date <span class="text-cyan-400">DATE NOT NULL</span>,</p>
      <p class="pl-4">process_status <span class="text-purple-400">ENUM</span>(<span class="text-orange-300">'Pending_Return'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Aborted'</span>, <span class="text-orange-300">'Legal_Dispute'</span>) <span class="text-cyan-400">DEFAULT</span> <span class="text-orange-300">'Pending_Return'</span>,</p>
      <p class="pl-4">product_condition <span class="text-purple-400">ENUM</span>(<span class="text-orange-300">'Good'</span>, <span class="text-orange-300">'Damaged'</span>, <span class="text-orange-300">'Very_Damaged'</span>, <span class="text-orange-300">'Not_Received'</span>) <span class="text-cyan-400">DEFAULT</span> <span class="text-orange-300">'Not_Received'</span>,</p>
      <p class="pl-4">issue_source <span class="text-purple-400">ENUM</span>(<span class="text-orange-300">'Production'</span>, <span class="text-orange-300">'Customer'</span>, <span class="text-orange-300">'Unknown'</span>) <span class="text-cyan-400">DEFAULT</span> <span class="text-orange-300">'Unknown'</span>,</p>
      <p class="pl-4">refund_percentage <span class="text-cyan-400">INT DEFAULT 0</span>,</p>
      <p class="pl-4">refund_amount <span class="text-cyan-400">DECIMAL(10,2) DEFAULT 0.00</span></p>
      <p class="mb-4">);</p>
      <p class="text-emerald-500 font-semibold mb-2">-- 2. Mock Data Insertion (2026 Audit Dataset)</p>
      <p><span class="text-pink-400">INSERT INTO</span> Claim_Management (customer_name, product_name, product_price, claim_date, process_status, product_condition, issue_source)</p>
      <p><span class="text-pink-400">VALUES</span></p>
      <p class="pl-4">(<span class="text-orange-300">'Alice Johnson'</span>, <span class="text-orange-300">'HP PC AMD RYZEN 2025'</span>, 1200.00, <span class="text-orange-300">'2026-05-01'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Very_Damaged'</span>, <span class="text-orange-300">'Customer'</span>),</p>
      <p class="pl-4">(<span class="text-orange-300">'Bob Smith'</span>, <span class="text-orange-300">'Google 10 Pixel Phone'</span>, 800.00, <span class="text-orange-300">'2026-05-05'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Good'</span>, <span class="text-orange-300">'Customer'</span>),</p>
      <p class="pl-4">(<span class="text-orange-300">'Charlie Davis'</span>, <span class="text-orange-300">'Lenovo Tab M12'</span>, 500.00, <span class="text-orange-300">'2026-05-08'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Damaged'</span>, <span class="text-orange-300">'Customer'</span>),</p>
      <p class="pl-4">(<span class="text-orange-300">'Hans Mustermann'</span>, <span class="text-orange-300">'Iphone 13'</span>, 1200.00, <span class="text-orange-300">'2026-05-04'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Damaged'</span>, <span class="text-orange-300">'Production'</span>),</p>
      <p class="pl-4">(<span class="text-orange-300">'David Wilson'</span>, <span class="text-orange-300">'Google Pixel 8 Phone'</span>, 300.00, <span class="text-orange-300">'2026-04-01'</span>, <span class="text-orange-300">'Pending_Return'</span>, <span class="text-orange-300">'Not_Received'</span>, <span class="text-orange-300">'Unknown'</span>);</p>
      <p class="text-emerald-500 font-semibold mt-4 mb-2">-- 3. Corrected Multi-Tiered Matrix Logic Execution</p>
      <p><span class="text-pink-400">UPDATE</span> Claim_Management</p>
      <p><span class="text-pink-400">SET</span> refund_percentage = <span class="text-purple-400">CASE</span></p>
      <p class="pl-8"><span class="text-cyan-400">WHEN</span> issue_source = <span class="text-orange-300">'Customer'</span> <span class="text-cyan-400">AND</span> product_condition = <span class="text-orange-300">'Good'</span> <span class="text-cyan-400">THEN</span> 100</p>
      <p class="pl-8"><span class="text-cyan-400">WHEN</span> issue_source = <span class="text-orange-300">'Production'</span> <span class="text-cyan-400">AND</span> product_condition = <span class="text-orange-300">'Damaged'</span> <span class="text-cyan-400">THEN</span> 100</p>
      <p class="pl-8"><span class="text-cyan-400">WHEN</span> issue_source = <span class="text-orange-300">'Customer'</span> <span class="text-cyan-400">AND</span> product_condition = <span class="text-orange-300">'Damaged'</span> <span class="text-cyan-400">THEN</span> 85</p>
      <p class="pl-8"><span class="text-cyan-400">WHEN</span> issue_source = <span class="text-orange-300">'Customer'</span> <span class="text-cyan-400">AND</span> product_condition = <span class="text-orange-300">'Very_Damaged'</span> <span class="text-cyan-400">THEN</span> 70</p>
      <p class="pl-8"><span class="text-cyan-400">ELSE</span> 0</p>
      <p class="pl-4"><span class="text-purple-400">END</span></p>
      <p><span class="text-pink-400">WHERE</span> process_status = <span class="text-orange-300">'Received'</span>;</p>
      <p class="text-emerald-500 font-semibold mt-4 mb-2">-- 4. Financial Calculations Layer</p>
      <p><span class="text-pink-400">UPDATE</span> Claim_Management</p>
      <p><span class="text-pink-400">SET</span> refund_amount = (product_price * refund_percentage / 100)</p>
      <p><span class="text-pink-400">WHERE</span> process_status = <span class="text-orange-300">'Received'</span>;</p>
      <p class="text-emerald-500 font-semibold mt-4 mb-2">-- 5. Final Granular Audit View Output</p>
      <p><span class="text-pink-400">SELECT</span> claim_id, customer_name, product_name,</p>
      <p class="pl-4"><span class="text-purple-400">CONCAT</span>(product_price, <span class="text-orange-300">' €'</span>) <span class="text-pink-400">AS</span> unit_price, issue_source, product_condition,</p>
      <p class="pl-4"><span class="text-purple-400">CONCAT</span>(refund_percentage, <span class="text-orange-300">'%'</span>) <span class="text-pink-400">AS</span> rate,</p>
      <p class="pl-4"><span class="text-purple-400">CONCAT</span>(refund_amount, <span class="text-orange-300">' €'</span>) <span class="text-pink-400">AS</span> total_refunded, process_status</p>
      <p><span class="text-pink-400">FROM</span> Claim_Management;</p>
    </div>
    
  <div class="p-4 glass-card rounded-xl border border-white/10 mt-4" data-aos="zoom-in">
      <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest"><span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">Table with the previous mySQL code</span></h3>
      <img src="./images/sql-table-result.png" alt="Datas Table" class="w-full rounded-lg border border-white/5 shadow-2xl">
      <p class="text-[10px] text-slate-400 mt-2 italic text-center">Visual Table of the data compiled from the database terminal.</p>
  </div>
    <div class="mt-4 p-4 rounded-lg bg-emerald-500/10 border border-emerald-500/20 text-center flex items-center justify-center gap-3">
      <i class="fa-solid fa-circle-check text-2xl text-emerald-400"></i>
      <span class="text-sm font-semibold text-white">
        Result: Visualisation of the <span class="text-emerald-400 font-bold">optimized</span> Datas and significant reduction of humans' errors.
      </span>
    </div>
  </section>

<div class="p-4 glass-card rounded-xl border border-white/10" data-aos="zoom-in">
    <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest"><span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">Representation in Excel</span></h3>
    <img src="./images/excel-powerquery-dash.png" alt="Excel View" class="w-full rounded-lg border border-white/5 shadow-2xl">
    <p class="text-[10px] text-slate-400 mt-2 italic text-center">Case Studies in Excel consolidated with Power Query.</p>
  </div>
  
<section id="deliverables" class="mt-12 grid grid-cols-1 md:grid-cols-2 gap-6" data-aos="fade-up">  
    <div class="p-6 glass-card rounded-xl border border-white/10 flex flex-col justify-between">
        <div>
            <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest flex items-center gap-2">
                <i class="fas fa-history text-amber-500"></i> Initial Case Documents
            </h3>
            <p class="text-slate-300 text-sm mb-6">
                Download the original files and the legacy workflow mapping before the automation process.
            </p>
        </div>        
        <div class="space-y-3">
            <a href="./documents/process-overview.pdf" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-file-pdf text-rose-500 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">Process Overview (PDF)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
            <a href="./documents/process-initial.drawio" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-project-diagram text-orange-400 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">Initial BPMN Process (DRAW.IO)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
        </div>
    </div>
    <div class="p-6 glass-card rounded-xl border border-white/10 flex flex-col justify-between">
        <div>
            <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest flex items-center gap-2">
                <i class="fas fa-magic text-emerald-400"></i> Optimized Solutions
            </h3>
            <p class="text-slate-300 text-sm mb-6">
                Access the automated architecture, engineered scripts, and dynamic data visualizations.
            </p>
        </div>        
        <div class="space-y-3">
            <a href="./documents/bpmn-claims-optimized.drawio" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-project-diagram text-emerald-400 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">Optimized BPMN Process (DRAW.IO)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
            <a href="./database/script.sql" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-code text-blue-400 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">MySQL Database Script (Open with VS Code)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
            <a href="./documents/excel-visualisation.xlsx" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-file-excel text-green-500 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">Excel Visualisation Dashboard (XLSX)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
        </div>
    </div>
    <div class="col-span-full p-6 glass-card rounded-xl border border-white/10 flex flex-col sm:flex-row items-center justify-between gap-6 text-center sm:text-left">
        <div>
            <h3 class="text-xs font-bold text-cyan-400 mb-1 uppercase tracking-widest flex items-center justify-center sm:justify-start gap-2">
                <i class="fas fa-share-alt text-purple-400"></i> Connect with me
            </h3>
            <p class="text-slate-400 text-xs">
                Interested in process optimization and data engineering? Let's discuss this project on my networks.
            </p>
        </div>
        <div class="flex items-center gap-4">
            <a href="https://www.linkedin.com/in/winston-engamba-7b3489325/" target="_blank" rel="noopener noreferrer" 
               class="w-10 h-10 flex items-center justify-center rounded-lg bg-white/5 hover:bg-[#0077b5]/20 border border-white/5 hover:border-[#0077b5]/50 text-slate-300 hover:text-[#0077b5] transition-all duration-300 text-sm group" title="LinkedIn">
                <i class="fab fa-linkedin-in group-hover:scale-110 transition-transform"></i>
            </a>
            <a href="https://github.com/wero-git/" target="_blank" rel="noopener noreferrer" 
               class="w-10 h-10 flex items-center justify-center rounded-lg bg-white/5 hover:bg-white/20 border border-white/5 hover:border-white/50 text-slate-300 hover:text-white transition-all duration-300 text-sm group" title="GitHub">
                <i class="fab fa-github group-hover:scale-110 transition-transform"></i>
            </a>
            <a href="mailto:rodokomon24@gmail.com" 
               class="w-10 h-10 flex items-center justify-center rounded-lg bg-white/5 hover:bg-emerald-500/20 border border-white/5 hover:border-emerald-500/50 text-slate-300 hover:text-emerald-400 transition-all duration-300 text-sm group" title="Email">
                <i class="fas fa-envelope group-hover:scale-110 transition-transform"></i>
            </a>
        </div>
    </div>
</section>

<div class="mt-16 pt-6 border-t border-white/5 flex flex-col sm:flex-row items-center justify-between gap-4 text-xs text-slate-500">
    <div>
        © 2026 - End-to-End Claims Optimization Project. All rights reserved.
    </div>
        <a href="#home" class="flex items-center gap-2 text-slate-400 hover:text-cyan-400 transition-all duration-300 group font-medium uppercase tracking-wider">
        Back to top 
        <i class="fas fa-arrow-up group-hover:-translate-y-1 transition-transform text-emerald-400"></i>
    </a>
</div>

  <div class="pt-6 text-center" data-aos="fade-up">
    <a href="./index.html" class="inline-flex items-center gap-2 text-sm font-semibold text-cyan-400 hover:underline transition">
      <i class="fa-solid fa-house"></i> Back Home
    </a>
  </div>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>AOS.init({ duration: 800, once: true });</script>
