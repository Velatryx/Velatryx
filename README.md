<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 200" width="100%" height="100%">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=VT323&amp;display=swap');
    
    .bg { fill: #000000; }
    
    .pixel-text {
      font-family: 'VT323', monospace;
      font-size: 110px;
      fill: #ffffff;
      letter-spacing: 6px;
      text-anchor: middle;
      dominant-baseline: middle;
    }

    /* Glitch/Drip Animation Simulation */
    .layer-base { animation: flicker 4s infinite; }
    
    @keyframes flicker {
      0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% { opacity: 1; filter: drop-shadow(0px 0px 1px rgba(255,255,255,0.3)); }
      20%, 24%, 55% { opacity: 0.8; filter: drop-shadow(0px 2px 4px rgba(255,255,255,0.1)); }
    }
  </style>

  <rect width="1000" height="200" class="bg" />

  <defs>
    <pattern id="pixelgrid" width="4" height="4" patternUnits="userSpaceOnUse">
      <line x1="0" y1="0" x2="4" y2="0" stroke="#000000" stroke-width="1.5" opacity="0.8" />
      <line x1="0" y1="0" x2="0" y2="4" stroke="#000000" stroke-width="1.5" opacity="0.8" />
    </pattern>
  </defs>

  <g class="layer-base">
    <text x="500" y="95" class="pixel-text">RED TEAMING / PENTESTING</text>
  </g>

  <rect width="1000" height="200" fill="url(#pixelgrid)" pointer-events="none" />
</svg>


###
<p align="center">
  <img src="./header.svg" alt="Red Teaming / Pentesting" width="100%">
</p>

<p align="center">
  <code>⛤ offensive packet manipulation ⛤</code>
  <br>
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png" width="100%">
</p>

<p align="center">
  <code>[ ⛤about ]</code> &nbsp;&nbsp;&nbsp;&nbsp;
  <code>[ ⛤arsenal ]</code> &nbsp;&nbsp;&nbsp;&nbsp;
  <code>[ ⛤exploits ]</code> &nbsp;&nbsp;&nbsp;&nbsp;
  <code>[ ⛤loot ]</code> &nbsp;&nbsp;&nbsp;&nbsp;
  <code>[ ⛤certifications ]</code>
</p>

<hr>

<table align="center" width="100%">
  <tr>
    <td bgcolor="#000000">
      <p align="center"><code>⛤ OFFENSIVE SECURITY RESEARCH ⛤</code></p>
      <br>
      <p>
        Execution of advanced adversarial simulations, vulnerability discovery, and low-level exploit development. Understanding the underlying mechanisms of system architecture — its faults, its structural defenses, its layout — is the fundamental prerequisite to complete system compromise.
      </p>
    </td>
  </tr>
</table>

<br>

## 📂 Current Operations & Tooling

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Velatryx&show_icons=true&theme=dark&hide_border=true&bg_color=000000&text_color=ffffff&icon_color=ffffff&title_color=ffffff" height="150px"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Velatryx&theme=dark&hide_border=true&background=000000&text=ffffff&ring=ffffff&fire=ffffff&currStreakNum=ffffff" height="150px"/>
</p>

### 🛠️ Core Arsenal
```text
[Memory Safety] -> C / C++ / Assembly (x86_64)
[Automation]    -> Python / Bash
[Environments]  -> Linux (Fedora / Kali)
[Focus Areas]   -> Binary Exploitation, Web Forensics, Process Injection, Evasion

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/accent.png" width="100%">




![](https://komarev.com/ghpvc/?username=Velatryx&abbreviated=true)
