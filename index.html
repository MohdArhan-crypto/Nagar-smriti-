<!DOCTYPE html>
<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nagar Smriti - City's Memory | AI Municipal Reconciliation</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        amber: {
                            500: '#f59e0b',
                            600: '#d97706',
                            700: '#b45309',
                            900: '#451a03',
                        },
                        archival: {
                            bg: '#0a0f1d',
                            card: '#131c31',
                            cardBorder: '#23304d',
                            paper: '#192238',
                            accent: '#fbbf24',
                        }
                    },
                    fontFamily: {
                        mono: ['Courier New', 'Courier', 'monospace'],
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Marked.js for markdown rendering -->
    <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
    <!-- FontAwesome icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        body {
            background-color: #080c16;
            color: #e2e8f0;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
        }

        .archive-font {
            font-family: 'Courier New', Courier, monospace;
        }

        .citation-badge {
            display: inline-flex;
            align-items: center;
            padding: 0.125rem 0.375rem;
            border-radius: 0.25rem;
            font-size: 0.75rem;
            font-weight: 700;
            letter-spacing: 0.025em;
            text-transform: uppercase;
            margin: 0 0.125rem;
        }

        .citation-bwssb {
            background-color: rgba(14, 165, 233, 0.2);
            color: #38bdf8;
            border: 1px solid rgba(56, 189, 248, 0.4);
        }

        .citation-bescom {
            background-color: rgba(234, 179, 8, 0.2);
            color: #fde047;
            border: 1px solid rgba(250, 204, 21, 0.4);
        }

        .citation-roads {
            background-color: rgba(239, 68, 68, 0.2);
            color: #fca5a5;
            border: 1px solid rgba(248, 113, 113, 0.4);
        }

        .stamped-paper {
            background: radial-gradient(circle at top right, rgba(245, 158, 11, 0.05), transparent 70%), #131c31;
            box-shadow: inset 0 0 15px rgba(0,0,0,0.5);
            border: 1px solid #23304d;
            position: relative;
        }

        .stamped-paper::before {
            content: "ARCHIVAL RECORD";
            position: absolute;
            top: 15px;
            right: 15px;
            font-family: 'Courier New', monospace;
            font-size: 0.65rem;
            color: rgba(245, 158, 11, 0.3);
            border: 1px dashed rgba(245, 158, 11, 0.3);
            padding: 2px 6px;
            transform: rotate(-3deg);
            pointer-events: none;
        }

        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #0f172a;
        }
        ::-webkit-scrollbar-thumb {
            background: #334155;
            border-radius: 3px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #f59e0b;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col">

    <!-- Top Header & API Key Bar -->
    <header class="bg-slate-900 border-b border-slate-800 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 py-3 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-3">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-lg bg-amber-500/10 border border-amber-500/40 flex items-center justify-center text-amber-500 font-bold text-xl">
                    <i class="fa-solid me-0.5 fa-landmark"></i>
                </div>
                <div>
                    <div class="flex items-center space-x-2">
                        <h1 class="text-xl font-bold tracking-tight text-white">Nagar Smriti <span class="text-xs px-2 py-0.5 rounded bg-amber-500/20 text-amber-400 border border-amber-500/30">नगर स्मृति</span></h1>
                    </div>
                    <p class="text-xs text-slate-400">City's Institutional Memory & Underground Infrastructure Reconciler</p>
                </div>
            </div>

            <!-- API Key Input -->
            <div class="w-full sm:w-auto flex items-center space-x-2 bg-slate-950 px-3 py-1.5 rounded-lg border border-slate-800">
                <i class="fa-solid fa-key text-amber-500 text-xs"></i>
                <input type="password" id="apiKeyInput" placeholder="Enter Gemini API Key..." 
                       class="bg-transparent text-xs text-slate-200 placeholder-slate-500 focus:outline-none w-48 sm:w-60" />
                <button id="saveKeyBtn" onclick="saveApiKey()" class="text-xs bg-amber-600 hover:bg-amber-500 text-slate-950 font-semibold px-2.5 py-1 rounded transition">
                    Save
                </button>
                <a href="https://aistudio.google.com" target="_blank" rel="noopener noreferrer" 
                   class="text-xs text-amber-400/80 hover:text-amber-300 underline flex items-center gap-1 pl-1">
                   <span>Get Key</span>
                   <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                </a>
            </div>
        </div>

        <!-- Navigation Tabs -->
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex space-x-1 border-t border-slate-800/60 mt-1">
            <button onclick="switchTab('records')" id="tab-records" 
                    class="tab-btn px-4 py-2.5 text-sm font-medium border-b-2 border-amber-500 text-amber-400 flex items-center gap-2 transition">
                <i class="fa-solid fa-folder-open text-xs"></i>
                <span>Agency Records</span>
                <span class="text-[10px] bg-slate-800 text-slate-400 px-1.5 py-0.5 rounded-full">3 Raw Sources</span>
            </button>

            <button onclick="switchTab('query')" id="tab-query" 
                    class="tab-btn px-4 py-2.5 text-sm font-medium border-b-2 border-transparent text-slate-400 hover:text-slate-200 flex items-center gap-2 transition">
                <i class="fa-solid fa-brain text-xs"></i>
                <span>Ask Nagar Smriti</span>
                <span class="text-[10px] bg-amber-500/20 text-amber-400 px-1.5 py-0.5 rounded-full">AI Reconciler</span>
            </button>

            <button onclick="switchTab('permit')" id="tab-permit" 
                    class="tab-btn px-4 py-2.5 text-sm font-medium border-b-2 border-transparent text-slate-400 hover:text-slate-200 flex items-center gap-2 transition">
                <i class="fa-solid fa-shield-cat text-xs"></i>
                <span>Permit Check</span>
                <span class="text-[10px] bg-emerald-500/20 text-emerald-400 px-1.5 py-0.5 rounded-full">Preventive Risk</span>
            </button>
        </div>
    </header>

    <!-- Main Container -->
    <main class="flex-1 max-w-7xl w-full mx-auto p-4 sm:p-6 lg:p-8">

        <!-- SCREEN 1: AGENCY RECORDS -->
        <section id="screen-records" class="space-y-6">
            <div class="bg-slate-900/80 border border-slate-800 rounded-xl p-4 sm:p-5 flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
                <div>
                    <h2 class="text-lg font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot text-amber-500"></i>
                        Target Corridor: MG Road (Junction A to Junction B)
                    </h2>
                    <p class="text-sm text-slate-400 mt-1">
                        Demonstrating 3 fragmented, un-reconciled municipal dataset records for the exact same 400m street segment in Bengaluru.
                    </p>
                </div>
                <div class="flex items-center gap-2 bg-amber-950/40 border border-amber-800/50 text-amber-300 px-3 py-2 rounded-lg text-xs">
                    <i class="fa-solid fa-triangle-exclamation text-amber-400 text-sm"></i>
                    <span><strong>Problem State:</strong> Zero cross-verification between agency databases.</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
                <!-- AGENCY 1: BWSSB -->
                <div class="stamped-paper rounded-xl p-5 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-700/60 pb-3 mb-4">
                            <div class="flex items-center gap-3">
                                <span class="text-3xl">💧</span>
                                <div>
                                    <h3 class="font-bold text-sky-400 text-base">BWSSB</h3>
                                    <p class="text-xs text-slate-400">Water Supply & Sewerage Board</p>
                                </div>
                            </div>
                            <span class="text-[10px] font-mono bg-sky-950 text-sky-300 border border-sky-800/60 px-2 py-0.5 rounded">
                                Digitized 2019
                            </span>
                        </div>

                        <div class="space-y-3 font-mono text-xs text-slate-300 leading-relaxed">
                            <div>
                                <span class="text-slate-500 block text-[10px]">RECORD TYPE</span>
                                <span class="text-slate-200">Underground pipeline map (digitized scan)</span>
                            </div>
                            <div>
                                <span class="text-slate-500 block text-[10px]">SOURCE MAP BASE YEAR</span>
                                <span class="text-amber-400 font-bold">2002 road survey</span>
                            </div>
                            <div>
                                <span class="text-slate-500 block text-[10px]">LAST FIELD VERIFICATION</span>
                                <span class="text-red-400 font-bold">Not recorded since 2002</span>
                            </div>
                            <div class="bg-slate-900/90 p-3 rounded border border-slate-800 space-y-1">
                                <span class="text-slate-400 font-sans font-semibold text-[11px] block text-sky-400">PIPELINE DETAILS:</span>
                                <p>• 450mm sewage trunk line (depth ~2.1m, laid 1998)</p>
                                <p>• 200mm water supply line (depth ~1.4m, laid 2002)</p>
                            </div>
                            <div class="bg-amber-950/30 p-2.5 rounded border border-amber-900/40 text-amber-200/90 italic">
                                <span class="font-sans font-bold text-[10px] text-amber-400 block non-italic">⚠️ HANDWRITTEN ANNOTATION:</span>
                                "Road widened after this map was made — pipeline position relative to current road edge not re-surveyed. Approximate only."
                            </div>
                        </div>
                    </div>
                    <div class="mt-4 pt-3 border-t border-slate-800/80 flex justify-between items-center text-[10px] text-slate-500">
                        <span>GIS attached: NONE</span>
                        <span>Ref: BWSSB-2002</span>
                    </div>
                </div>

                <!-- AGENCY 2: BESCOM -->
                <div class="stamped-paper rounded-xl p-5 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-700/60 pb-3 mb-4">
                            <div class="flex items-center gap-3">
                                <span class="text-3xl">⚡</span>
                                <div>
                                    <h3 class="font-bold text-amber-400 text-base">BESCOM</h3>
                                    <p class="text-xs text-slate-400">Electricity Supply Company</p>
                                </div>
                            </div>
                            <span class="text-[10px] font-mono bg-amber-950 text-amber-300 border border-amber-800/60 px-2 py-0.5 rounded">
                                Updated 2019-11-03
                            </span>
                        </div>

                        <div class="space-y-3 font-mono text-xs text-slate-300 leading-relaxed">
                            <div>
                                <span class="text-slate-500 block text-[10px]">RECORD TYPE</span>
                                <span class="text-slate-200">GIS export (partial network)</span>
                            </div>
                            <div>
                                <span class="text-slate-500 block text-[10px]">NETWORK MAPPING COMPLETENESS</span>
                                <span class="text-amber-400 font-bold">83% mapped in Ward 7</span>
                            </div>
                            <div class="bg-slate-900/90 p-3 rounded border border-slate-800 space-y-1">
                                <span class="text-slate-400 font-sans font-semibold text-[11px] block text-amber-400">CABLE DETAILS:</span>
                                <p>• 11kV underground feeder cable present in corridor</p>
                                <p class="text-red-400">• Chainage: Unmapped 17% zone</p>
                                <p class="text-red-400 font-bold">• Depth: NOT RECORDED (2D GIS system)</p>
                            </div>
                            <div class="bg-red-950/30 p-2.5 rounded border border-red-900/40 text-red-200/90">
                                <span class="font-sans font-bold text-[10px] text-red-400 block">⚠️ AUDIT WARNING:</span>
                                Cross-verification with BWSSB or road department records: NONE ON FILE.
                            </div>
                        </div>
                    </div>
                    <div class="mt-4 pt-3 border-t border-slate-800/80 flex justify-between items-center text-[10px] text-slate-500">
                        <span>Format: 2D Layer Only</span>
                        <span>Ref: BESCOM-2019</span>
                    </div>
                </div>

                <!-- AGENCY 3: ROADS & PERMITS -->
                <div class="stamped-paper rounded-xl p-5 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-700/60 pb-3 mb-4">
                            <div class="flex items-center gap-3">
                                <span class="text-3xl">🚧</span>
                                <div>
                                    <h3 class="font-bold text-rose-400 text-base">Roads & Permits</h3>
                                    <p class="text-xs text-slate-400">Excavation Permit History Log</p>
                                </div>
                            </div>
                            <span class="text-[10px] font-mono bg-rose-950 text-rose-300 border border-rose-800/60 px-2 py-0.5 rounded">
                                Log 2015-2023
                            </span>
                        </div>

                        <div class="space-y-3 font-mono text-xs text-slate-300 leading-relaxed">
                            <div>
                                <span class="text-slate-500 block text-[10px]">RECORD TYPE</span>
                                <span class="text-slate-200">Road-cutting permit history log</span>
                            </div>
                            <div class="bg-slate-900/90 p-3 rounded border border-slate-800 space-y-2 text-[11px]">
                                <div>
                                    <span class="text-slate-400 font-bold">2015 (#RC-2015-0447):</span>
                                    <p>Telecom fiber laying (~1m depth). No as-built drawing filed.</p>
                                </div>
                                <div class="pt-1 border-t border-slate-800">
                                    <span class="text-rose-400 font-bold">2020 (#RC-2020-1183):</span>
                                    <p>Emergency BWSSB repair. Struck unmarked electrical conduit at ~1.3m. Paused 2 days. No formal BESCOM report filed.</p>
                                </div>
                                <div class="pt-1 border-t border-slate-800">
                                    <span class="text-amber-400 font-bold">2023 (#CC-2023-8821):</span>
                                    <p>Citizen complaint: Road dug up twice in 8 months by different agencies.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="mt-4 pt-3 border-t border-slate-800/80 flex justify-between items-center text-[10px] text-slate-500">
                        <span>Unified Layer: None</span>
                        <span>Ref: ROADS-PERMITS</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- SCREEN 2: ASK NAGAR SMRITI -->
        <section id="screen-query" class="hidden space-y-6">
            <div class="bg-slate-900 border border-slate-800 rounded-xl p-5">
                <h2 class="text-lg font-bold text-white flex items-center gap-2 mb-2">
                    <i class="fa-solid fa-comments text-amber-500"></i>
                    Query Institutional Memory
                </h2>
                <p class="text-xs text-slate-400 mb-4">
                    Ask plain-language questions. Gemini will synthesize across agency records, cite specific departmental logs, and highlight contradictions.
                </p>

                <!-- Pre-populated Quick Prompt Buttons -->
                <div class="space-y-2 mb-4">
                    <p class="text-[11px] font-semibold text-slate-400 uppercase tracking-wider">Suggested Hackathon Queries:</p>
                    <div class="flex flex-wrap gap-2">
                        <button onclick="useQuickQuery('What utilities run under this stretch of road?')" 
                                class="text-xs bg-slate-800 hover:bg-slate-700 hover:text-amber-300 text-slate-300 px-3 py-2 rounded-lg border border-slate-700 transition flex items-center gap-1.5">
                            <i class="fa-solid fa-circle-question text-amber-500 text-[10px]"></i>
                            <span>"What utilities run under this stretch of road?"</span>
                        </button>

                        <button onclick="useQuickQuery('Has this road been dug up before, and why?')" 
                                class="text-xs bg-slate-800 hover:bg-slate-700 hover:text-amber-300 text-slate-300 px-3 py-2 rounded-lg border border-slate-700 transition flex items-center gap-1.5">
                            <i class="fa-solid fa-shovel text-amber-500 text-[10px]"></i>
                            <span>"Has this road been dug up before, and why?"</span>
                        </button>

                        <button onclick="useQuickQuery('Is it safe to excavate here without further checks?')" 
                                class="text-xs bg-slate-800 hover:bg-slate-700 hover:text-amber-300 text-slate-300 px-3 py-2 rounded-lg border border-slate-700 transition flex items-center gap-1.5">
                            <i class="fa-solid fa-triangle-exclamation text-amber-500 text-[10px]"></i>
                            <span>"Is it safe to excavate here without further checks?"</span>
                        </button>
                    </div>
                </div>

                <!-- Question Input Area -->
                <form id="queryForm" onsubmit="handleQuerySubmit(event)" class="flex flex-col sm:flex-row gap-3">
                    <div class="relative flex-1">
                        <input type="text" id="userQueryInput" 
                               placeholder="e.g. Are there electrical cables near 1.3 meters depth?" 
                               class="w-full bg-slate-950 border border-slate-700 text-slate-100 rounded-lg px-4 py-3 text-sm focus:outline-none focus:border-amber-500 transition pr-10" 
                               required />
                    </div>
                    <button type="submit" id="querySubmitBtn"
                            class="bg-amber-600 hover:bg-amber-500 text-slate-950 font-bold px-6 py-3 rounded-lg transition flex items-center justify-center gap-2 text-sm shadow-lg shadow-amber-600/20">
                        <i class="fa-solid fa-paper-plane"></i>
                        <span>Reconcile & Answer</span>
                    </button>
                </form>
            </div>

            <!-- AI Response Box -->
            <div id="queryResultContainer" class="hidden space-y-4">
                <!-- Conflict Callout Banner (Dynamically Shown) -->
                <div id="conflictAlertBox" class="bg-amber-950/50 border border-amber-600/50 rounded-xl p-4 hidden flex items-start gap-3">
                    <div class="p-2 bg-amber-500/20 text-amber-400 rounded-lg text-lg mt-0.5">
                        <i class="fa-solid fa-triangle-exclamation"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-amber-300 text-sm">Inter-Agency Conflicts & Gaps Detected</h4>
                        <p class="text-xs text-amber-200/80 mt-0.5">
                            Nagar Smriti found contradictory data points across BWSSB, BESCOM, and Permit records. Review cited discrepancies below.
                        </p>
                    </div>
                </div>

                <!-- Answer Card -->
                <div class="bg-slate-900 border border-slate-800 rounded-xl p-6 relative">
                    <div class="flex justify-between items-center border-b border-slate-800 pb-3 mb-4">
                        <div class="flex items-center gap-2">
                            <span class="w-2 h-2 rounded-full bg-amber-500 animate-pulse"></span>
                            <span class="text-xs font-semibold text-amber-400 uppercase tracking-wider">Reconciled Institutional Synthesis</span>
                        </div>
                        <span class="text-[10px] font-mono text-slate-500">Model: gemini-1.5-flash</span>
                    </div>

                    <!-- Loader State -->
                    <div id="queryLoadingState" class="hidden py-8 flex flex-col items-center justify-center text-center space-y-3">
                        <div class="w-8 h-8 border-3 border-amber-500/20 border-t-amber-500 rounded-full animate-spin"></div>
                        <p class="text-sm text-slate-300 font-medium">Nagar Smriti is cross-referencing archival municipal logs...</p>
                        <p class="text-xs text-slate-500">Comparing BWSSB 2002 survey with BESCOM 2019 GIS & 2020 Incident Reports...</p>
                    </div>

                    <!-- Response Text Output -->
                    <div id="queryOutputText" class="prose prose-invert max-w-none text-sm text-slate-300 leading-relaxed space-y-3">
                        <!-- AI content will be inserted here -->
                    </div>
                </div>
            </div>
        </section>

        <!-- SCREEN 3: PERMIT RISK CHECK -->
        <section id="screen-permit" class="hidden space-y-6">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                <!-- Form Column -->
                <div class="lg:col-span-5 bg-slate-900 border border-slate-800 rounded-xl p-5 space-y-4">
                    <div>
                        <h2 class="text-lg font-bold text-white flex items-center gap-2">
                            <i class="fa-solid fa-file-signature text-amber-500"></i>
                            New Excavation Request
                        </h2>
                        <p class="text-xs text-slate-400 mt-1">
                            Run automated preventive risk evaluation before approving new road cutting.
                        </p>
                    </div>

                    <form id="permitForm" onsubmit="handlePermitSubmit(event)" class="space-y-4 pt-2">
                        <div>
                            <label class="block text-xs font-medium text-slate-300 mb-1">Target Street Segment</label>
                            <input type="text" readonly 
                                   value="MG Road, between Junction A (Church Street) and Junction B (Brigade Road)"
                                   class="w-full bg-slate-950 border border-slate-800 text-slate-400 rounded-lg p-2.5 text-xs font-mono cursor-not-allowed" />
                        </div>

                        <div>
                            <label class="block text-xs font-medium text-slate-300 mb-1">Planned Dig Depth</label>
                            <select id="permitDepth" class="w-full bg-slate-950 border border-slate-700 text-slate-200 rounded-lg p-2.5 text-xs focus:border-amber-500 focus:outline-none">
                                <option value="<1m">&lt; 1.0 meter (Shallow Fiber / Footpath)</option>
                                <option value="1-2m" selected>1.0m - 2.0m (Standard Utility / Electrical Conduit Zone)</option>
                                <option value=">2m">&gt; 2.0 meters (Deep Water Trunk / Heavy Sewerage Zone)</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-xs font-medium text-slate-300 mb-1">Requesting Agency / Entity</label>
                            <select id="permitAgency" class="w-full bg-slate-950 border border-slate-700 text-slate-200 rounded-lg p-2.5 text-xs focus:border-amber-500 focus:outline-none">
                                <option value="Private Telecom Contractor">Private Telecom Contractor</option>
                                <option value="BWSSB (Water Dept)">BWSSB (Water & Sewerage)</option>
                                <option value="BESCOM (Electricity)">BESCOM (Electricity)</option>
                                <option value="Roads & Excavation Dept">Roads & Excavation Dept</option>
                                <option value="Gas Utility Provider">Gas Utility Provider</option>
                            </select>
                        </div>

                        <button type="submit" id="permitSubmitBtn"
                                class="w-full bg-amber-600 hover:bg-amber-500 text-slate-950 font-bold py-3 rounded-lg transition flex items-center justify-center gap-2 text-sm shadow-lg shadow-amber-600/20">
                            <i class="fa-solid fa-shield-halved"></i>
                            <span>Evaluate Risk & Reconcile Records</span>
                        </button>
                    </form>
                </div>

                <!-- Result Column -->
                <div class="lg:col-span-7 bg-slate-900 border border-slate-800 rounded-xl p-5 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-800 pb-3 mb-4">
                            <span class="text-xs font-semibold text-slate-400 uppercase tracking-wider flex items-center gap-2">
                                <i class="fa-solid fa-gavel text-amber-500"></i>
                                Risk Assessment & Clearance Verdict
                            </span>
                            <span class="text-[10px] text-slate-500">Preventive Rule Engine</span>
                        </div>

                        <div id="permitInitialState" class="py-12 text-center text-slate-500 space-y-2">
                            <i class="fa-solid fa-clipboard-check text-3xl opacity-30"></i>
                            <p class="text-xs">Fill out the permit details on the left and click "Evaluate Risk".</p>
                        </div>

                        <!-- Permit Loader -->
                        <div id="permitLoadingState" class="hidden py-12 flex flex-col items-center justify-center text-center space-y-3">
                            <div class="w-8 h-8 border-3 border-amber-500/20 border-t-amber-500 rounded-full animate-spin"></div>
                            <p class="text-sm text-slate-300 font-medium">Evaluating historical incident clashes & missing depth layers...</p>
                        </div>

                        <!-- Permit Verdict Output -->
                        <div id="permitResultContent" class="hidden space-y-4">
                            <!-- Badge Header -->
                            <div class="flex items-center gap-3">
                                <div id="verdictBadge" class="px-4 py-2 rounded-lg font-black text-sm tracking-wider uppercase flex items-center gap-2 border">
                                    <!-- Badge content inserted via JS -->
                                </div>
                            </div>

                            <!-- Verdict Reasoning Text -->
                            <div id="verdictReasoning" class="prose prose-invert max-w-none text-xs text-slate-300 leading-relaxed bg-slate-950 p-4 rounded-lg border border-slate-800">
                                <!-- Text inserted via JS -->
                            </div>
                        </div>
                    </div>

                    <div class="mt-4 pt-3 border-t border-slate-800/80 text-[11px] text-slate-500 flex justify-between">
                        <span>Framework: CAG Audit Compliance Protocol</span>
                        <span>Mode: Zero-Silent-Suppression</span>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-800/80 bg-slate-950 py-4 text-center text-xs text-slate-500">
        <p>Nagar Smriti Proof-of-Concept • Hackathon Demo • Powered by Google Gemini 2.5 Flash</p>
    </footer>

    <!-- Application Logic Script -->
    <script type="module">
      function getApiKey() {
  let key = localStorage.getItem("NAGAR_SMRITI_KEY");
  if (!key) {
    key = prompt("Please enter your Gemini API Key:");
    if (key) localStorage.setItem("NAGAR_SMRITI_KEY", key);
  }
  return key;
}
const apiKey = getApiKey();
      
import { GoogleGenAI } from 'https://esm.run/@google/genai';

        // --- Embedded DEMO DATA ---
        const DEMO_DATA = {
            BWSSB: `AGENCY 1 — Bengaluru Water Supply & Sewerage Board (BWSSB)
RECORD TYPE: Underground pipeline map (digitized scan)
SEGMENT: MG Road, between Junction A (Church Street) and Junction B (Brigade Road)
SOURCE MAP BASE YEAR: 2002 road survey
LAST FIELD VERIFICATION: Not recorded since 2002
PIPELINE DETAILS:
  - 450mm sewage trunk line, approximate depth 2.1m, laid 1998
  - 200mm water supply line, approximate depth 1.4m, laid 2002
NOTES (handwritten annotation, transcribed): "Road widened after this map was made — pipeline position relative to current road edge not re-surveyed. Approximate only."
STATUS: No coordinate/GIS data attached. Paper record only, digitized 2019.`,

            BESCOM: `AGENCY 2 — Bangalore Electricity Supply Company (BESCOM)
RECORD TYPE: GIS export (partial network)
SEGMENT: MG Road corridor, Ward 7
NETWORK MAPPING COMPLETENESS: 83% of ward network mapped as of last audit
LAST UPDATED: 2019-11-03
CABLE DETAILS:
  - 11kV underground feeder cable present in this corridor (exact chainage not available — falls in unmapped 17%)
  - Depth: NOT RECORDED (GIS system does not capture depth field)
  - Format: 2D only, no elevation/depth layer
NOTES: Cross-verification with BWSSB or road department records: NONE ON FILE.`,

            ROADS: `AGENCY 3 — Roads & Excavation Permits Department
RECORD TYPE: Road-cutting permit history log
SEGMENT: MG Road, Junction A to Junction B
PERMIT HISTORY:
  - 2015: Permit #RC-2015-0447 issued to telecom contractor for fiber cable laying. Depth logged: "approx 1m". No utility clash reported. No as-built drawing filed after completion (required but not enforced).
  - 2020: Permit #RC-2020-1183 issued to BWSSB for "emergency sewage line repair — pipe location uncertain, located via probing during excavation." Excavation crew reported striking an unmarked electrical conduit at approx. 1.3m depth — no injury, work paused 2 days, no formal report filed with BESCOM afterward.
  - 2023: Citizen complaint (Ref #CC-2023-8821) — "Same stretch of MG Road dug up twice within 8 months, once by water dept, once by telecom. Nobody seems to check what the other did."
NOTES: No unified GIS layer combining all three departments' work on this segment exists as of this filing.`
        };

        const COMBINED_AGENCY_RECORDS = `=== MUNICIPAL ARCHIVAL RECORDS ===\n\n${DEMO_DATA.BWSSB}\n\n${DEMO_DATA.BESCOM}\n\n${DEMO_DATA.ROADS}`;

        // Global State Variable for API Key
        let apiKey = localStorage.getItem('nagar_smriti_gemini_key') || '';

        window.onload = function() {
            if (apiKey) {
                document.getElementById('apiKeyInput').value = apiKey;
            }
        };

        window.saveApiKey = function() {
            const inputVal = document.getElementById('apiKeyInput').value.trim();
            if (!inputVal) {
                alert("Please enter a valid Gemini API key.");
                return;
            }
            apiKey = inputVal;
            localStorage.setItem('nagar_smriti_gemini_key', apiKey);
            alert("Gemini API key saved for this browser session!");
        };

        // Navigation Tab Switching
        window.switchTab = function(tabName) {
            const tabs = ['records', 'query', 'permit'];
            tabs.forEach(t => {
                const btn = document.getElementById(`tab-${t}`);
                const screen = document.getElementById(`screen-${t}`);
                if (t === tabName) {
                    btn.classList.add('border-amber-500', 'text-amber-400');
                    btn.classList.remove('border-transparent', 'text-slate-400');
                    screen.classList.remove('hidden');
                } else {
                    btn.classList.remove('border-amber-500', 'text-amber-400');
                    btn.classList.add('border-transparent', 'text-slate-400');
                    screen.classList.add('hidden');
                }
            });
        };

        window.useQuickQuery = function(qText) {
            document.getElementById('userQueryInput').value = qText;
            document.getElementById('queryForm').requestSubmit();
        };

        // Formatting citations into stylized HTML badges
        function formatCitations(text) {
            if (!text) return '';
            // Replace markdown citations like [BWSSB-2002], [BESCOM-2019], [ROADS-2020], [BWSSB] with styled tags
            return text
                .replace(/\[(BWSSB[^\]]*)\]/gi, '<span class="citation-badge citation-bwssb">💧 $1</span>')
                .replace(/\[(BESCOM[^\]]*)\]/gi, '<span class="citation-badge citation-bescom">⚡ $1</span>')
                .replace(/\[(ROADS[^\]]*|PERMITS[^\]]*)\]/gi, '<span class="citation-badge citation-roads">🚧 $1</span>');
        }

        // --- API CALL 1: Ask Nagar Smriti Chat ---
        window.handleQuerySubmit = async function(e) {
            e.preventDefault();
            const userQuery = document.getElementById('userQueryInput').value.trim();
            if (!userQuery) return;

           let currentKey = apiKey || localStorage.getItem("NAGAR_SMRITI_KEY");
if (!currentKey) {
  currentKey = prompt("Please enter your Gemini API Key:");
  if (currentKey) {
    localStorage.setItem("NAGAR_SMRITI_KEY", currentKey);
  } else {
    return;
  }
}

            const resultContainer = document.getElementById('queryResultContainer');
            const loadingState = document.getElementById('queryLoadingState');
            const outputText = document.getElementById('queryOutputText');
            const conflictAlert = document.getElementById('conflictAlertBox');
            const submitBtn = document.getElementById('querySubmitBtn');

            // UI Reset
            resultContainer.classList.remove('hidden');
            loadingState.classList.remove('hidden');
            outputText.innerHTML = '';
            conflictAlert.classList.add('hidden');
            submitBtn.disabled = true;
            submitBtn.classList.add('opacity-50');

            try {
    const ai = new GoogleGenAI({ apiKey: currentKey });
    const response = await ai.models.generateContent({
      model: 'gemini-1.5-flash',
      contents: prompt,
      config: {
        systemInstruction: systemInstruction,
        temperature: 0.2
      }
    });
                const ai = new GoogleGenAI({ apiKey: currentKey });
                const response = await ai.models.generateContent({
                    model: 'gemini-1.5-flash',
                    contents: prompt,
                    config: {
                        systemInstruction: systemInstruction,
                        temperature: 0.2
                    }
                });

                const rawText = response.text || "No output returned from Nagar Smriti.";
                
                // Parse markdown and inject citation badges
                let parsedHtml = marked.parse(rawText);
                parsedHtml = formatCitations(parsedHtml);

                outputText.innerHTML = parsedHtml;

                // Detect if model flagged conflicts
                if (rawText.toLowerCase().includes('conflict') || 
                    rawText.toLowerCase().includes('contradict') || 
                    rawText.toLowerCase().includes('unmarked') ||
                    rawText.toLowerCase().includes('mismatch') ||
                    rawText.toLowerCase().includes('gap')) {
                    conflictAlert.classList.remove('hidden');
                }

            } catch (err) {
                console.error(err);
                outputText.innerHTML = `<div class="p-3 bg-red-950/60 border border-red-800 text-red-300 rounded-lg text-xs">
                    <strong>API Error:</strong> ${err.message || 'Failed to communicate with Gemini API. Check your API key.'}
                </div>`;
            } finally {
                loadingState.classList.add('hidden');
                submitBtn.disabled = false;
                submitBtn.classList.remove('opacity-50');
            }
        };

        // --- API CALL 2: Permit Risk Checker ---
        window.handlePermitSubmit = async function(e) {
            e.preventDefault();

            if (!apiKey) {
                alert("Please enter your Gemini API Key in the top bar before submitting!");
                document.getElementById('apiKeyInput').focus();
                return;
            }

            const depth = document.getElementById('permitDepth').value;
            const agency = document.getElementById('permitAgency').value;

            const initialState = document.getElementById('permitInitialState');
            const loadingState = document.getElementById('permitLoadingState');
            const resultContent = document.getElementById('permitResultContent');
            const verdictBadge = document.getElementById('verdictBadge');
            const verdictReasoning = document.getElementById('verdictReasoning');
            const submitBtn = document.getElementById('permitSubmitBtn');

            initialState.classList.add('hidden');
            resultContent.classList.add('hidden');
            loadingState.classList.remove('hidden');
            submitBtn.disabled = true;
            submitBtn.classList.add('opacity-50');

            const systemInstruction = `You are a preventive risk-checker for excavation permits. Given the same three agency records as before and these new permit request details, determine whether there is enough consistent information to safely approve this dig, or whether there are unresolved conflicts/gaps that should trigger mandatory physical verification first. Give a clear verdict — APPROVE, APPROVE WITH CONDITIONS, or HOLD FOR VERIFICATION — with your reasoning and citations, in under 120 words. Format the first line as EXACTLY one of: "VERDICT: APPROVE", "VERDICT: APPROVE WITH CONDITIONS", or "VERDICT: HOLD FOR VERIFICATION".`;

            const prompt = `AGENCY RECORDS:\n${COMBINED_AGENCY_RECORDS}\n\nNEW PERMIT REQUEST:\nStreet: MG Road (Junction A to B)\nDepth requested: ${depth}\nRequesting Entity: ${agency}`;

            try {
                const ai = new GoogleGenAI({ apiKey: apiKey });
                const response = await ai.models.generateContent({
                    model: 'gemini-1.5-flash',
                    contents: prompt,
                    config: {
                        systemInstruction: systemInstruction,
                        temperature: 0.1
                    }
                });

                const rawText = response.text || "VERDICT: HOLD FOR VERIFICATION\nUnable to verify.";

                // Parse Verdict Tag
                let verdictType = "HOLD FOR VERIFICATION";
                if (rawText.includes("VERDICT: APPROVE WITH CONDITIONS")) {
                    verdictType = "APPROVE WITH CONDITIONS";
                } else if (rawText.includes("VERDICT: APPROVE") && !rawText.includes("CONDITIONS")) {
                    verdictType = "APPROVE";
                } else if (rawText.includes("HOLD FOR VERIFICATION")) {
                    verdictType = "HOLD FOR VERIFICATION";
                }

                // Render Badge
                if (verdictType === "APPROVE") {
                    verdictBadge.className = "px-4 py-2 rounded-lg font-black text-sm uppercase tracking-wider bg-emerald-950 border-emerald-500 text-emerald-400 flex items-center gap-2";
                    verdictBadge.innerHTML = `<i class="fa-solid fa-circle-check text-emerald-400"></i> APPROVE`;
                } else if (verdictType === "APPROVE WITH CONDITIONS") {
                    verdictBadge.className = "px-4 py-2 rounded-lg font-black text-sm uppercase tracking-wider bg-amber-950 border-amber-500 text-amber-300 flex items-center gap-2";
                    verdictBadge.innerHTML = `<i class="fa-solid fa-triangle-exclamation text-amber-400"></i> APPROVE WITH CONDITIONS`;
                } else {
                    verdictBadge.className = "px-4 py-2 rounded-lg font-black text-sm uppercase tracking-wider bg-rose-950 border-rose-500 text-rose-300 flex items-center gap-2";
                    verdictBadge.innerHTML = `<i class="fa-solid fa-ban text-rose-400"></i> HOLD FOR VERIFICATION`;
                }

                // Clean reasoning text & format citations
                let cleanReasoning = rawText.replace(/VERDICT:\s*[A-Z\s]+/g, '').trim();
                let parsedHtml = marked.parse(cleanReasoning);
                parsedHtml = formatCitations(parsedHtml);

                verdictReasoning.innerHTML = parsedHtml;
                resultContent.classList.remove('hidden');

            } catch (err) {
                console.error(err);
                verdictReasoning.innerHTML = `<span class="text-red-400">Error: ${err.message || 'Failed to complete risk evaluation.'}</span>`;
                resultContent.classList.remove('hidden');
            } finally {
                loadingState.classList.add('hidden');
                submitBtn.disabled = false;
                submitBtn.classList.remove('opacity-50');
            }
        };
    </script>
</body>
</html>
