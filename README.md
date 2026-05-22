<!-- ████████████████████████████████████████████████████████████ -->
<!-- ██          ADITYA MALLICK — GITHUB PROFILE README         ██ -->
<!-- ████████████████████████████████████████████████████████████ -->

<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    ANIMATED HEADER SVG                     -->
<!-- ═══════════════════════════════════════════════════════════ -->

<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020010;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#06001a;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#020010;stop-opacity:1"/>
    </linearGradient>

    <!-- Neon blue glow filter -->
    <filter id="neonBlue" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <!-- Neon cyan glow -->
    <filter id="neonCyan" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <!-- Strong glow for title -->
    <filter id="titleGlow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <!-- Grid line pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#0a0a2e" stroke-width="0.5"/>
    </pattern>

    <!-- Scanning gradient -->
    <linearGradient id="scanGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#00f5ff;stop-opacity:0.08"/>
      <stop offset="100%" style="stop-color:#00f5ff;stop-opacity:0"/>
    </linearGradient>

    <!-- Orbit gradient -->
    <linearGradient id="orbitGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7c3aed;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#7c3aed;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:0"/>
    </linearGradient>

    <!-- Corner bracket clip -->
    <clipPath id="mainClip">
      <rect x="0" y="0" width="900" height="280" rx="12"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="900" height="280" fill="url(#bgGrad)" rx="12"/>
  <rect width="900" height="280" fill="url(#grid)" rx="12" clip-path="url(#mainClip)"/>

  <!-- Animated scan line -->
  <rect x="0" y="0" width="900" height="60" fill="url(#scanGrad)" clip-path="url(#mainClip)">
    <animateTransform attributeName="transform" type="translate" from="0,0" to="0,280" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- Corner brackets — top left -->
  <path d="M20,45 L20,20 L55,20" fill="none" stroke="#00f5ff" stroke-width="2" opacity="0.8">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
  </path>
  <!-- top right -->
  <path d="M880,45 L880,20 L845,20" fill="none" stroke="#00f5ff" stroke-width="2" opacity="0.8">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" begin="0.5s" repeatCount="indefinite"/>
  </path>
  <!-- bottom left -->
  <path d="M20,235 L20,260 L55,260" fill="none" stroke="#7c3aed" stroke-width="2" opacity="0.8">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" begin="1s" repeatCount="indefinite"/>
  </path>
  <!-- bottom right -->
  <path d="M880,235 L880,260 L845,260" fill="none" stroke="#7c3aed" stroke-width="2" opacity="0.8">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" begin="1.5s" repeatCount="indefinite"/>
  </path>

  <!-- Orbit ring left -->
  <ellipse cx="120" cy="140" rx="70" ry="25" fill="none" stroke="url(#orbitGrad)" stroke-width="1" opacity="0.4">
    <animateTransform attributeName="transform" type="rotate" from="0 120 140" to="360 120 140" dur="8s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Orbit ring right -->
  <ellipse cx="780" cy="140" rx="70" ry="25" fill="none" stroke="url(#orbitGrad)" stroke-width="1" opacity="0.4">
    <animateTransform attributeName="transform" type="rotate" from="360 780 140" to="0 780 140" dur="8s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Floating particles -->
  <circle cx="60" cy="80" r="2" fill="#00f5ff" opacity="0.6">
    <animate attributeName="cy" values="80;60;80" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="840" cy="100" r="1.5" fill="#7c3aed" opacity="0.6">
    <animate attributeName="cy" values="100;80;100" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;1;0.2" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="230" r="1.5" fill="#06b6d4" opacity="0.5">
    <animate attributeName="cy" values="230;215;230" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="50" r="2" fill="#a855f7" opacity="0.5">
    <animate attributeName="cy" values="50;35;50" dur="5s" repeatCount="indefinite"/>
  </circle>

  <!-- SYS STATUS tag -->
  <rect x="360" y="20" width="180" height="22" rx="11" fill="none" stroke="#00f5ff" stroke-width="1" opacity="0.5"/>
  <text x="450" y="35" text-anchor="middle" font-family="monospace" font-size="9" fill="#00f5ff" opacity="0.8">⬡ SYS:ONLINE  ⬡ CGPA:9.20  ⬡</text>

  <!-- Main Title -->
  <text x="450" y="105" text-anchor="middle" font-family="'Courier New', monospace" font-size="52" font-weight="900"
    fill="#00f5ff" filter="url(#titleGlow)" letter-spacing="6">
    ADITYA
    <animate attributeName="opacity" values="0.85;1;0.85" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="160" text-anchor="middle" font-family="'Courier New', monospace" font-size="52" font-weight="900"
    fill="#a855f7" filter="url(#titleGlow)" letter-spacing="6">
    MALLICK
    <animate attributeName="opacity" values="1;0.85;1" dur="3s" begin="1.5s" repeatCount="indefinite"/>
  </text>

  <!-- Role text -->
  <text x="450" y="195" text-anchor="middle" font-family="monospace" font-size="13" fill="#94a3b8" letter-spacing="4">
    ⟨ AI ENGINEER · FULL STACK DEV · IOT ARCHITECT ⟩
  </text>

  <!-- Animated divider line -->
  <line x1="150" y1="210" x2="750" y2="210" stroke="#1e293b" stroke-width="1"/>
  <line x1="150" y1="210" x2="750" y2="210" stroke="url(#orbitGrad)" stroke-width="1.5">
    <animate attributeName="x1" values="150;750;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="750;150;750" dur="4s" repeatCount="indefinite"/>
  </line>

  <!-- Bottom info bar -->
  <text x="450" y="240" text-anchor="middle" font-family="monospace" font-size="10" fill="#475569" letter-spacing="2">
    SOA University · Bhubaneswar · India
  </text>

  <!-- ID tag bottom right -->
  <text x="875" y="270" text-anchor="end" font-family="monospace" font-size="8" fill="#1e3a5f">ID:AM-2026-CSE</text>
