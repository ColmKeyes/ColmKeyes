# COLM KEYES

**// EARTH OBSERVATION × FOREST INTELLIGENCE**

<br>

Building AI systems that monitor forests from space. I work at the intersection of satellite remote sensing, foundation models, and agentic AI — turning radar signals and spectral data into tools that help protect and understand the world's forests.

<br>

---

<br>

## 📡 SAR & InSAR Remote Sensing

Working with **Synthetic Aperture Radar** for all-weather, day-night forest monitoring. I build coherence-based pipelines for change detection, biomass estimation, and forest structure analysis using interferometric techniques. Tracking the next generation of L-band and P-band missions — **NISAR** and **BIOMASS** — that will transform how we measure forests from space.

<p align="center">
<svg viewBox="0 0 400 200" width="400" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="wave-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7ee787;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#7ee787;stop-opacity:0.2"/>
    </linearGradient>
    <linearGradient id="return-grad" x1="100%" y1="0%" x2="0%" y2="0%">
      <stop offset="0%" style="stop-color:#58a6ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#58a6ff;stop-opacity:0.2"/>
    </linearGradient>
    <pattern id="grid-pattern" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#21262d" stroke-width="0.5"/>
    </pattern>
  </defs>
  
  <rect width="400" height="200" fill="#0d1117"/>
  <rect width="400" height="200" fill="url(#grid-pattern)" opacity="0.5"/>
  
  <!-- Satellite -->
  <rect x="25" y="40" width="45" height="35" rx="4" fill="#161b22" stroke="#58a6ff" stroke-width="2"/>
  <rect x="8" y="48" width="20" height="18" fill="#1a3a5c" stroke="#58a6ff" stroke-width="1"/>
  <line x1="12" y1="48" x2="12" y2="66" stroke="#58a6ff" stroke-width="0.5" opacity="0.5"/>
  <line x1="18" y1="48" x2="18" y2="66" stroke="#58a6ff" stroke-width="0.5" opacity="0.5"/>
  <line x1="24" y1="48" x2="24" y2="66" stroke="#58a6ff" stroke-width="0.5" opacity="0.5"/>
  <rect x="67" y="48" width="20" height="18" fill="#1a3a5c" stroke="#58a6ff" stroke-width="1"/>
  <line x1="71" y1="48" x2="71" y2="66" stroke="#58a6ff" stroke-width="0.5" opacity="0.5"/>
  <line x1="77" y1="48" x2="77" y2="66" stroke="#58a6ff" stroke-width="0.5" opacity="0.5"/>
  <line x1="83" y1="48" x2="83" y2="66" stroke="#58a6ff" stroke-width="0.5" opacity="0.5"/>
  <rect x="35" y="28" width="25" height="14" rx="2" fill="#30363d" stroke="#58a6ff" stroke-width="1"/>
  <circle cx="47" cy="57" r="5" fill="#7ee787">
    <animate attributeName="opacity" values="1;0.3;1" dur="1.2s" repeatCount="indefinite"/>
  </circle>
  <text x="47" y="95" text-anchor="middle" fill="#58a6ff" font-family="monospace" font-size="9">SAR</text>
  
  <!-- Circular polarized wave hitting forest -->
  <path d="M90,55 Q110,45 130,60 Q150,75 170,85 Q190,95 210,110 Q230,125 250,135 Q270,145 285,150" 
        fill="none" stroke="#7ee787" stroke-width="2" opacity="0.8">
    <animate attributeName="stroke-dasharray" values="0,350;220,130" dur="2.2s" repeatCount="indefinite"/>
  </path>
  <path d="M90,65 Q110,55 130,70 Q150,85 170,95 Q190,105 210,120 Q230,135 250,145 Q270,155 285,160" 
        fill="none" stroke="#58a6ff" stroke-width="1.5" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,350;220,130" dur="2.2s" begin="0.1s" repeatCount="indefinite"/>
  </path>
  
  <!-- Polarization indicators -->
  <ellipse cx="140" cy="72" rx="5" ry="9" fill="none" stroke="#7ee787" stroke-width="1" opacity="0.4" transform="rotate(35 140 72)">
    <animate attributeName="opacity" values="0.5;0.15;0.5" dur="1s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="190" cy="100" rx="5" ry="9" fill="none" stroke="#7ee787" stroke-width="1" opacity="0.4" transform="rotate(40 190 100)">
    <animate attributeName="opacity" values="0.5;0.15;0.5" dur="1s" begin="0.3s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="240" cy="130" rx="5" ry="9" fill="none" stroke="#7ee787" stroke-width="1" opacity="0.4" transform="rotate(45 240 130)">
    <animate attributeName="opacity" values="0.5;0.15;0.5" dur="1s" begin="0.6s" repeatCount="indefinite"/>
  </ellipse>
  
  <text x="130" y="38" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="7">VV + VH</text>
  
  <!-- Forest canopy -->
  <line x1="250" y1="180" x2="385" y2="180" stroke="#30363d" stroke-width="1"/>
  <path d="M275,180 L275,145 M262,153 Q275,130 288,153 M255,167 Q275,135 295,167" 
        fill="none" stroke="#238636" stroke-width="2.5" stroke-linecap="round"/>
  <path d="M315,180 L315,135 M299,145 Q315,117 331,145 M290,163 Q315,123 340,163" 
        fill="none" stroke="#2ea043" stroke-width="2.5" stroke-linecap="round"/>
  <path d="M355,180 L355,150 M345,157 Q355,143 365,157 M340,170 Q355,147 370,170" 
        fill="none" stroke="#238636" stroke-width="2.5" stroke-linecap="round"/>
  <path d="M295,180 L295,160 M287,165 Q295,155 303,165" 
        fill="none" stroke="#196c2e" stroke-width="1.5" stroke-linecap="round" opacity="0.6"/>
  <path d="M335,180 L335,163 M329,167 Q335,160 341,167" 
        fill="none" stroke="#196c2e" stroke-width="1.5" stroke-linecap="round" opacity="0.6"/>
  
  <!-- Canopy interaction -->
  <circle cx="300" cy="145" r="18" fill="none" stroke="#7ee787" stroke-width="1" stroke-dasharray="4,3" opacity="0.5">
    <animate attributeName="r" values="15;22;15" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.2;0.5" dur="2s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Return backscatter -->
  <path d="M290,145 Q220,100 95,58" fill="none" stroke="#58a6ff" stroke-width="1.5" opacity="0.7">
    <animate attributeName="stroke-dasharray" values="0,280;220,60" dur="2.5s" begin="1.1s" repeatCount="indefinite"/>
  </path>
  <path d="M310,140 Q230,95 95,52" fill="none" stroke="#58a6ff" stroke-width="1" opacity="0.5">
    <animate attributeName="stroke-dasharray" values="0,280;220,60" dur="2.5s" begin="1.3s" repeatCount="indefinite"/>
  </path>
  
  <text x="315" y="195" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="8">forest canopy</text>
  
  <!-- Info box -->
  <rect x="10" y="130" width="75" height="55" rx="3" fill="#161b22" stroke="#30363d" opacity="0.9"/>
  <text x="47" y="145" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="6">INTERFEROMETRY</text>
  <text x="47" y="160" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="7">γ coherence</text>
  <text x="47" y="175" text-anchor="middle" fill="#58a6ff" font-family="monospace" font-size="7">Δφ phase</text>
