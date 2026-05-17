<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Winston's Portfolio | Business Analyst & Automation Expert</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 50%, #1e293b 100%);
            color: #f8fafc;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }
    </style>
</head>
<body class="antialiased">
    <nav class="fixed top-0 w-full z-50 glass-card px-8 py-4 flex justify-between items-center">
        <div class="text-xl font-bold bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">
            Analyst.Portfolio
        </div>
        <ul class="flex space-x-6 text-sm font-medium">
            <li><a href="#home" class="hover:text-cyan-400 transition">Home</a></li>
            <li><a href="#project-overview" class="hover:text-cyan-400 transition">Overview</a></li>
            <li><a href="#audit" class="hover:text-cyan-400 transition">Audit</a></li>
            <li><a href="#optimization" class="hover:text-cyan-400 transition">Optimization</a></li>
            <li><a href="#contact" class="hover:text-cyan-400 transition">Contact</a></li>
        </ul>
    </nav>
    <header id="home" class="pt-32 pb-20 px-8 max-w-7xl mx-auto min-h-screen flex flex-col md:flex-row items-center justify-between gap-12">
        <div class="flex-1 space-y-6" data-aos="fade-right">
            <div class="inline-block px-4 py-1.5 rounded-full text-xs font-semibold uppercase bg-cyan-500/10 text-cyan-400 border border-cyan-500/20">
                🚀 Open to Opportunities
            </div>
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight">
                Hi, I'm <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 via-teal-400 to-blue-500">Winston</span> <br>
                Welcome to my Portfolio 🤗
            </h1>
            <p class="text-gray-400 text-lg max-w-xl mb-4">
                I bridge the gap between complex business workflows and data architecture. Specialized in Process Optimization, SQL Logic, and Automated Financial Reporting.
            </p>
            <p class="text-sm text-cyan-400 italic font-mono">
                "Throughout what follows, a fragmented customer return process will be identified, modeled, and resolved."
            </p>
            <div class="flex space-x-4 pt-4">
                <a href="#project-overview" class="px-6 py-3 rounded-lg bg-gradient-to-r from-cyan-500 to-blue-600 font-medium hover:opacity-90 transition desktop-btn">Explore Case Study</a>
                <a href="#contact" class="px-6 py-3 rounded-lg border border-gray-600 hover:bg-white/5 font-medium transition">Get in Touch</a>
            </div>
        </div>
        <div class="flex-1 relative flex justify-center" data-aos="fade-left">
            <div class="absolute w-72 h-72 bg-blue-500/20 rounded-full blur-3xl -z-10"></div>
            <img src="./images/tech_dna_process_fusion.png" alt="Data & Process Integration DNA" class="w-full max-w-md object-contain rounded-2xl drop-shadow-[0_0_35px_rgba(6,182,212,0.3)]">
        </div>
    </header>
    <main class="py-10 px-4 max-w-5xl mx-auto space-y-16">
        <section id="project-overview" class="glass-card p-8 rounded-2xl space-y-6" data-aos="fade-up">
            <div class="border-b border-white/10 pb-4">
                <h2 class="text-3xl font-bold bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">
                    End-to-End Claim Management Optimization
                </h2>
                <p class="text-gray-400 text-sm mt-1">Process Description & Situation Interpretation</p>
            </div>
            <div class="space-y-4 text-gray-300 leading-relaxed text-sm md:text-base">
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
            <div class="grid md:grid-cols-2 gap-6 pt-4 text-sm">
                <div class="bg-slate-900/50 p-4 rounded-xl border border-white/5">
                    <h4 class="font-semibold text-cyan-400 mb-2"><i class="fa-solid fa-clipboard-check mr-2"></i>Receipt & Validation</h4>
                    <ul class="list-disc list-inside space-y-1 text-gray-400">
                        <li><strong class="text-gray-300">Case A (Legitimate):</strong> Return initiated. 30-day window enforced.</li>
                        <li><strong class="text-gray-300">Case B (Abusive):</strong> Immediate flow termination; escalated to legal counsel for defamation.</li>
                    </ul>
                </div>
                <div class="bg-slate-900/50 p-4 rounded-xl border border-white/5">
                    <h4 class="font-semibold text-teal-400 mb-2"><i class="fa-solid fa-calculator mr-2"></i>Refund Matrix Engine</h4>
                    <ul class="list-disc list-inside space-y-1 text-gray-400">
                        <li><strong class="text-gray-300">100% Refund:</strong> Production defect AND product is in Good Condition.</li>
                        <li><strong class="text-gray-300">85% Refund:</strong> Customer-related issue BUT product is Damaged.</li>
                        <li><strong class="text-gray-300">70% Refund:</strong> Customer-related issue AND product is Very Damaged.</li>
                    </ul>
                </div>
            </div>
        </section>
        <section id="audit" class="glass-card p-8 rounded-2xl space-y-6" data-aos="fade-up">
            <div class="border-b border-white/10 pb-4">
                <h2 class="text-2xl font-bold text-red-400">
                    <i class="fa-solid fa-triangle-exclamation mr-2"></i>System Audit & Critical Flaws
                </h2>
                <p class="text-gray-400 text-sm mt-1">Why the legacy Excel workflow was highly vulnerable</p>
            </div>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="space-y-2">
                    <h3 class="text-base font-semibold text-gray-200">❌ Lack of Parallelism</h3>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        The process relied on a linear "handover"—technicians filled out reports, and accounting had to manually check files later. This sequential workflow caused reading errors and severe payment delays.
                    </p>
                </div>
                <div class="space-y-2">
                    <h3 class="text-base font-semibold text-gray-200">❌ Business Rule Complexity</h3>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        The multi-tiered refund structure (100%, 85%, 70%) crossing multiple variables made manual input a high-risk factor for financial inaccuracies.
                    </p>
                </div>
                <div class="space-y-2">
                    <h3 class="text-base font-semibold text-gray-200">❌ Invisibility of Legal Exceptions</h3>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        Claims escalated to the Legal Department completely left the standard tracking radar, causing an operational disconnect between teams.
                    </p>
                </div>
                <div class="space-y-2">
                    <h3 class="text-base font-semibold text-gray-200">❌ Inefficient Deadline Management</h3>
                    <p class="text-sm text-gray-400 leading-relaxed">
                        No automation at the 30-day mark forced a line-by-line manual review to abort expired claims, wasting valuable operational hours.
                    </p>
                </div>
            </div>
        </section>
        <section id="optimization" class="glass-card p-8 rounded-2xl space-y-6" data-aos="fade-up">
            <div class="border-b border-white/10 pb-4">
                <h2 class="text-2xl font-bold text-emerald-400">
                    <i class="fa-solid fa-square-poll-horizontal mr-2"></i>The Optimized Architecture
                </h2>
                <p class="text-gray-400 text-sm mt-1">Driving efficiency through structured data models and formulas</p>
            </div>
            <div class="space-y-4">
                <p class="text-gray-300 text-sm md:text-base">
                    I optimized the manual claim process by implementing a structured database model and automated calculation rules, <strong class="text-emerald-400">reducing manual processing time by an estimated 60%</strong> and eliminating calculation errors.
                </p>           
                <h3 class="text-lg font-medium text-gray-200 pt-2">Key Operational Pillars:</h3>
                <div class="grid md:grid-cols-3 gap-4 text-xs md:text-sm">
                    <div class="p-4 rounded-xl bg-slate-900/60 border border-emerald-500/10">
                        <span class="text-xl">🤖</span>
                        <h4 class="font-semibold text-gray-200 mt-1 mb-1">Logic Automation</h4>
                        <p class="text-gray-400 text-xs">Replaced estimations with strict SQL <code class="text-cyan-400">CASE WHEN</code> structures and clean nested formulas.</p>
                    </div>
                    <div class="p-4 rounded-xl bg-slate-900/60 border border-emerald-500/10">
                        <span class="text-xl">🎯</span>
                        <h4 class="font-semibold text-gray-200 mt-1 mb-1">Financial Accuracy</h4>
                        <p class="text-gray-400 text-xs">An automatic matrix engine applying 70%, 85%, or 100% rates based on inputs.</p>
                    </div>
                    <div class="p-4 rounded-xl bg-slate-900/60 border border-emerald-500/10">
                        <span class="text-xl">🛡️</span>
                        <h4 class="font-semibold text-gray-200 mt-1 mb-1">Time-Fencing</h4>
                        <p class="text-gray-400 text-xs">Enforced the "30-day rule" natively to automatically flag or abort expired claims, protecting cash flow.</p>
                    </div>
                </div>
                <div class="pt-4 space-y-3">
                    <h4 class="text-sm font-semibold text-gray-300">Implementation Stack & Tools:</h4>
                    <div class="flex flex-wrap gap-3 text-xs font-mono">
                        <span class="px-3 py-1.5 rounded-lg bg-slate-800 border border-white/10 text-cyan-400">
                            <strong>SQL:</strong> Enforced Constraints (ENUM) & Automated Updates
                        </span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-800 border border-white/10 text-teal-400">
                            <strong>Excel Power Query:</strong> Unified reporting pipelines
                        </span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-800 border border-white/10 text-yellow-400">
                            <strong>Formulas:</strong> Nested WENN/UND (IF/AND) for edge cases
                        </span>
                    </div>
                </div>
            </div>
        </section>
    </main>
    <footer id="contact" class="py-20 px-8 max-w-4xl mx-auto space-y-12 border-t border-white/10">
        <div class="text-center space-y-4" data-aos="zoom-in">
            <h2 class="text-3xl font-bold">Get In Touch</h2>
            <p class="text-gray-400 text-sm">Have an opportunity or want to discuss process automation? Let's connect!</p>
        </div>
        <div class="grid md:grid-cols-2 gap-8">
            <div class="glass-card p-6 rounded-xl flex flex-col justify-between space-y-6" data-aos="fade-right">
                <div>
                    <h3 class="text-lg font-semibold mb-2">Connect with me</h3>
                    <p class="text-sm text-gray-400">Access my live technical repositories and professional profiles.</p>
                </div>
                <div class="flex space-x-6 text-3xl text-gray-300">
                    <a href="YOUR_GITHUB_LINK" class="hover:text-cyan-400 transition"><i class="fab fa-github"></i></a>
                    <a href="YOUR_LINKEDIN_LINK" class="hover:text-blue-500 transition"><i class="fab fa-linkedin"></i></a>
                    <a href="mailto:your.email@example.com" class="hover:text-teal-400 transition"><i class="fas fa-envelope"></i></a>
                </div>
                <p class="text-xs text-gray-500 font-mono">Designed by Winston © 2026</p>
            </div>
            <form class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-left">
                <div>
                    <label class="block text-xs uppercase text-gray-400 mb-1">Your Name</label>
                    <input type="text" class="w-full bg-slate-900 border border-white/10 rounded p-2 text-sm focus:border-cyan-500 outline-none text-white">
                </div>
                <div>
                    <label class="block text-xs uppercase text-gray-400 mb-1">Your Email</label>
                    <input type="email" class="w-full bg-slate-900 border border-white/10 rounded p-2 text-sm focus:border-cyan-500 outline-none text-white">
                </div>
                <div>
                    <label class="block text-xs uppercase text-gray-400 mb-1">Message</label>
                    <textarea rows="3" class="w-full bg-slate-900 border border-white/10 rounded p-2 text-sm focus:border-cyan-500 outline-none text-white"></textarea>
                </div>
                <button type="submit" class="w-full py-2 rounded bg-cyan-500 hover:bg-cyan-600 font-medium text-sm transition text-white">Send Message</button>
            </form>
        </div>
    </footer>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 1000,
            once: true,
        });
    </script>
</body>
</html>
