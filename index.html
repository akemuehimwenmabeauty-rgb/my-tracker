<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phase 0 Protocol Dashboard</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
</head>
<body class="bg-slate-950 text-slate-100 font-sans min-h-screen p-3 md:p-6 flex flex-col items-center selection:bg-indigo-500/30">

    <div class="w-full max-w-xl bg-slate-900 rounded-2xl shadow-2xl p-5 md:p-6 mt-2 md:mt-6 border border-slate-800/80 backdrop-blur-md">
        
        <div class="flex items-center justify-between border-b border-slate-800 pb-4 mb-5">
            <div>
                <h1 class="text-xl md:text-2xl font-black uppercase tracking-wider text-transparent bg-clip-text bg-gradient-to-r fancy-gradient from-indigo-400 via-purple-400 to-pink-400">Phase 0 Dashboard 🎯</h1>
                <p class="text-slate-500 text-xs font-semibold tracking-wide uppercase mt-0.5">Surgical Forex Extractions Protocol</p>
            </div>
            <div class="bg-slate-950/60 border border-slate-800 rounded-xl px-3 py-1.5 text-right">
                <span id="clock" class="text-xs font-mono font-bold text-slate-400 tracking-widest">00:00:00 WAT</span>
            </div>
        </div>

        <div class="grid grid-cols-3 gap-3 mb-5">
            <div class="bg-slate-950/40 border border-slate-800/60 rounded-xl p-3 text-center transition-all hover:border-slate-700/60">
                <div class="text-[10px] text-slate-500 font-bold uppercase tracking-wider">Extractions</div>
                <div class="flex items-center justify-center gap-1.5 mt-1">
                    <button id="minusCount" class="w-5 h-5 rounded bg-slate-800 hover:bg-slate-700 flex items-center justify-center text-xs font-bold active:scale-90 transition-all">-</button>
                    <div id="extractionCount" class="text-base md:text-lg font-black text-emerald-400 font-mono">5</div>
                    <button id="plusCount" class="w-5 h-5 rounded bg-slate-800 hover:bg-slate-700 flex items-center justify-center text-xs font-bold active:scale-90 transition-all">+</button>
                </div>
            </div>
            <div class="bg-slate-950/40 border border-slate-800/60 rounded-xl p-3 text-center transition-all hover:border-slate-700/60">
                <div class="text-[10px] text-slate-500 font-bold uppercase tracking-wider">Target Objective</div>
                <div class="text-base md:text-lg font-black text-slate-300 font-mono mt-1">50</div>
            </div>
            <div class="bg-slate-950/40 border border-slate-800/60 rounded-xl p-3 text-center transition-all hover:border-slate-700/60">
                <div class="text-[10px] text-slate-500 font-bold uppercase tracking-wider">Progress</div>
                <div id="progressPercent" class="text-base md:text-lg font-black text-indigo-400 font-mono mt-1">10%</div>
            </div>
        </div>

        <div class="w-full bg-slate-950 rounded-full h-2 mb-6 border border-slate-800/50 overflow-hidden">
            <div id="progressBar" class="bg-gradient-to-r from-indigo-500 to-purple-500 h-full rounded-full transition-all duration-500 ease-out" style="width: 10%心里"></div>
        </div>

        <div class="space-y-4">
            
            <div>
                <label class="block text-[10px] font-bold uppercase tracking-widest text-slate-400 mb-2">Tactical Operations Trigger</label>
                <div class="grid grid-cols-2 gap-2.5">
                    <button id="strikeBtn" class="bg-emerald-600/10 border border-emerald-500/30 text-emerald-400 hover:bg-emerald-600/20 font-bold py-2.5 px-3 rounded-xl flex items-center justify-center gap-2 text-xs uppercase tracking-wider transition-all active:scale-95 cursor-pointer">
                        <i data-lucide="crosshair" class="w-4 h-4"></i> Strike Authorized
                    </button>
                    <button id="vetoBtn" class="bg-rose-600/10 border border-rose-500/30 text-rose-400 hover:bg-rose-600/20 font-bold py-2.5 px-3 rounded-xl flex items-center justify-center gap-2 text-xs uppercase tracking-wider transition-all active:scale-95 cursor-pointer">
                        <i data-lucide="ban" class="w-4 h-4"></i> Veto Mandated
                    </button>
                </div>
            </div>

            <div>
                <label class="block text-[10px] font-bold uppercase tracking-widest text-slate-400 mb-1.5">Active Workspace Log</label>
                <div class="relative">
                    <textarea id="logInput" rows="7" class="w-full bg-slate-950/80 border border-slate-800 rounded-xl p-3 text-slate-200 focus:outline-none focus:border-indigo-500 placeholder-slate-600 text-sm font-mono leading-relaxed transition-all resize-none" placeholder="// Paste or record operational frameworks, ATR/ADX evaluations, session rules, or extraction metrics..."></textarea>
                    <div class="absolute bottom-2.5 right-2.5 flex items-center gap-1.5 bg-slate-900/90 border border-slate-800 px-2 py-1 rounded-md text-[10px] font-mono text-slate-500">
                        <i data-lucide="database" class="w-3 h-3"></i> Sync Live
                    </div>
                </div>
            </div>
            
            <button id="saveBtn" class="w-full bg-indigo-600 hover:bg-indigo-500 text-white font-bold py-3.5 rounded-xl transition duration-200 shadow-xl shadow-indigo-600/10 active:scale-[0.98] flex items-center justify-center gap-2 text-sm uppercase tracking-wider cursor-pointer">
                <i data-lucide="save" class="w-4 h-4"></i> Commit Context Changes
            </button>
        </div>

        <div id="statusMsg" class="text-center text-xs font-semibold text-emerald-400 mt-4 opacity-0 transition-opacity duration-300 flex items-center justify-center gap-1.5">
            <i data-lucide="check-circle" class="w-3.5 h-3.5"></i> Operations safe-saved to device matrix!
        </div>
    </div>

    <script>
        // Start Lucide Icon Matrix
        lucide.createIcons();

        // Target Elements DOM
        const logInput = document.getElementById('logInput');
        const saveBtn = document.getElementById('saveBtn');
        const strikeBtn = document.getElementById('strikeBtn');
        const vetoBtn = document.getElementById('vetoBtn');
        const statusMsg = document.getElementById('statusMsg');
        const countDisplay = document.getElementById('extractionCount');
        const progressPercent = document.getElementById('progressPercent');
        const progressBar = document.getElementById('progressBar');
        const plusCount = document.getElementById('plusCount');
        const minusCount = document.getElementById('minusCount');

        // State Metrics Memory Layout
        let state = {
            extractions: 5,
            target: 50,
            logText: ""
        };

        // Initialize Audio Framework Engine
        let audioCtx = null;
        function initAudio() {
            if (!audioCtx) {
                audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            }
        }

        // Tactical Sound Core Driver
        function playSound(type) {
            try {
                initAudio();
                if (!audioCtx) return;
                
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.connect(gain);
                gain.connect(audioCtx.destination);

                const now = audioCtx.currentTime;

                switch(type) {
                    case 'click':
                        osc.type = 'sine';
                        osc.frequency.setValueAtTime(1200, now);
                        osc.frequency.exponentialRampToValueAtTime(800, now + 0.05);
                        gain.gain.setValueAtTime(0.05, now);
                        gain.gain.linearRampToValueAtTime(0.001, now + 0.05);
                        osc.start(now);
                        osc.stop(now + 0.05);
                        break;
                        
                    case 'success':
                        // High-pitch laser double-beep for TP Hit
                        [0, 0.08].forEach((delay) => {
                            const o = audioCtx.createOscillator();
                            const g = audioCtx.createGain();
                            o.connect(g);
                            g.connect(audioCtx.destination);
                            o.type = 'triangle';
                            o.frequency.setValueAtTime(1500 + (delay * 1000), audioCtx.currentTime + delay);
                            o.frequency.exponentialRampToValueAtTime(2000, audioCtx.currentTime + delay + 0.08);
                            g.gain.setValueAtTime(0.05, audioCtx.currentTime + delay);
                            g.gain.linearRampToValueAtTime(0.001, audioCtx.currentTime + delay + 0.08);
                            o.start(audioCtx.currentTime + delay);
                            o.stop(audioCtx.currentTime + delay + 0.08);
                        });
                        break;
                        
                    case 'veto':
                        // Deep structural lock hum
                        osc.type = 'sawtooth';
                        osc.frequency.setValueAtTime(1500, now);
                        osc.frequency.linearRampToValueAtTime(80, now + 0.25);
                        
                        const filter = audioCtx.createBiquadFilter();
                        filter.type = 'lowpass';
                        filter.frequency.setValueAtTime(300, now);
                        
                        osc.disconnect(gain);
                        osc.connect(filter);
                        filter.connect(gain);
                        
                        gain.gain.setValueAtTime(0.12, now);
                        gain.gain.linearRampToValueAtTime(0.001, now + 0.25);
                        osc.start(now);
                        osc.stop(now + 0.25);
                        break;
                }
            } catch (e) {
                console.log("Audio Engine context block restriction:", e);
            }
        }

        // Calculate and Adjust HUD Statistics
        function updateHUD() {
            countDisplay.textContent = state.extractions;
            const pct = Math.round((state.extractions / state.target) * 100);
            progressPercent.textContent = `${pct}%`;
            progressBar.style.width = `${pct}%`;
        }

        // Commit Updates to Local Core Storage
        function saveStateToStorage() {
            localStorage.setItem('phase0_core_state', JSON.stringify(state));
        }

        // Load Matrix from Storage Context
        window.addEventListener('DOMContentLoaded', () => {
            const rawData = localStorage.getItem('phase0_core_state');
            if (rawData) {
                state = JSON.parse(rawData);
                logInput.value = state.logText || "";
            } else {
                state.logText = logInput.value;
            }
            updateHUD();
        });

        // Appending Metric Modifiers 
        plusCount.addEventListener('click', () => {
            playSound('click');
            if(state.extractions < state.target) {
                state.extractions++;
                updateHUD();
                saveStateToStorage();
            }
        });

        minusCount.addEventListener('click', () => {
            playSound('click');
            if(state.extractions > 0) {
                state.extractions--;
                updateHUD();
                saveStateToStorage();
            }
        });

        // Trigger Executions Action Hooks
        strikeBtn.addEventListener('click', () => {
            playSound('success');
            // Flash a visual context trace to console output field
            logInput.value += `\n[${new Date().toLocaleTimeString('en-GB')} WAT] // CRITICAL: STRIKE AUTHORIZED ENGINE. TARGET DEPLOYED.`;
            state.logText = logInput.value;
            saveStateToStorage();
        });

        vetoBtn.addEventListener('click', () => {
            playSound('veto');
            logInput.value += `\n[${new Date().toLocaleTimeString('en-GB')} WAT] // NOTICE: VETO INTERCEPT ACTION MANDATED. OUT.`;
            state.logText = logInput.value;
            saveStateToStorage();
        });

        // Universal Save Button Action
        saveBtn.addEventListener('click', () => {
            playSound('click');
            state.logText = logInput.value;
            saveStateToStorage();

            // Flash Success Notice on HUD
            statusMsg.classList.remove('opacity-0');
            setTimeout(() => {
                statusMsg.classList.add('opacity-0');
            }, 2500);
        });

        // Live Real-Time WAT Clock Matrix 
        function updateClock() {
            const now = new Date();
            // Force calculations directly into West Africa Time (WAT) formatting format
            const options = { timeZone: 'Africa/Lagos', hour12: false, hour: '2-digit', minute: '2-digit', second: '2-digit' };
            const timeString = now.toLocaleTimeString('en-GB', options);
            document.getElementById('clock').textContent = `${timeString} WAT`;
        }
        setInterval(updateClock, 1000);
        updateClock();
    </script>
</body>
</html>