</svg>
</p>

<br>

---

<br>

## 🧠 Foundation Models for Earth Observation

Leveraging **pre-trained vision transformers** for forest analysis tasks. These models learn rich representations from massive EO datasets, enabling few-shot transfer to specific applications like disturbance detection, species classification, and change mapping. Working with embedding-based approaches for unsupervised forest zone classification and semantic segmentation.

<p align="center">
<svg viewBox="0 0 420 200" width="420" height="200" xmlns="http://www.w3.org/2000/svg">
  <rect width="420" height="200" fill="#0d1117"/>
  
  <!-- Source imagery -->
  <rect x="15" y="30" width="120" height="120" fill="#0d1117" stroke="#30363d" stroke-width="1"/>
  <rect x="16" y="31" width="59" height="59" fill="#238636" opacity="0.65"/>
  <rect x="76" y="31" width="58" height="59" fill="#2ea043" opacity="0.75"/>
  <rect x="16" y="91" width="59" height="58" fill="#2ea043" opacity="0.55"/>
  <rect x="76" y="91" width="58" height="58" fill="#7c4a1a" opacity="0.45"/>
  
  <!-- Canopy texture -->
  <circle cx="35" cy="50" r="15" fill="#2ea043" opacity="0.4"/>
  <circle cx="55" cy="65" r="10" fill="#238636" opacity="0.35"/>
  <circle cx="100" cy="48" r="18" fill="#238636" opacity="0.5"/>
  <circle cx="115" cy="70" r="12" fill="#2ea043" opacity="0.35"/>
  <circle cx="35" cy="105" r="16" fill="#238636" opacity="0.45"/>
  <circle cx="60" cy="120" r="12" fill="#2ea043" opacity="0.35"/>
  <rect x="80" y="95" width="50" height="50" fill="#5c3d1a" opacity="0.25"/>
  
  <!-- Grid -->
  <line x1="75" y1="30" x2="75" y2="150" stroke="#30363d" stroke-width="1"/>
  <line x1="15" y1="90" x2="135" y2="90" stroke="#30363d" stroke-width="1"/>
  
  <!-- Scanning highlight -->
  <rect x="15" y="30" width="60" height="60" fill="none" stroke="#7ee787" stroke-width="2.5">
    <animate attributeName="x" values="15;75;75;15;15" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="y" values="30;30;90;90;30" dur="5s" repeatCount="indefinite"/>
  </rect>
  
  <text x="75" y="165" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="8">satellite imagery</text>
  
  <!-- Arrow -->
  <path d="M145,90 L175,90" stroke="#58a6ff" stroke-width="2"/>
  <path d="M170,85 L180,90 L170,95" fill="none" stroke="#58a6ff" stroke-width="2"/>
  <text x="162" y="80" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="6">tokenize</text>
  
  <!-- Token sequence -->
  <rect x="190" y="25" width="100" height="130" rx="4" fill="#161b22" stroke="#30363d"/>
  <text x="240" y="18" text-anchor="middle" fill="#a371f7" font-family="monospace" font-size="7">PATCH TOKENS</text>
  
  <!-- Tokens -->
  <rect x="200" y="35" width="35" height="25" rx="3" fill="#238636" opacity="0.5" stroke="#7ee787" stroke-width="1.5">
    <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="5s" repeatCount="indefinite"/>
  </rect>
  <text x="217" y="51" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="7">t₁</text>
  <text x="217" y="72" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="5">dense</text>
  
  <rect x="245" y="35" width="35" height="25" rx="3" fill="#2ea043" opacity="0.5" stroke="#7ee787" stroke-width="1.5">
    <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="5s" begin="1.25s" repeatCount="indefinite"/>
  </rect>
  <text x="262" y="51" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="7">t₂</text>
  <text x="262" y="72" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="5">healthy</text>
  
  <rect x="200" y="82" width="35" height="25" rx="3" fill="#2ea043" opacity="0.4" stroke="#7ee787" stroke-width="1.5">
    <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="5s" begin="2.5s" repeatCount="indefinite"/>
  </rect>
  <text x="217" y="98" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="7">t₃</text>
  <text x="217" y="119" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="5">mixed</text>
  
  <rect x="245" y="82" width="35" height="25" rx="3" fill="#f0883e" opacity="0.4" stroke="#f0883e" stroke-width="1.5">
    <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="5s" begin="3.75s" repeatCount="indefinite"/>
  </rect>
  <text x="262" y="98" text-anchor="middle" fill="#f0883e" font-family="monospace" font-size="7">t₄</text>
  <text x="262" y="119" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="5">disturbed</text>
  
  <!-- Positional encoding -->
  <rect x="200" y="130" width="80" height="16" rx="2" fill="#0d1117" stroke="#58a6ff" stroke-width="1"/>
  <text x="240" y="141" text-anchor="middle" fill="#58a6ff" font-family="monospace" font-size="6">+ pos encoding</text>
  
  <!-- Arrow to embedding -->
  <path d="M300,90 L325,90" stroke="#a371f7" stroke-width="2"/>
  <path d="M320,85 L330,90 L320,95" fill="none" stroke="#a371f7" stroke-width="2"/>
  
  <!-- Embedding output -->
  <rect x="340" y="35" width="65" height="110" rx="4" fill="#161b22" stroke="#a371f7" stroke-width="1.5"/>
  <text x="372" y="28" text-anchor="middle" fill="#a371f7" font-family="monospace" font-size="7">EMBEDDING</text>
  
  <rect x="350" y="45" width="45" height="8" rx="2" fill="#7ee787" opacity="0.6"/>
  <rect x="350" y="57" width="35" height="8" rx="2" fill="#58a6ff" opacity="0.5"/>
  <rect x="350" y="69" width="42" height="8" rx="2" fill="#a371f7" opacity="0.5"/>
  <rect x="350" y="81" width="28" height="8" rx="2" fill="#f0883e" opacity="0.4"/>
  <rect x="350" y="93" width="38" height="8" rx="2" fill="#7ee787" opacity="0.4"/>
  <rect x="350" y="105" width="32" height="8" rx="2" fill="#58a6ff" opacity="0.35"/>
  
  <text x="372" y="128" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="6">768-dim</text>
  
  <text x="210" y="185" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="7">imagery → tokens → embeddings → downstream tasks</text>