</svg>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               ANIMATED TYPING INTRO                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<br>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2800&pause=1000&color=00F5FF&center=true&vCenter=true&multiline=false&repeat=true&width=700&height=45&lines=🤖+Building+AI-powered+systems...;⚙️+Engineering+Spring+Boot+backends...;🦾+Automating+with+Raspberry+Pi+%2B+OpenCV...;🌐+Crafting+REST+APIs+%26+microservices...;🔬+Exploring+Computer+Vision+%26+ML...;🚀+Full+Stack+%2B+AI+Engineer+in+the+making...)](https://git.io/typing-svg)

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  QUICK STATS BADGES                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

![Profile Views](https://komarev.com/ghpvc/?username=AdityaMallick01&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS)
![GitHub followers](https://img.shields.io/github/followers/AdityaMallick01?style=for-the-badge&color=00f5ff&labelColor=020010&label=FOLLOWERS)
![CGPA](https://img.shields.io/badge/CGPA-9.20%2F10-00f5ff?style=for-the-badge&labelColor=020010)
![Year](https://img.shields.io/badge/YEAR-3rd%20BTech%20CSE-a855f7?style=for-the-badge&labelColor=020010)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  SYSTEM BOOT TERMINAL                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║           ⬡  A D I T Y A . O S  —  SYSTEM BOOT SEQUENCE  ⬡         ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  [■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■] 100%  INIT COMPLETE       ║
║                                                                      ║
║  > Loading Core Modules...                             [  OK  ]      ║
║  > Java Full Stack Engine         v3.0 ...             [  OK  ]      ║
║  > Python + AI/ML Runtime         v2.1 ...             [  OK  ]      ║
║  > Raspberry Pi GPIO Interface    v1.4 ...             [  OK  ]      ║
║  > OpenCV Computer Vision Core    v4.8 ...             [  OK  ]      ║
║  > Spring Boot Backend Server     v3.2 ...             [  OK  ]      ║
║  > MySQL Database Engine          v8.0 ...             [  OK  ]      ║
║  > REST API Gateway               v1.0 ...             [  OK  ]      ║
║  > Git Version Control            v2.4 ...             [  OK  ]      ║
║                                                                      ║
║  ✦ ADITYA.OS ONLINE  ✦ ALL SYSTEMS NOMINAL  ✦ READY TO BUILD ✦     ║
╚══════════════════════════════════════════════════════════════════════╝
```

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                       ABOUT ME                             -->
<!-- ═══════════════════════════════════════════════════════════ -->

<img align="right" width="300" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif" alt="coding gif"/>

### `> whoami`

```yaml
name        : Aditya Mallick
alias       : AdityaMallick01
location    : Bhubaneswar, Odisha, India 🇮🇳
university  : SOA University (B.Tech CSE)
cgpa        : 9.20 / 10.0
year        : Third Year (2023–Present)
focus       :
  - Java Full Stack Development
  - AI / Machine Learning
  - Computer Vision (OpenCV)
  - Embedded Systems & IoT
  - Raspberry Pi Robotics
  - REST API Architecture
goal        : Full Stack + AI Engineer
status      : 🟢 Open to Internships
```

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  TECH STACK DASHBOARD                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

## ⚡ TECH STACK MATRIX

<!-- Languages -->
### 〔 LANGUAGES 〕
![Java](https://img.shields.io/badge/Java-%23ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

### 〔 BACKEND & FRAMEWORKS 〕
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-005571?style=for-the-badge&logo=fastapi&logoColor=white)

### 〔 DATABASE 〕
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### 〔 AI / ML / COMPUTER VISION 〕
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![ML](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

### 〔 EMBEDDED / IOT 〕
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry-Pi&logoColor=white)
![GPIO](https://img.shields.io/badge/GPIO-Control-00f5ff?style=for-the-badge&labelColor=020010)
![PiCamera2](https://img.shields.io/badge/PiCamera2-A22846?style=for-the-badge&logo=Raspberry-Pi&logoColor=white)
![HX711](https://img.shields.io/badge/HX711-ADC-7c3aed?style=for-the-badge&labelColor=020010)
![PCA9685](https://img.shields.io/badge/PCA9685-I2C-a855f7?style=for-the-badge&labelColor=020010)

### 〔 TOOLS & PLATFORM 〕
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               SKILLS PROFICIENCY BARS (SVG)                -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

## 📊 SKILL PROFICIENCY MATRIX

<svg width="820" height="320" viewBox="0 0 820 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="barBlue" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7c3aed"/>
      <stop offset="100%" style="stop-color:#00f5ff"/>
    </linearGradient>
    <linearGradient id="barPurple" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#a855f7"/>
      <stop offset="100%" style="stop-color:#7c3aed"/>
    </linearGradient>
    <linearGradient id="barGreen" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#06b6d4"/>
      <stop offset="100%" style="stop-color:#a855f7"/>
    </linearGradient>
    <filter id="barGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="820" height="320" fill="#020010" rx="12"/>
  <rect width="820" height="320" fill="none" stroke="#1e293b" stroke-width="1" rx="12"/>

  <!-- Header -->
  <text x="410" y="30" text-anchor="middle" font-family="monospace" font-size="12" fill="#00f5ff" letter-spacing="4">⬡ CAPABILITY INDEX ⬡</text>
  <line x1="40" y1="42" x2="780" y2="42" stroke="#1e293b" stroke-width="1"/>

  <!-- Skill rows — col 1 -->
  <!-- Java -->
  <text x="50" y="72" font-family="monospace" font-size="11" fill="#94a3b8">Java</text>
  <rect x="160" y="60" width="280" height="14" rx="7" fill="#0f172a"/>
  <rect x="160" y="60" width="252" height="14" rx="7" fill="url(#barBlue)" filter="url(#barGlow)">
    <animate attributeName="width" from="0" to="252" dur="1.5s" fill="freeze"/>
  </rect>
  <text x="448" y="72" font-family="monospace" font-size="10" fill="#00f5ff">90%</text>

  <!-- Python -->
  <text x="50" y="107" font-family="monospace" font-size="11" fill="#94a3b8">Python</text>
  <rect x="160" y="95" width="280" height="14" rx="7" fill="#0f172a"/>
  <rect x="160" y="95" width="238" height="14" rx="7" fill="url(#barPurple)" filter="url(#barGlow)">
    <animate attributeName="width" from="0" to="238" dur="1.7s" fill="freeze"/>
  </rect>
  <text x="448" y="107" font-family="monospace" font-size="10" fill="#a855f7">85%</text>

  <!-- Spring Boot -->
  <text x="50" y="142" font-family="monospace" font-size="11" fill="#94a3b8">Spring Boot</text>
  <rect x="160" y="130" width="280" height="14" rx="7" fill="#0f172a"/>
  <rect x="160" y="130" width="224" height="14" rx="7" fill="url(#barBlue)" filter="url(#barGlow)">
    <animate attributeName="width" from="0" to="224" dur="1.9s" fill="freeze"/>
  </rect>
  <text x="448" y="142" font-family="monospace" font-size="10" fill="#00f5ff">80%</text>

  <!-- OpenCV -->
  <text x="50" y="177" font-family="monospace" font-size="11" fill="#94a3b8">OpenCV / CV</text>
  <rect x="160" y="165" width="280" height="14" rx="7" fill="#0f172a"/>
  <rect x="160" y="165" width="224" height="14" rx="7" fill="url(#barGreen)" filter="url(#barGlow)">
    <animate attributeName="width" from="0" to="224" dur="2s" fill="freeze"/>
  </rect>
  <text x="448" y="177" font-family="monospace" font-size="10" fill="#06b6d4">80%</text>

  <!-- Raspberry Pi -->
  <text x="50" y="212" font-family="monospace" font-size="11" fill="#94a3b8">Raspberry Pi</text>
  <rect x="160" y="200" width="280" height="14" rx="7" fill="#0f172a"/>
  <rect x="160" y="200" width="238" height="14" rx="7" fill="url(#barPurple)" filter="url(#barGlow)">
    <animate attributeName="width" from="0" to="238" dur="2.1s" fill="freeze"/>
  </rect>
  <text x="448" y="212" font-family="monospace" font-size="10" fill="#a855f7">85%</text>

  <!-- REST APIs -->
  <text x="50" y="247" font-family="monospace" font-size="11" fill="#94a3b8">REST APIs</text>
  <rect x="160" y="235" width="280" height="14" rx="7" fill="#0f172a"/>
  <rect x="160" y="235" width="238" height="14" rx="7" fill="url(#barBlue)" filter="url(#barGlow)">
    <animate attributeName="width" from="0" to="238" dur="2.2s" fill="freeze"/>
  </rect>
  <text x="448" y="247" font-family="monospace" font-size="10" fill="#00f5ff">85%</text>

  <!-- MySQL -->
  <text x="50" y="282" font-family="monospace" font-size="11" fill="#94a3b8">MySQL / JPA</text>
  <rect x="160" y="270" width="280" height="14" rx="7" fill="#0f172a"/>
  <rect x="160" y="270" width="210" height="14" rx="7" fill="url(#barGreen)" filter="url(#barGlow)">
    <animate attributeName="width" from="0" to="210" dur="2.3s" fill="freeze"/>
  </rect>
  <text x="448" y="282" font-family="monospace" font-size="10" fill="#06b6d4">75%</text>

  <!-- Divider -->
  <line x1="490" y1="50" x2="490" y2="300" stroke="#1e293b" stroke-width="1"/>

  <!-- Right column — radial skills -->
  <text x="640" y="72" text-anchor="middle" font-family="monospace" font-size="10" fill="#475569">DOMAIN COVERAGE</text>

  <!-- Hexagonal stat circles -->
  <!-- Backend -->
  <circle cx="560" cy="150" r="45" fill="none" stroke="#1e293b" stroke-width="2"/>
  <circle cx="560" cy="150" r="45" fill="none" stroke="url(#barBlue)" stroke-width="3" stroke-dasharray="254 30" stroke-dashoffset="0">
    <animate attributeName="stroke-dashoffset" from="283" to="28" dur="2s" fill="freeze"/>
  </circle>
  <text x="560" y="145" text-anchor="middle" font-family="monospace" font-size="11" fill="#00f5ff">Backend</text>
  <text x="560" y="162" text-anchor="middle" font-family="monospace" font-size="14" font-weight="bold" fill="#00f5ff">90%</text>

  <!-- AI/ML -->
  <circle cx="660" cy="150" r="45" fill="none" stroke="#1e293b" stroke-width="2"/>
  <circle cx="660" cy="150" r="45" fill="none" stroke="url(#barPurple)" stroke-width="3" stroke-dasharray="226 57" stroke-dashoffset="0">
    <animate attributeName="stroke-dashoffset" from="283" to="57" dur="2.2s" fill="freeze"/>
  </circle>
  <text x="660" y="145" text-anchor="middle" font-family="monospace" font-size="11" fill="#a855f7">AI / ML</text>
  <text x="660" y="162" text-anchor="middle" font-family="monospace" font-size="14" font-weight="bold" fill="#a855f7">80%</text>

  <!-- IoT -->
  <circle cx="760" cy="150" r="45" fill="none" stroke="#1e293b" stroke-width="2"/>
  <circle cx="760" cy="150" r="45" fill="none" stroke="url(#barGreen)" stroke-width="3" stroke-dasharray="240 43" stroke-dashoffset="0">
    <animate attributeName="stroke-dashoffset" from="283" to="43" dur="2.4s" fill="freeze"/>
  </circle>
  <text x="760" y="145" text-anchor="middle" font-family="monospace" font-size="11" fill="#06b6d4">IoT</text>
  <text x="760" y="162" text-anchor="middle" font-family="monospace" font-size="14" font-weight="bold" fill="#06b6d4">85%</text>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               FEATURED PROJECTS SHOWCASE                   -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

## 🚀 MISSION CONTROL — FEATURED PROJECTS

</div>

---

### 🤖 PROJECT ALPHA — Intelligent Object Sorting System

<div align="center">

> **`[CLASSIFICATION: COMPUTER VISION + EMBEDDED SYSTEMS]`**

</div>

```
╔═══════════════════════════════════════════════════════════════╗
║  INTELLIGENT OBJECT SORTING SYSTEM                           ║
║  ─────────────────────────────────────────────────────────  ║
║  STATUS: [■■■■■■■■■■] OPERATIONAL                           ║
║                                                              ║
║  SUBSYSTEMS:                                                 ║
║  ├─ 📷 PiCamera2     → Real-time object capture             ║
║  ├─ 🧠 OpenCV        → Shape detection + classification      ║
║  ├─ ⚖️  HX711 (ADC)  → 24-bit weight sensing                 ║
║  ├─ 🦾 PCA9685 (I2C) → 6-DOF robotic arm control            ║
║  └─ 🍓 Raspberry Pi  → Central control unit                  ║
║                                                              ║
║  TECH: Python · OpenCV · PiCamera2 · GPIO · NumPy           ║
╚═══════════════════════════════════════════════════════════════╝
```

**Key Engineering Achievements:**
- 🔬 Dual-parameter sorting: **shape + weight** classification simultaneously
- 📡 Real-time image processing pipeline with sub-second latency
- ⚙️ Calibrated load cell with 24-bit ADC for precision weight sensing
- 🦾 Automated 6-DOF pick-and-place robotic arm via I²C protocol

[![View Project](https://img.shields.io/badge/View%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AdityaMallick01)

---

### 🤖 PROJECT BETA — Web-Controlled Surveillance Robot

<div align="center">

> **`[CLASSIFICATION: IoT + FLASK BACKEND + LIVE STREAMING]`**

</div>

```
╔═══════════════════════════════════════════════════════════════╗
║  WEB-CONTROLLED SURVEILLANCE ROBOT                           ║
║  ─────────────────────────────────────────────────────────  ║
║  STATUS: [■■■■■■■■■■] LIVE STREAMING                        ║
║                                                              ║
║  ARCHITECTURE:                                               ║
║  ├─ 🌐 Flask Backend  → Web server + streaming endpoint      ║
║  ├─ 📹 OpenCV         → Video capture + MJPEG stream         ║
║  ├─ 🕹️  GPIO Control  → Motor driver (L298N)                ║
║  ├─ 📡 Wi-Fi          → Remote navigation interface          ║
║  └─ 🍓 Raspberry Pi   → Full system orchestration            ║
║                                                              ║
║  TECH: Python · Flask · OpenCV · GPIO · HTML/CSS/JS         ║
╚═══════════════════════════════════════════════════════════════╝
```

**Key Engineering Achievements:**
- 📺 Live **MJPEG video streaming** over local network
- 🌐 Custom Flask web interface for real-time robot control
- 🔄 Bidirectional motor control with direction switching
- 🛡️ Stable remote navigation under network conditions

[![View Project](https://img.shields.io/badge/View%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AdityaMallick01)

---

### ⚡ PROJECT GAMMA — Student Management REST API

<div align="center">

> **`[CLASSIFICATION: JAVA FULL STACK · SPRING BOOT · MYSQL]`**

</div>

```
╔═══════════════════════════════════════════════════════════════╗
║  STUDENT MANAGEMENT REST API                                 ║
║  ─────────────────────────────────────────────────────────  ║
║  STATUS: [■■■■■■■■■■] API ENDPOINTS LIVE                    ║
║                                                              ║
║  ARCHITECTURE:                                               ║
║  ├─ 🟢 Spring Boot  → Application framework + DI            ║
║  ├─ 📊 Spring JPA   → ORM + Many-to-Many relationships      ║
║  ├─ 🗄️  MySQL        → Relational data persistence           ║
║  ├─ 🔄 DTO Pattern  → Clean API response separation          ║
║  └─ 📄 REST CRUD    → Full resource lifecycle management     ║
║                                                              ║
║  TECH: Java · Spring Boot · MySQL · JPA · REST API          ║
╚═══════════════════════════════════════════════════════════════╝
```

**Key Engineering Achievements:**
- 🔗 Many-to-Many student-course relationship with join table
- 📑 Full **CRUD + pagination + search** implementation
- 🏗️ Clean DTO pattern separating entity from API layer
- 🔒 Data exposure prevention via response projection

[![View Project](https://img.shields.io/badge/View%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AdityaMallick01)

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               GITHUB STATS DASHBOARD                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

## 📈 GITHUB ANALYTICS HUB

<img height="180" src="https://github-readme-stats.vercel.app/api?username=AdityaMallick01&show_icons=true&theme=tokyonight&hide_border=true&bg_color=020010&title_color=00f5ff&icon_color=a855f7&text_color=94a3b8&border_radius=12&include_all_commits=true&count_private=true" alt="GitHub Stats"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdityaMallick01&layout=compact&theme=tokyonight&hide_border=true&bg_color=020010&title_color=00f5ff&text_color=94a3b8&border_radius=12&langs_count=8" alt="Top Languages"/>

<br/><br/>

<img width="700" src="https://github-readme-streak-stats.herokuapp.com/?user=AdityaMallick01&theme=tokyonight&hide_border=true&background=020010&ring=00f5ff&fire=a855f7&currStreakLabel=00f5ff&sideLabels=94a3b8&border_radius=12" alt="GitHub Streak"/>

<br/><br/>

<!-- Contribution Graph -->
<img width="700" src="https://github-readme-activity-graph.vercel.app/graph?username=AdityaMallick01&bg_color=020010&color=00f5ff&line=7c3aed&point=a855f7&area=true&hide_border=true" alt="Activity Graph"/>

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               LEARNING JOURNEY PATHS                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

## 🧠 DUAL JOURNEY PROGRESS

</div>

<table>
<tr>
<td width="50%" valign="top">

### ☕ Java Full Stack Path

```
JAVA FOUNDATION
├── ✅ Core Java (OOP, Collections)
├── ✅ JDBC & SQL Fundamentals
├── ✅ Spring Boot Framework
├── ✅ Spring Data JPA & Hibernate
├── ✅ REST API Design & CRUD
├── ✅ DTO Pattern & Relationships
├── 🔄 Spring Security (JWT)
├── 🔄 Microservices Architecture
└── 📌 React.js Frontend Integration
```

</td>
<td width="50%" valign="top">

### 🤖 AI / ML + CV Path

```
AI FOUNDATION
├── ✅ Python for ML (NumPy, etc.)
├── ✅ OpenCV (Image Processing)
├── ✅ PiCamera2 + Video Pipelines
├── ✅ Object Detection (Shape/Color)
├── ✅ Weight Sensing + Sensor Fusion
├── 🔄 Supervised ML (Coursera)
├── 🔄 Deep Learning Basics (CNNs)
├── 🔄 YOLO / Real-time Detection
└── 📌 LLMs & Agentic AI Systems
```

</td>
</tr>
</table>

**Legend:** `✅ Completed` · `🔄 In Progress` · `📌 Coming Next`

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               CERTIFICATIONS & ACHIEVEMENTS                -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

## 🏆 ACHIEVEMENTS & CERTIFICATIONS

</div>

<div align="center">

| 🏅 Achievement | 📋 Details | 🗓️ Year |
|:---:|:---:|:---:|
| ☁️ Oracle Cloud AI Foundations | OCI 2025 Associate Certified | 2025 |
| 🤖 Supervised Machine Learning | Stanford + DeepLearning.AI | 2024 |
| ☕ Core Java Training | Lakshya Institute of Technology | 2024 |
| 🎨 Adobe India Hackathon | Qualified Round 1 | 2025 |
| ☁️ Google Cloud Agentic AI Day | Participated in Hackathon | 2025 |
| 📚 SOA University CGPA | 9.20 / 10.0 | Ongoing |

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--            CURRENTLY BUILDING / LEARNING                   -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

## 🛰️ CURRENT MISSION LOG

</div>

```python
class AdityaMallick:
    def __init__(self):
        self.name       = "Aditya Mallick"
        self.university = "SOA University, Bhubaneswar"
        self.cgpa       = 9.20

    @property
    def currently_building(self):
        return [
            "Spring Boot microservices with Spring Security + JWT",
            "Deep Learning models for real-time object detection (YOLO)",
            "AI-integrated REST APIs using Python + Java backend",
            "Advanced IoT automation with sensor fusion",
        ]

    @property
    def currently_learning(self):
        return [
            "React.js for Full Stack frontend integration",
            "Docker & Kubernetes for containerized deployments",
            "LLM APIs & Agentic AI workflows",
            "Advanced Computer Vision (CNNs, YOLO, SAM)",
        ]

    @property
    def open_to(self):
        return ["Internships", "Open Source Contributions", "Collaborations"]

    def __repr__(self):
        return "Building the future, one commit at a time. 🚀"

aditya = AdityaMallick()
print(aditya)
# → Building the future, one commit at a time. 🚀
```

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  CONNECT / CONTACT                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

## 🌐 ESTABLISH CONNECTION

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adityamallick01)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AdityaMallick01)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adityamallick002@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-00f5ff?style=for-the-badge&logo=vercel&logoColor=black)](https://github.com/AdityaMallick01)

<br>

> 💬 *"I'm always open to exciting projects, internship opportunities, and open-source collaborations. Let's build something remarkable together."*

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  FUTURISTIC FOOTER SVG                     -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="900" height="80" viewBox="0 0 900 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7c3aed;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#7c3aed;stop-opacity:1"/>
      <stop offset="70%" style="stop-color:#00f5ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#00f5ff;stop-opacity:0"/>
    </linearGradient>
    <filter id="footerGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="900" height="80" fill="#020010" rx="12"/>

  <!-- Animated top line -->
  <line x1="0" y1="2" x2="900" y2="2" stroke="url(#footerGrad)" stroke-width="2" filter="url(#footerGlow)">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </line>

  <!-- Footer text -->
  <text x="450" y="32" text-anchor="middle" font-family="monospace" font-size="11" fill="#475569" letter-spacing="3">
    ⟨ ADITYA.OS v2026.1 — FULL STACK + AI ENGINEER IN TRAINING ⟩
  </text>
  <text x="450" y="52" text-anchor="middle" font-family="monospace" font-size="10" fill="#334155" letter-spacing="2">
    SOA University · Bhubaneswar, India
  </text>
  <text x="450" y="70" text-anchor="middle" font-family="monospace" font-size="9" fill="#1e293b" letter-spacing="1">
    Built with 💙 by Aditya Mallick · github.com/AdityaMallick01
  </text>
</svg>

<br>

![Wave](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=80&section=footer&animation=twinkling)

</div>

<!-- ████████████████████████████████████████████████████████████ -->
<!--               END OF ADITYA MALLICK README                  -->
<!-- ████████████████████████████████████████████████████████████ -->
