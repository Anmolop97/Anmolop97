<svg width="1200" height="420" viewBox="0 0 1200 420" fill="none" xmlns="http://www.w3.org/2000/svg">
  <style>
    .bg { fill: #05070d; }
    .grid { stroke: #132033; stroke-width: 1; opacity: .55; }
    .cyan { fill: #00e5ff; }
    .white { fill: #f5f7ff; }
    .muted { fill: #7d8da8; }
    .green { fill: #39ff88; }
    .line { stroke: #00e5ff; stroke-width: 2; opacity: .75; }
    .glow { filter: drop-shadow(0 0 10px #00e5ff); }
    .scan { animation: scan 3s linear infinite; }
    .blink { animation: blink 1s steps(2) infinite; }
    .float { animation: float 4s ease-in-out infinite; }
    .pulse { animation: pulse 2s ease-in-out infinite; }

    @keyframes scan {
      from { transform: translateY(-120px); }
      to { transform: translateY(420px); }
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
    @keyframes float {
      50% { transform: translateY(-10px); }
    }
    @keyframes pulse {
      50% { opacity: .35; }
    }

    text {
      font-family: JetBrains Mono, Consolas, monospace;
    }
  </style>

  <rect class="bg" width="1200" height="420"/>

  <g opacity=".55">
    <path class="grid" d="M0 60H1200M0 120H1200M0 180H1200M0 240H1200M0 300H1200M0 360H1200"/>
    <path class="grid" d="M80 0V420M160 0V420M240 0V420M320 0V420M400 0V420M480 0V420M560 0V420M640 0V420M720 0V420M800 0V420M880 0V420M960 0V420M1040 0V420M1120 0V420"/>
  </g>

  <rect x="70" y="55" width="1060" height="310" rx="22" fill="#0b1020" stroke="#1d3557"/>
  <rect x="70" y="55" width="1060" height="48" rx="22" fill="#101827"/>
  <circle cx="105" cy="79" r="7" fill="#ff5f57"/>
  <circle cx="130" cy="79" r="7" fill="#ffbd2e"/>
  <circle cx="155" cy="79" r="7" fill="#28c840"/>

  <text x="95" y="150" class="muted" font-size="18">$ whoami</text>
  <text x="95" y="205" class="white glow" font-size="54" font-weight="800">ANMOL KUMAR</text>
  <text x="95" y="248" class="cyan" font-size="22">B.Tech CSE Student · Web Dev · Debugging Reality</text>
  <text x="95" y="295" class="muted" font-size="18">build → break → debug → understand</text>
  <rect class="blink" x="565" y="276" width="12" height="24" fill="#00e5ff"/>

  <g class="float">
    <rect x="760" y="135" width="285" height="150" rx="16" fill="#05070d" stroke="#00e5ff" opacity=".95"/>
    <text x="790" y="175" class="green" font-size="17">const mission = {</text>
    <text x="815" y="210" class="white" font-size="16">learn: "deeply",</text>
    <text x="815" y="240" class="white" font-size="16">build: "clean UI",</text>
    <text x="815" y="270" class="white" font-size="16">copyPaste: false</text>
    <text x="790" y="300" class="green" font-size="17">}</text>
  </g>

  <line class="scan" x1="70" y1="0" x2="1130" y2="0" stroke="#00e5ff" stroke-width="3" opacity=".35"/>
  <circle class="pulse glow" cx="1090" cy="332" r="10" fill="#00e5ff"/>
</svg>