</svg>
</p>

<br>

---

<br>

## 🤖 Agentic AI Systems

Building **autonomous AI agents** that orchestrate Earth observation workflows. These systems combine conversational interfaces with tool-use capabilities — coordinating satellite data retrieval, model inference, and analysis pipelines through natural language. The goal: make forest monitoring accessible without requiring users to write code or understand complex data formats.

<p align="center">
<svg viewBox="0 0 850 110" width="100%" height="110" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="flow-gradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#58a6ff;stop-opacity:0.15"/>
      <stop offset="50%" style="stop-color:#7ee787;stop-opacity:0.1"/>
      <stop offset="100%" style="stop-color:#f0883e;stop-opacity:0.15"/>
    </linearGradient>
  </defs>
  
  <rect width="850" height="110" fill="#0d1117"/>
  <rect x="0" y="45" width="850" height="20" fill="url(#flow-gradient)" opacity="0.4"/>
  
  <!-- SAR Data -->
  <rect x="30" y="32" width="30" height="24" rx="3" fill="#161b22" stroke="#58a6ff" stroke-width="1.5"/>
  <rect x="20" y="38" width="12" height="12" fill="#1a3a5c" stroke="#58a6ff" stroke-width="0.5"/>
  <rect x="58" y="38" width="12" height="12" fill="#1a3a5c" stroke="#58a6ff" stroke-width="0.5"/>
  <circle cx="45" cy="44" r="3" fill="#7ee787">
    <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  
  <path d="M72,48 Q100,40 128,55 Q145,65 158,72" fill="none" stroke="#7ee787" stroke-width="1.5" opacity="0.7">
    <animate attributeName="stroke-dasharray" values="0,120;90,30" dur="2s" repeatCount="indefinite"/>
  </path>
  
  <path d="M160,78 L160,60 M152,65 Q160,52 168,65 M148,75 Q160,55 172,75" fill="none" stroke="#238636" stroke-width="2" stroke-linecap="round"/>
  <path d="M180,78 L180,65 M174,69 Q180,61 186,69" fill="none" stroke="#2ea043" stroke-width="1.5" stroke-linecap="round"/>
  
  <text x="45" y="92" text-anchor="middle" fill="#58a6ff" font-family="monospace" font-size="8">SAR DATA</text>
  
  <!-- Flow 1 -->
  <path d="M200,55 L235,55" stroke="#30363d" stroke-width="1.5"/>
  <circle cx="217" cy="55" r="2" fill="#58a6ff">
    <animate attributeName="cx" values="205;230;205" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Encoder -->
  <rect x="250" y="38" width="14" height="14" fill="#238636" opacity="0.5" stroke="#30363d" stroke-width="0.5"/>
  <rect x="266" y="38" width="14" height="14" fill="#2ea043" opacity="0.6" stroke="#30363d" stroke-width="0.5"/>
  <rect x="250" y="54" width="14" height="14" fill="#238636" opacity="0.4" stroke="#30363d" stroke-width="0.5"/>
  <rect x="266" y="54" width="14" height="14" fill="#7c4a1a" opacity="0.4" stroke="#30363d" stroke-width="0.5"/>
  
  <rect x="295" y="35" width="22" height="40" rx="2" fill="#161b22" stroke="#a371f7" stroke-width="1.5">
    <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="1.8s" repeatCount="indefinite"/>
  </rect>
  <text x="306" y="58" text-anchor="middle" fill="#a371f7" font-family="monospace" font-size="7">E</text>
  
  <rect x="323" y="35" width="22" height="40" rx="2" fill="#161b22" stroke="#a371f7" stroke-width="1.5">
    <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="1.8s" begin="0.3s" repeatCount="indefinite"/>
  </rect>
  <text x="334" y="58" text-anchor="middle" fill="#a371f7" font-family="monospace" font-size="7">N</text>
  
  <rect x="351" y="35" width="22" height="40" rx="2" fill="#161b22" stroke="#a371f7" stroke-width="1.5">
    <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="1.8s" begin="0.6s" repeatCount="indefinite"/>
  </rect>
  <text x="362" y="58" text-anchor="middle" fill="#a371f7" font-family="monospace" font-size="7">C</text>
  
  <circle cx="395" cy="55" r="14" fill="#161b22" stroke="#f0883e" stroke-width="1.5">
    <animate attributeName="r" values="14;16;14" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <text x="395" y="59" text-anchor="middle" fill="#f0883e" font-family="monospace" font-size="7">E</text>
  
  <text x="325" y="92" text-anchor="middle" fill="#a371f7" font-family="monospace" font-size="8">ENCODER</text>
  
  <!-- Flow 2 -->
  <path d="M415,55 L455,55" stroke="#30363d" stroke-width="1.5"/>
  <circle cx="435" cy="55" r="2" fill="#a371f7">
    <animate attributeName="cx" values="420;450;420" dur="1.5s" begin="0.3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Agent -->
  <rect x="465" y="28" width="75" height="54" rx="5" fill="#161b22" stroke="#7ee787" stroke-width="2">
    <animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </rect>
  <text x="502" y="50" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="10">AGENT</text>
  <text x="502" y="65" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="6">orchestrator</text>
  
  <!-- Tool indicators -->
  <circle cx="550" cy="35" r="6" fill="#161b22" stroke="#58a6ff" stroke-width="1">
    <animate attributeName="stroke-opacity" values="0.3;1;0.3" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="550" cy="55" r="6" fill="#161b22" stroke="#a371f7" stroke-width="1">
    <animate attributeName="stroke-opacity" values="0.3;1;0.3" dur="1.5s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="550" cy="75" r="6" fill="#161b22" stroke="#f0883e" stroke-width="1">
    <animate attributeName="stroke-opacity" values="0.3;1;0.3" dur="1.5s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  
  <line x1="542" y1="42" x2="544" y2="38" stroke="#30363d" stroke-width="1" stroke-dasharray="2,2">
    <animate attributeName="stroke-dashoffset" values="8;0" dur="0.8s" repeatCount="indefinite"/>
  </line>
  <line x1="542" y1="55" x2="544" y2="55" stroke="#30363d" stroke-width="1" stroke-dasharray="2,2">
    <animate attributeName="stroke-dashoffset" values="8;0" dur="0.8s" begin="0.2s" repeatCount="indefinite"/>
  </line>
  <line x1="542" y1="68" x2="544" y2="72" stroke="#30363d" stroke-width="1" stroke-dasharray="2,2">
    <animate attributeName="stroke-dashoffset" values="8;0" dur="0.8s" begin="0.4s" repeatCount="indefinite"/>
  </line>
  
  <text x="502" y="100" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="8">AGENTIC AI</text>
  
  <!-- Flow 3 -->
  <path d="M575,55 L615,55" stroke="#30363d" stroke-width="1.5"/>
  <circle cx="595" cy="55" r="2" fill="#7ee787">
    <animate attributeName="cx" values="580;610;580" dur="1.5s" begin="0.6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Output -->
  <rect x="625" y="20" width="120" height="70" rx="5" fill="#161b22" stroke="#30363d" stroke-width="1"/>
  
  <rect x="633" y="28" width="80" height="14" rx="3" fill="#1a3a5c"/>
  <text x="673" y="38" text-anchor="middle" fill="#58a6ff" font-family="monospace" font-size="6">analyze sector 7</text>
  
  <rect x="648" y="46" width="90" height="14" rx="3" fill="#1a3020"/>
  <text x="693" y="56" text-anchor="middle" fill="#7ee787" font-family="monospace" font-size="6">⚠ 3.2ha disturbed</text>
  
  <rect x="633" y="66" width="40" height="18" rx="2" fill="#0d1117" stroke="#30363d"/>
  <path d="M643,75 L643,72 M648,78 L648,70 M653,76 L653,73 M658,79 L658,71 M663,75 L663,74" stroke="#238636" stroke-width="2" stroke-linecap="round" opacity="0.6"/>
  
  <circle cx="705" cy="75" r="8" fill="#238636" opacity="0.4" stroke="#7ee787">
    <animate attributeName="opacity" values="0.3;0.6;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="725" cy="75" r="8" fill="#f0883e" opacity="0.4" stroke="#f0883e">
    <animate attributeName="opacity" values="0.3;0.6;0.3" dur="2s" begin="0.5s" repeatCount="indefinite"/>
  </circle>
  
  <text x="685" y="105" text-anchor="middle" fill="#f0883e" font-family="monospace" font-size="8">FOREST INTEL</text>
  
  <!-- End dots -->
  <circle cx="775" cy="55" r="4" fill="#238636">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="793" cy="55" r="3" fill="#7ee787">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="807" cy="55" r="2" fill="#58a6ff">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
</svg>
</p>

<br>

---

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/colm-keyes-4960a5132/">LinkedIn</a> · Dublin, Ireland
</p>
