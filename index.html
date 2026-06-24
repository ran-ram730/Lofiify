<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lofiify - Convert Any Song to Lofi</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Font (Inter & Nunito) -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Nunito:wght@400;700;900&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        body {
            font-family: 'Nunito', 'Inter', sans-serif;
            background: linear-gradient(135deg, #0f0c1b 0%, #201335 50%, #2b1029 100%);
            color: #f7ebfd;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: rgba(15, 12, 27, 0.5);
        }
        ::-webkit-scrollbar-thumb {
            background: #ff7597;
            border-radius: 3px;
        }
        /* Cassette rotation */
        @keyframes rotate-wheel {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        .spinning {
            animation: rotate-wheel 4s linear infinite;
        }
        /* Pulse for glowing elements */
        @keyframes gentle-pulse {
            0%, 100% { opacity: 0.6; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.03); }
        }
        .glowing-bg {
            animation: gentle-pulse 4s ease-in-out infinite;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-between p-4 md:p-8 overflow-x-hidden">

<header class="w-full max-w-5xl flex justify-between items-center mb-6">
    <div class="flex items-center gap-3">
        <div class="w-10 h-10 bg-gradient-to-tr from-pink-500 to-amber-500 rounded-xl flex items-center justify-center shadow-lg shadow-pink-500/20">
            <i class="fa-solid fa-compact-disc text-white text-xl animate-spin" style="animation-duration: 6s;"></i>
        </div>
        <div>
            <h1 class="text-2xl font-black tracking-wide bg-gradient-to-r from-pink-400 via-purple-300 to-amber-300 bg-clip-text text-transparent">LOFIIFY</h1>
            <p class="text-xs text-purple-300/80">लो-फाई मैजिक कनवर्टर</p>
        </div>
    </div>
    <div class="hidden sm:flex items-center gap-2 bg-purple-950/40 px-3 py-1.5 rounded-full border border-purple-500/20">
        <span class="w-2.5 h-2.5 rounded-full bg-emerald-500 animate-ping"></span>
        <span class="text-xs font-semibold text-emerald-400">Offline Processing Supported</span>
    </div>
</header>

<main class="w-full max-w-5xl grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch mb-8">
    
    <!-- Left Column: Visualizer & Cassette Animation -->
    <div class="lg:col-span-5 flex flex-col justify-between bg-purple-950/30 border border-purple-500/20 rounded-3xl p-6 backdrop-blur-md shadow-2xl relative overflow-hidden min-h-[350px]">
        <!-- Ambient Glowing Background Grid -->
        <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-pink-600/10 via-transparent to-transparent pointer-events-none glowing-bg"></div>
        
        <!-- Tape Header / Status -->
        <div class="flex justify-between items-center z-10">
            <span class="text-xs font-bold uppercase tracking-wider text-amber-300 bg-amber-950/50 px-2.5 py-1 rounded-md border border-amber-500/20" id="status-label">
                <i class="fa-solid fa-hourglass-start mr-1"></i> No Song Loaded
            </span>
            <div class="flex gap-1.5" id="recording-indicator" style="display: none;">
                <span class="w-3 h-3 rounded-full bg-red-500 animate-pulse"></span>
                <span class="text-xs text-red-400 font-bold">RECORDING...</span>
            </div>
        </div>

        <!-- Rotating Retro Cassette Animation -->
        <div class="my-6 flex justify-center items-center z-10 relative">
            <div class="w-72 h-44 bg-gradient-to-b from-[#2e1a47] to-[#1a0e2a] border-4 border-purple-900/80 rounded-xl relative shadow-2xl flex flex-col justify-between p-3">
                <!-- Cassette Top Decor -->
                <div class="w-full h-4 bg-[#140b21] rounded flex justify-between items-center px-4 text-[9px] text-pink-400/60 font-mono">
                    <span>A-SIDE</span>
                    <span>100% RETRO LOFI</span>
                </div>
                <!-- Cassette Windows and Reels -->
                <div class="w-full h-20 bg-gradient-to-r from-purple-950 to-indigo-950 rounded border-2 border-purple-900/60 flex justify-center items-center gap-10 relative">
                    <!-- Left Reel -->
                    <div class="w-14 h-14 rounded-full border-4 border-dashed border-pink-500/40 bg-zinc-900 flex items-center justify-center">
                        <div class="w-8 h-8 rounded-full bg-amber-500/80 flex items-center justify-center" id="reel-left">
                            <div class="w-3 h-3 rounded-full bg-zinc-950"></div>
                        </div>
                    </div>
                    <!-- Middle Window Label -->
                    <div class="absolute w-20 h-6 bg-[#25153a] border border-purple-800/40 rounded flex flex-col justify-center items-center text-[8px] text-amber-200/50">
                        <span class="truncate max-w-[70px]" id="cassette-title">No Audio</span>
                    </div>
                    <!-- Right Reel -->
                    <div class="w-14 h-14 rounded-full border-4 border-dashed border-pink-500/40 bg-zinc-900 flex items-center justify-center">
                        <div class="w-8 h-8 rounded-full bg-amber-500/80 flex items-center justify-center" id="reel-right">
                            <div class="w-3 h-3 rounded-full bg-zinc-950"></div>
                        </div>
                    </div>
                </div>
                <!-- Cassette Bottom Decor -->
                <div class="w-full h-6 bg-[#231536] rounded-b flex justify-around items-center text-[10px] text-purple-400/40 font-mono">
                    <div class="flex gap-1"><span class="w-2 h-1 bg-pink-500/50 rounded-full"></span><span class="w-2 h-1 bg-amber-500/50 rounded-full"></span></div>
                    <span>C-90</span>
                    <i class="fa-solid fa-music"></i>
                </div>
            </div>
        </div>

        <!-- Atmospheric Canvas Waveform / Rain Visualizer -->
        <div class="relative w-full h-24 bg-[#140a22]/80 border border-purple-900/50 rounded-2xl overflow-hidden z-10">
            <canvas id="visualizer" class="w-full h-full block"></canvas>
            <div class="absolute bottom-2 left-3 text-[10px] text-pink-400/40 font-mono uppercase tracking-wider flex items-center gap-1">
                <span class="w-1.5 h-1.5 rounded-full bg-pink-500/50 animate-pulse"></span> Ambient Visualiser
            </div>
        </div>
    </div>

    <!-- Right Column: Upload Panel & Effects Board -->
    <div class="lg:col-span-7 bg-purple-950/20 border border-purple-500/10 rounded-3xl p-6 backdrop-blur-md flex flex-col justify-between">
        
        <div class="space-y-4">
            <div id="drop-zone" class="border-2 border-dashed border-purple-500/30 hover:border-pink-500/60 rounded-2xl p-6 transition-all duration-300 cursor-pointer bg-purple-950/10 hover:bg-purple-950/30 flex flex-col items-center justify-center text-center relative group">
                <input type="file" id="file-input" accept="audio/*" class="absolute inset-0 opacity-0 cursor-pointer z-20">
                <div class="w-12 h-12 rounded-full bg-purple-900/30 group-hover:bg-pink-500/20 flex items-center justify-center transition-all duration-300 mb-3">
                    <i class="fa-solid fa-cloud-arrow-up text-pink-400 text-xl group-hover:scale-110 transition-transform"></i>
                </div>
                <h3 class="font-bold text-base text-pink-300 group-hover:text-pink-200">अपना पसंदीदा गाना यहाँ डालें / Upload Your Song</h3>
                <p class="text-xs text-purple-300/60 mt-1">Drag and drop any audio file here (MP3, WAV, M4A, etc.)</p>
                <span class="text-xs text-amber-300/80 mt-2 bg-amber-950/30 px-3 py-1 rounded-full border border-amber-500/10" id="file-name-display">Koi file select nahi hai</span>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <!-- Slow & Pitched Down (Tempo) -->
                <div class="bg-purple-950/40 p-4 rounded-2xl border border-purple-900/40">
                    <div class="flex justify-between items-center mb-1">
                        <label class="text-sm font-semibold flex items-center gap-1 text-pink-200">
                            <i class="fa-solid fa-clock text-pink-400"></i> Speed / Tempo (लो-फाई पिच)
                        </label>
                        <span id="speed-val" class="text-xs font-mono text-amber-300">80%</span>
                    </div>
                    <input type="range" id="param-speed" min="50" max="100" value="80" class="w-full accent-pink-500 cursor-pointer h-1.5 bg-purple-900 rounded-lg appearance-none">
                    <p class="text-[10px] text-purple-300/50 mt-1">Slowing down automatically lowers the pitch for warm aesthetics.</p>
                </div>

                <!-- Lowpass Muffle Filter -->
                <div class="bg-purple-950/40 p-4 rounded-2xl border border-purple-900/40">
                    <div class="flex justify-between items-center mb-1">
                        <label class="text-sm font-semibold flex items-center gap-1 text-pink-200">
                            <i class="fa-solid fa-filter text-indigo-400"></i> Muffle / Lowpass (धुंधलापन)
                        </label>
                        <span id="lowpass-val" class="text-xs font-mono text-amber-300">1200 Hz</span>
                    </div>
                    <input type="range" id="param-lowpass" min="400" max="8000" value="1200" class="w-full accent-indigo-400 cursor-pointer h-1.5 bg-purple-900 rounded-lg appearance-none">
                    <p class="text-[10px] text-purple-300/50 mt-1">Cuts higher frequencies to give that vintage "through the wall" sound.</p>
                </div>

                <!-- Ambient Rain Synth -->
                <div class="bg-purple-950/40 p-4 rounded-2xl border border-purple-900/40">
                    <div class="flex justify-between items-center mb-1">
                        <label class="text-sm font-semibold flex items-center gap-1 text-pink-200">
                            <i class="fa-solid fa-cloud-showers-heavy text-blue-400 animate-bounce"></i> Rain Atmosphere (बारिश)
                        </label>
                        <span id="rain-val" class="text-xs font-mono text-amber-300">20%</span>
                    </div>
                    <input type="range" id="param-rain" min="0" max="100" value="20" class="w-full accent-blue-400 cursor-pointer h-1.5 bg-purple-900 rounded-lg appearance-none">
                </div>

                <!-- Vinyl Crackle Synth -->
                <div class="bg-purple-950/40 p-4 rounded-2xl border border-purple-900/40">
                    <div class="flex justify-between items-center mb-1">
                        <label class="text-sm font-semibold flex items-center gap-1 text-pink-200">
                            <i class="fa-solid fa-circle-dot text-amber-400"></i> Vinyl Crackle (विनाइल कड़कड़)
                        </label>
                        <span id="crackle-val" class="text-xs font-mono text-amber-300">30%</span>
                    </div>
                    <input type="range" id="param-crackle" min="0" max="100" value="30" class="w-full accent-amber-400 cursor-pointer h-1.5 bg-purple-900 rounded-lg appearance-none">
                </div>

                <!-- Spacious Reverb -->
                <div class="bg-purple-950/40 p-4 rounded-2xl border border-purple-900/40">
                    <div class="flex justify-between items-center mb-1">
                        <label class="text-sm font-semibold flex items-center gap-1 text-pink-200">
                            <i class="fa-solid fa-mountain text-emerald-400"></i> Spacious Reverb (गूंज)
                        </label>
                        <span id="reverb-val" class="text-xs font-mono text-amber-300">40%</span>
                    </div>
                    <input type="range" id="param-reverb" min="0" max="100" value="40" class="w-full accent-emerald-400 cursor-pointer h-1.5 bg-purple-900 rounded-lg appearance-none">
                </div>

                <!-- Tape Flutter / Wobble -->
                <div class="bg-purple-950/40 p-4 rounded-2xl border border-purple-900/40">
                    <div class="flex justify-between items-center mb-1">
                        <label class="text-sm font-semibold flex items-center gap-1 text-pink-200">
                            <i class="fa-solid fa-waveform text-rose-400"></i> Tape Flutter (आवाज़ का डगमगाना)
                        </label>
                        <span id="flutter-val" class="text-xs font-mono text-amber-300">35%</span>
                    </div>
                    <input type="range" id="param-flutter" min="0" max="100" value="35" class="w-full accent-rose-400 cursor-pointer h-1.5 bg-purple-900 rounded-lg appearance-none">
                </div>
            </div>
        </div>

        <div class="mt-6 pt-4 border-t border-purple-900/30 flex flex-col gap-4">
            <!-- Progress Bar -->
            <div class="flex items-center gap-3">
                <span id="curr-time" class="text-xs font-mono text-purple-400">00:00</span>
                <div class="flex-1 h-2 bg-purple-900/50 rounded-full relative overflow-hidden cursor-pointer" id="progress-bar-container">
                    <div id="progress-bar-fill" class="w-0 h-full bg-gradient-to-r from-pink-500 to-amber-500 rounded-full"></div>
                </div>
                <span id="total-time" class="text-xs font-mono text-purple-400">00:00</span>
            </div>

            <!-- Controller Buttons -->
            <div class="flex flex-wrap items-center justify-between gap-4">
                <!-- Playback Action Row -->
                <div class="flex items-center gap-3">
                    <button id="btn-play-pause" class="px-6 py-3 bg-gradient-to-r from-pink-500 to-amber-500 hover:from-pink-600 hover:to-amber-600 text-white font-bold rounded-2xl shadow-lg shadow-pink-500/20 active:scale-95 transition-all flex items-center gap-2 text-sm disabled:opacity-40" disabled>
                        <i class="fa-solid fa-play"></i> <span id="btn-play-text">PLAY LOFI</span>
                    </button>
                    <button id="btn-stop" class="p-3 bg-purple-900/40 hover:bg-purple-900/60 border border-purple-700/30 text-purple-300 rounded-2xl active:scale-95 transition-all disabled:opacity-40" disabled>
                        <i class="fa-solid fa-stop"></i>
                    </button>
                </div>

                <!-- Record & Export Action Row -->
                <div class="flex items-center gap-2">
                    <button id="btn-record" class="px-4 py-2 bg-purple-900/40 hover:bg-[#c93b3b]/20 hover:border-red-500 border border-purple-700/30 text-purple-300 hover:text-red-400 font-semibold rounded-2xl active:scale-95 transition-all flex items-center gap-2 text-xs disabled:opacity-40" disabled>
                        <i class="fa-solid fa-microphone"></i> <span id="btn-record-text">Record Remix</span>
                    </button>
                    <button id="btn-download" class="px-4 py-2 bg-emerald-500/20 hover:bg-emerald-500/30 border border-emerald-500/40 text-emerald-300 font-semibold rounded-2xl active:scale-95 transition-all flex items-center gap-2 text-xs" style="display: none;">
                        <i class="fa-solid fa-download"></i> Save Lofi Track (.webm)
                    </button>
                </div>
            </div>
        </div>

    </div>
</main>

<!-- Info & Instruction Section -->
<footer class="w-full max-w-5xl text-center space-y-2 py-4 border-t border-purple-500/10">
    <div class="flex justify-center gap-6 text-sm text-purple-400/80 flex-wrap">
        <span class="flex items-center gap-1"><i class="fa-solid fa-music text-pink-400"></i> No Servers! Safe Processing</span>
        <span class="flex items-center gap-1"><i class="fa-solid fa-headphones text-amber-400"></i> Headphones Recommended</span>
        <span class="flex items-center gap-1"><i class="fa-solid fa-sliders text-indigo-400"></i> Fully Adjustable Controls</span>
    </div>
    <p class="text-xs text-purple-300/40">© 2026 Lofiify. Crafted with cozy vintage magic & HTML5 Web Audio API.</p>
</footer>

<script>
/* Audio Engine Setup */
let audioCtx = null;
let mainAudioBuffer = null;
let currentSongSourceNode = null;

// Audio Nodes Reference
let gainNode = null;         // Master track gain
let filterNode = null;       // Lowpass filter
let convolverNode = null;   // Spacious reverb
let dryReverbGain = null;    // Main direct channel to bypass reverb dry mix
let wetReverbGain = null;    // Direct wet channel from convolver
let lfoNode = null;          // LFO for pitch flutter
let lfoGainNode = null;      // Flutter intensity
let masterVolumeNode = null; // Final sum mix output
let analyserNode = null;     // Visualizer node

// Ambience Synthesizers Nodes
let rainSourceNode = null;
let rainGainNode = null;
let crackleSourceNode = null;
let crackleGainNode = null;

// Built-in Synth Audio Buffers
let rainBuffer = null;
let crackleBuffer = null;
let impulseResponseBuffer = null; // Reverb room

// Playback Logic Parameters
let isPlaying = false;
let startTime = 0;
let pausedAt = 0;
let songDuration = 0;
let playbackTimerInterval = null;

// Recorder variables
let mediaRecorder = null;
let recordedChunks = [];
let audioDestinationNode = null; // Media stream dest for exporting
let isRecording = false;

/* Initialise UI DOM Elements */
const fileInput = document.getElementById('file-input');
const dropZone = document.getElementById('drop-zone');
const fileNameDisplay = document.getElementById('file-name-display');
const btnPlayPause = document.getElementById('btn-play-pause');
const btnPlayText = document.getElementById('btn-play-text');
const btnStop = document.getElementById('btn-stop');
const btnRecord = document.getElementById('btn-record');
const btnRecordText = document.getElementById('btn-record-text');
const btnDownload = document.getElementById('btn-download');
const cassetteTitle = document.getElementById('cassette-title');
const statusLabel = document.getElementById('status-label');
const reelLeft = document.getElementById('reel-left');
const reelRight = document.getElementById('reel-right');

// Progress Bar
const currTimeSpan = document.getElementById('curr-time');
const totalTimeSpan = document.getElementById('total-time');
const progressContainer = document.getElementById('progress-bar-container');
const progressFill = document.getElementById('progress-bar-fill');

// Visualizer Canvas
const canvas = document.getElementById('visualizer');
const canvasCtx = canvas.getContext('2d');

function resizeCanvas() {
    canvas.width = canvas.parentElement.clientWidth * window.devicePixelRatio;
    canvas.height = canvas.parentElement.clientHeight * window.devicePixelRatio;
}
window.addEventListener('resize', resizeCanvas);
resizeCanvas();

function initAudio() {
    if (audioCtx) return;

    // Use standard AudioContext compatible with multiple browsers
    const AudioContextClass = window.AudioContext || window.webkitAudioContext;
    audioCtx = new AudioContextClass();

    // Create sum master gain node
    masterVolumeNode = audioCtx.createGain();
    masterVolumeNode.gain.value = 1.0;

    // Connect analyzer
    analyserNode = audioCtx.createAnalyser();
    analyserNode.fftSize = 256;
    masterVolumeNode.connect(analyserNode);

    // Audio recording destination
    audioDestinationNode = audioCtx.createMediaStreamDestination();
    
    // Connect final mix out to physical speakers AND to recorder stream
    masterVolumeNode.connect(audioCtx.destination);
    masterVolumeNode.connect(audioDestinationNode);

    // Generate custom ambiance synthesizers buffers offline for zero latency
    rainBuffer = generateRainBuffer(audioCtx, 10); // 10 seconds loopable rain
    crackleBuffer = generateCrackleBuffer(audioCtx, 8); // 8 seconds loopable vintage vinyl
    impulseResponseBuffer = generateReverbImpulse(audioCtx, 3.5, 2.5); // 3.5 seconds roomy reverb IR
}

// Pink noise synthesis algorithm (Paul Kellet's refined formula) for cozy rain sound
function generateRainBuffer(ctx, duration) {
    const sampleRate = ctx.sampleRate;
    const totalSamples = sampleRate * duration;
    const buffer = ctx.createBuffer(1, totalSamples, sampleRate);
    const data = buffer.getChannelData(0);
    
    let b0 = 0, b1 = 0, b2 = 0, b3 = 0, b4 = 0, b5 = 0, b6 = 0;
    
    for (let i = 0; i < totalSamples; i++) {
        const white = Math.random() * 2 - 1;
        b0 = 0.99886 * b0 + white * 0.0555179;
        b1 = 0.99332 * b1 + white * 0.0750759;
        b2 = 0.96900 * b2 + white * 0.1538520;
        b3 = 0.86650 * b3 + white * 0.3104856;
        b4 = 0.55000 * b4 + white * 0.5329522;
        b5 = -0.7616 * b5 - white * 0.0168980;
        data[i] = b0 + b1 + b2 + b3 + b4 + b5 + b6 + white * 0.5362;
        data[i] *= 0.08; // Safe balance level
        b6 = white * 0.115926;
    }
    return buffer;
}

// Vintage Vinyl Crackle Synthesizer (low rumble + random highpass crackles)
function generateCrackleBuffer(ctx, duration) {
    const sampleRate = ctx.sampleRate;
    const totalSamples = sampleRate * duration;
    const buffer = ctx.createBuffer(1, totalSamples, sampleRate);
    const data = buffer.getChannelData(0);
    
    for (let i = 0; i < totalSamples; i++) {
        // low crackle base noise
        let baseRumble = (Math.random() * 2 - 1) * 0.005;
        
        // Dynamic dust crackle pops spikes
        if (Math.random() < 0.00015) {
            const crackleDuration = Math.floor(Math.random() * 15) + 3;
            const popGain = Math.random() > 0.4 ? 0.35 : -0.35;
            for (let p = 0; p < crackleDuration && (i + p) < totalSamples; p++) {
                data[i + p] += popGain * (1 - p / crackleDuration);
            }
        }
        data[i] += baseRumble;
    }
    return buffer;
}

// Spacious exponential decaying white noise algorithm to generate natural Impulse Response
function generateReverbImpulse(ctx, duration, decay) {
    const sampleRate = ctx.sampleRate;
    const length = sampleRate * duration;
    const buffer = ctx.createBuffer(2, length, sampleRate);
    const left = buffer.getChannelData(0);
    const right = buffer.getChannelData(1);
    
    for (let i = 0; i < length; i++) {
        const progress = i / length;
        const multiplier = Math.pow(1 - progress, decay);
        left[i] = (Math.random() * 2 - 1) * multiplier;
        right[i] = (Math.random() * 2 - 1) * multiplier;
    }
    return buffer;
}

fileInput.addEventListener('change', handleFileSelection);

// Drag & Drop visual highlights
['dragenter', 'dragover'].forEach(eventName => {
    dropZone.addEventListener(eventName, (e) => {
        e.preventDefault();
        dropZone.classList.add('border-pink-500', 'bg-purple-950/40');
    }, false);
});
['dragleave', 'drop'].forEach(eventName => {
    dropZone.addEventListener(eventName, (e) => {
        e.preventDefault();
        dropZone.classList.remove('border-pink-500', 'bg-purple-950/40');
    }, false);
});
dropZone.addEventListener('drop', (e) => {
    const files = e.dataTransfer.files;
    if (files.length > 0) {
        fileInput.files = files;
        handleFileSelection();
    }
});

function handleFileSelection() {
    const file = fileInput.files[0];
    if (!file) return;

    initAudio();

    fileNameDisplay.textContent = file.name;
    cassetteTitle.textContent = file.name;
    
    // Reset play/pause parameters
    stopAudio();
    mainAudioBuffer = null;
    pausedAt = 0;
    isPlaying = false;
    
    btnPlayPause.disabled = true;
    btnStop.disabled = true;
    btnRecord.disabled = true;
    
    statusLabel.innerHTML = `<i class="fa-solid fa-spinner animate-spin mr-1"></i> Decoding...`;
    
    const fileReader = new FileReader();
    fileReader.onload = function(evt) {
        audioCtx.decodeAudioData(evt.target.result)
            .then(decodedBuffer => {
                mainAudioBuffer = decodedBuffer;
                songDuration = decodedBuffer.duration;
                totalTimeSpan.textContent = formatTime(songDuration);
                currTimeSpan.textContent = "00:00";
                progressFill.style.width = '0%';
                
                statusLabel.innerHTML = `<i class="fa-solid fa-check text-emerald-400 mr-1"></i> Lofi Ready`;
                btnPlayPause.disabled = false;
                btnStop.disabled = false;
                btnRecord.disabled = false;
            })
            .catch(err => {
                console.error("Audio Decode Error:", err);
                statusLabel.innerHTML = `<i class="fa-solid fa-triangle-exclamation text-red-500 mr-1"></i> Decode Failed`;
                fileNameDisplay.textContent = "Koshish karein doosri standard mp3 file ke sath.";
            });
    };
    fileReader.readAsArrayBuffer(file);
}

function playAudio() {
    if (!audioCtx || !mainAudioBuffer) return;
    
    // Resume audio context if asleep (Chrome/Safari policy)
    if (audioCtx.state === 'suspended') {
        audioCtx.resume();
    }

    // Stop current playbacks if any
    if (currentSongSourceNode) {
        try { currentSongSourceNode.stop(); } catch(e){}
    }

    // Initialize individual nodes in processing pipeline
    gainNode = audioCtx.createGain();
    filterNode = audioCtx.createBiquadFilter();
    convolverNode = audioCtx.createConvolver();
    dryReverbGain = audioCtx.createGain();
    wetReverbGain = audioCtx.createGain();

    // Setup Filter Type
    filterNode.type = 'lowpass';

    // Set static values inside the Impulse Response Convolution Reverb
    convolverNode.buffer = impulseResponseBuffer;

    /* Build & Link Audio Signal Flow/Graph:
       [Source] -> [GainNode] -> [Lowpass Filter] ---> (Dry Reverb Gain) ---\
                                                   ---> (Wet Reverb Node -> Wet Gain) ---> [MasterSumNode]
    */
    currentSongSourceNode = audioCtx.createBufferSource();
    currentSongSourceNode.buffer = mainAudioBuffer;

    currentSongSourceNode.connect(gainNode);
    gainNode.connect(filterNode);

    // Reverb split channels
    filterNode.connect(dryReverbGain);
    filterNode.connect(convolverNode);
    convolverNode.connect(wetReverbGain);

    dryReverbGain.connect(masterVolumeNode);
    wetReverbGain.connect(masterVolumeNode);

    /* Setup Pitch Wow/Flutter (Tape Vibrato Engine) via LFO on PlaybackRate */
    lfoNode = audioCtx.createOscillator();
    lfoGainNode = audioCtx.createGain();
    lfoNode.type = 'sine';
    lfoNode.frequency.value = 1.3; // 1.3 Hz slow wobble cycle speed
    
    lfoNode.connect(lfoGainNode);
    lfoGainNode.connect(currentSongSourceNode.playbackRate); // Modulate speed/vibrato dynamically!

    // Start Tape modulation LFO
    lfoNode.start();

    // Inject loopable crackle and rain synthesizers
    startAmbienceSinks();

    // Map user slider positions to parameters
    updateAudioParameters();

    // Playback logic from designated positions (accounting for custom speed/tempo)
    const currentSpeed = parseFloat(document.getElementById('param-speed').value) / 100;
    currentSongSourceNode.playbackRate.value = currentSpeed;
    
    // Start track playback
    startTime = audioCtx.currentTime - (pausedAt / currentSpeed);
    currentSongSourceNode.start(0, pausedAt);
    
    isPlaying = true;
    btnPlayText.textContent = "PAUSE MASTER";
    btnPlayPause.querySelector('i').className = "fa-solid fa-pause";
    
    // Visual indicators active
    statusLabel.innerHTML = `<i class="fa-solid fa-compact-disc text-pink-400 animate-spin mr-1"></i> Jamming...`;
    reelLeft.classList.add('spinning');
    reelRight.classList.add('spinning');

    // Interval timers for tracker update
    startPlaybackTimers();
}

function pauseAudio() {
    if (!isPlaying) return;
    
    const currentSpeed = parseFloat(document.getElementById('param-speed').value) / 100;
    pausedAt += (audioCtx.currentTime - startTime) * currentSpeed;
    
    if (currentSongSourceNode) {
        try { currentSongSourceNode.stop(); } catch(e){}
    }
    
    stopAmbienceSinks();
    
    isPlaying = false;
    btnPlayText.textContent = "PLAY LOFI";
    btnPlayPause.querySelector('i').className = "fa-solid fa-play";
    
    statusLabel.innerHTML = `<i class="fa-solid fa-circle-pause text-amber-400 mr-1"></i> Paused`;
    reelLeft.classList.remove('spinning');
    reelRight.classList.remove('spinning');
    
    clearInterval(playbackTimerInterval);
}

function stopAudio() {
    pauseAudio();
    pausedAt = 0;
    currTimeSpan.textContent = "00:00";
    progressFill.style.width = '0%';
}

function startAmbienceSinks() {
    if (!audioCtx) return;

    // 1. Rain Synthesizer Setup
    rainSourceNode = audioCtx.createBufferSource();
    rainSourceNode.buffer = rainBuffer;
    rainSourceNode.loop = true;
    rainGainNode = audioCtx.createGain();
    
    rainSourceNode.connect(rainGainNode);
    rainGainNode.connect(masterVolumeNode);
    rainSourceNode.start();

    // 2. Vinyl Crackle Setup
    crackleSourceNode = audioCtx.createBufferSource();
    crackleSourceNode.buffer = crackleBuffer;
    crackleSourceNode.loop = true;
    crackleGainNode = audioCtx.createGain();
    
    crackleSourceNode.connect(crackleGainNode);
    crackleGainNode.connect(masterVolumeNode);
    crackleSourceNode.start();
}

function stopAmbienceSinks() {
    if (rainSourceNode) {
        try { rainSourceNode.stop(); } catch(e){}
        rainSourceNode = null;
    }
    if (crackleSourceNode) {
        try { crackleSourceNode.stop(); } catch(e){}
        crackleSourceNode = null;
    }
}

function updateAudioParameters() {
    if (!audioCtx) return;

    // Tempo Speed Pitch adjustments (Lowering speed automatically offsets the absolute pitch down)
    const currentSpeed = parseFloat(document.getElementById('param-speed').value) / 100;
    document.getElementById('speed-val').textContent = Math.round(currentSpeed * 100) + "%";
    if (isPlaying && currentSongSourceNode) {
        currentSongSourceNode.playbackRate.value = currentSpeed;
    }

    // Lowpass muffle filter cutoff
    const filterFreq = parseFloat(document.getElementById('param-lowpass').value);
    document.getElementById('lowpass-val').textContent = filterFreq + " Hz";
    if (filterNode) {
        filterNode.frequency.setValueAtTime(filterFreq, audioCtx.currentTime);
    }

    // Ambient Rain Volume
    const rainVol = parseFloat(document.getElementById('param-rain').value) / 100;
    document.getElementById('rain-val').textContent = Math.round(rainVol * 100) + "%";
    if (rainGainNode) {
        // Adjust lower rain balance nicely
        rainGainNode.gain.setValueAtTime(rainVol * 0.15, audioCtx.currentTime);
    }

    // Vinyl Crackle Volume
    const crackleVol = parseFloat(document.getElementById('param-crackle').value) / 100;
    document.getElementById('crackle-val').textContent = Math.round(crackleVol * 100) + "%";
    if (crackleGainNode) {
        crackleGainNode.gain.setValueAtTime(crackleVol * 0.12, audioCtx.currentTime);
    }

    // Reverb Blend ratios
    const reverbMixVal = parseFloat(document.getElementById('param-reverb').value) / 100;
    document.getElementById('reverb-val').textContent = Math.round(reverbMixVal * 100) + "%";
    if (dryReverbGain && wetReverbGain) {
        // Equal-power crossfade style reverb blend
        dryReverbGain.gain.setValueAtTime(1 - (reverbMixVal * 0.5), audioCtx.currentTime);
        wetReverbGain.gain.setValueAtTime(reverbMixVal * 0.8, audioCtx.currentTime);
    }

    // Tape Flutter wobble intensity
    const flutterVal = parseFloat(document.getElementById('param-flutter').value) / 100;
    document.getElementById('flutter-val').textContent = Math.round(flutterVal * 100) + "%";
    if (lfoGainNode) {
        // Subtle modulation (range: 0 to 0.01)
        lfoGainNode.gain.setValueAtTime(flutterVal * 0.006, audioCtx.currentTime);
    }
}

// Bind active state updates to UI elements
const controllers = [
    'param-speed', 'param-lowpass', 'param-rain', 
    'param-crackle', 'param-reverb', 'param-flutter'
];
controllers.forEach(ctrlId => {
    document.getElementById(ctrlId).addEventListener('input', updateAudioParameters);
});

function startPlaybackTimers() {
    clearInterval(playbackTimerInterval);
    playbackTimerInterval = setInterval(() => {
        if (!isPlaying) return;
        
        const currentSpeed = parseFloat(document.getElementById('param-speed').value) / 100;
        const currentProgress = pausedAt + ((audioCtx.currentTime - startTime) * currentSpeed);
        
        if (currentProgress >= songDuration) {
            stopAudio();
            return;
        }

        currTimeSpan.textContent = formatTime(currentProgress);
        const percent = (currentProgress / songDuration) * 100;
        progressFill.style.width = percent + '%';
    }, 250);
}

// Allow user to click anywhere on tracker to skip
progressContainer.addEventListener('click', (evt) => {
    if (!mainAudioBuffer) return;
    const rect = progressContainer.getBoundingClientRect();
    const clickX = evt.clientX - rect.left;
    const percent = clickX / rect.width;
    const targetProgress = percent * songDuration;

    if (isPlaying) {
        pausedAt = targetProgress;
        playAudio(); // Restarts with updated pausedAt coordinate
    } else {
        pausedAt = targetProgress;
        currTimeSpan.textContent = formatTime(targetProgress);
        progressFill.style.width = (percent * 100) + '%';
    }
});

/* Utilities */
function formatTime(secs) {
    const min = Math.floor(secs / 60);
    const sec = Math.floor(secs % 60);
    return (min < 10 ? '0' : '') + min + ':' + (sec < 10 ? '0' : '') + sec;
}

btnPlayPause.addEventListener('click', () => {
    if (isPlaying) {
        pauseAudio();
    } else {
        playAudio();
    }
});

btnStop.addEventListener('click', stopAudio);

let drops = [];
function initRainDrops() {
    drops = [];
    for (let i = 0; i < 40; i++) {
        drops.push({
            x: Math.random() * canvas.width,
            y: Math.random() * canvas.height,
            length: Math.random() * 15 + 10,
            speed: Math.random() * 3 + 4,
            opacity: Math.random() * 0.3 + 0.1
        });
    }
}

// Draw visual animation loop
function drawVisualizer() {
    requestAnimationFrame(drawVisualizer);
    if (!canvasCtx) return;

    const width = canvas.width;
    const height = canvas.height;

    // Clear with slightly transparent blue space atmosphere
    canvasCtx.fillStyle = 'rgba(20, 10, 34, 0.2)';
    canvasCtx.fillRect(0, 0, width, height);

    // Initialize drops if window was resized
    if (drops.length === 0) initRainDrops();

    // 1. Draw sliding rain backdrop on the screen
    canvasCtx.strokeStyle = 'rgba(174, 207, 238, 0.4)';
    canvasCtx.lineWidth = 1;
    drops.forEach(drop => {
        canvasCtx.beginPath();
        canvasCtx.moveTo(drop.x, drop.y);
        canvasCtx.lineTo(drop.x - (drop.speed * 0.15), drop.y + drop.length);
        canvasCtx.strokeStyle = `rgba(180, 200, 255, ${drop.opacity})`;
        canvasCtx.stroke();

        // Increment drop positions
        drop.y += drop.speed;
        drop.x -= drop.speed * 0.1;

        if (drop.y > height) {
            drop.y = -drop.length;
            drop.x = Math.random() * width;
        }
    });

    // 2. Draw sound frequency wave
    if (analyserNode) {
        const bufferLength = analyserNode.frequencyBinCount;
        const dataArray = new Uint8Array(bufferLength);
        analyserNode.getByteFrequencyData(dataArray);

        // Sum amplitudes to get dynamic sound energy
        let amplitudeSum = 0;
        for (let j = 0; j < bufferLength; j++) {
            amplitudeSum += dataArray[j];
        }
        const averageAmp = amplitudeSum / bufferLength;

        // Draw cozy pulsing mountains/grids matching music energy beat
        canvasCtx.beginPath();
        canvasCtx.moveTo(0, height);
        
        const sliceWidth = width / (bufferLength / 2);
        let x = 0;

        for (let i = 0; i < bufferLength / 2; i++) {
            const ratio = dataArray[i] / 255;
            // Cozy sunset color gradient
            const waveY = height - (ratio * (height * 0.6)) - 10;
            
            canvasCtx.lineTo(x, waveY);
            x += sliceWidth;
        }

        canvasCtx.lineTo(width, height);
        
        // Soft glowing neon gradients for waves
        const sunsetGrad = canvasCtx.createLinearGradient(0, height * 0.4, 0, height);
        sunsetGrad.addColorStop(0, 'rgba(217, 56, 122, 0.45)');  // Pink Sunset
        sunsetGrad.addColorStop(0.5, 'rgba(255, 142, 60, 0.25)'); // Amber Orange
        sunsetGrad.addColorStop(1, 'rgba(31, 14, 60, 0.9)');       // Indigo base
        
        canvasCtx.fillStyle = sunsetGrad;
        canvasCtx.fill();
        
        canvasCtx.strokeStyle = 'rgba(217, 56, 122, 0.7)';
        canvasCtx.lineWidth = 2;
        canvasCtx.stroke();
    } else {
        // Flat cozy idle wave
        canvasCtx.beginPath();
        canvasCtx.moveTo(0, height - 15);
        canvasCtx.quadraticCurveTo(width / 2, height - 25, width, height - 15);
        canvasCtx.strokeStyle = 'rgba(150, 100, 200, 0.3)';
        canvasCtx.lineWidth = 1.5;
        canvasCtx.stroke();
    }
}

// Kick off custom canvas rendering loop on boot
drawVisualizer();

btnRecord.addEventListener('click', () => {
    if (isRecording) {
        stopRecording();
    } else {
        startRecording();
    }
});

function startRecording() {
    if (!audioCtx || !audioDestinationNode) return;
    
    // Auto-play from start if loaded
    if (!isPlaying) {
        pausedAt = 0; // Rewind song
        playAudio();
    }

    recordedChunks = [];
    
    // Set recording stream details
    const options = { mimeType: 'audio/webm;codecs=opus' };
    mediaRecorder = new MediaRecorder(audioDestinationNode.stream, options);
    
    mediaRecorder.ondataavailable = (event) => {
        if (event.data.size > 0) {
            recordedChunks.push(event.data);
        }
    };
    
    mediaRecorder.onstop = () => {
        const audioBlob = new Blob(recordedChunks, { type: 'audio/webm' });
        const audioUrl = URL.createObjectURL(audioBlob);
        
        // Show download/save CTA
        btnDownload.style.display = 'inline-flex';
        btnDownload.onclick = () => {
            const a = document.createElement('a');
            a.href = audioUrl;
            a.download = `lofiify-${Date.now()}.webm`;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
        };
    };

    mediaRecorder.start();
    isRecording = true;
    
    // Update visual layouts
    document.getElementById('recording-indicator').style.display = 'flex';
    btnRecordText.textContent = "STOP RECORDING";
    btnRecord.classList.remove('bg-purple-900/40', 'text-purple-300');
    btnRecord.classList.add('bg-red-500/20', 'text-red-400', 'border-red-500');
    
    btnDownload.style.display = 'none'; // Clear older files
}

function stopRecording() {
    if (!isRecording || !mediaRecorder) return;
    
    mediaRecorder.stop();
    isRecording = false;
    
    document.getElementById('recording-indicator').style.display = 'none';
    btnRecordText.textContent = "Record Remix";
    btnRecord.classList.add('bg-purple-900/40', 'text-purple-300');
    btnRecord.classList.remove('bg-red-500/20', 'text-red-400', 'border-red-500');
}
</script>
</body>
</html>
