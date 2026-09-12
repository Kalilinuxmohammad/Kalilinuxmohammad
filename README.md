<!-- ╔══════════════════════════════════════════════════════════════╗
     ║              M A  //  CYBERNETIC IDENTITY                 ║
     ║                 Mohammad Amin — GitHub                    ║
     ╚══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<!-- ========================================================= -->

<!--                    ANIMATED MA CORE                       -->

<!-- ========================================================= -->

<svg width="100%" height="420" viewBox="0 0 1200 420"
  xmlns="http://www.w3.org/2000/svg"
  role="img"
  aria-label="Mohammad Amin MA Cybernetic Identity">

  <defs>

```
<linearGradient id="maGradient" x1="0%" y1="0%" x2="100%" y2="100%">
  <stop offset="0%" stop-color="#00ff9d"/>
  <stop offset="45%" stop-color="#00eaff"/>
  <stop offset="100%" stop-color="#00ff9d"/>
</linearGradient>

<radialGradient id="coreGlow">
  <stop offset="0%" stop-color="#00ff9d" stop-opacity="0.85"/>
  <stop offset="35%" stop-color="#00eaff" stop-opacity="0.35"/>
  <stop offset="100%" stop-color="#00110c" stop-opacity="0"/>
</radialGradient>

<filter id="glow">
  <feGaussianBlur stdDeviation="5" result="blur"/>
  <feMerge>
    <feMergeNode in="blur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>

<filter id="softGlow">
  <feGaussianBlur stdDeviation="12"/>
</filter>

<pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
  <path d="M40 0H0V40"
        fill="none"
        stroke="#00ff9d"
        stroke-opacity="0.08"/>
</pattern>
```

  </defs>

  <!-- Background -->

  <rect width="1200" height="420" fill="#050807" rx="24"/>
  <rect width="1200" height="420" fill="url(#grid)" rx="24"/>

  <!-- Ambient glow -->

<circle cx="600" cy="205" r="170"
       fill="url(#coreGlow)"
       filter="url(#softGlow)"> <animate attributeName="r"
          values="150;185;150"
          dur="4s"
          repeatCount="indefinite"/> </circle>

  <!-- Outer rotating orbit -->

<ellipse cx="600" cy="205"
        rx="260" ry="125"
        fill="none"
        stroke="#00ff9d"
        stroke-opacity="0.18"
        stroke-width="1"
        stroke-dasharray="5 12"> <animateTransform
   attributeName="transform"
   type="rotate"
   from="0 600 205"
   to="360 600 205"
   dur="18s"
   repeatCount="indefinite"/> </ellipse>

  <!-- Second orbit -->

<ellipse cx="600" cy="205"
        rx="215" ry="165"
        fill="none"
        stroke="#00eaff"
        stroke-opacity="0.12"
        stroke-width="1"
        stroke-dasharray="2 16"> <animateTransform
   attributeName="transform"
   type="rotate"
   from="360 600 205"
   to="0 600 205"
   dur="13s"
   repeatCount="indefinite"/> </ellipse>

  <!-- Orbit nodes -->

<circle cx="860" cy="205" r="5"
       fill="#00ff9d"
       filter="url(#glow)"> <animateTransform
   attributeName="transform"
   type="rotate"
   from="0 600 205"
   to="360 600 205"
   dur="18s"
   repeatCount="indefinite"/> </circle>

<circle cx="600" cy="40" r="4"
       fill="#00eaff"
       filter="url(#glow)"> <animateTransform
   attributeName="transform"
   type="rotate"
   from="360 600 205"
   to="0 600 205"
   dur="13s"
   repeatCount="indefinite"/> </circle>

  <!-- Circuit branches -->

<g stroke="#00ff9d" stroke-width="2" fill="none"
  stroke-linecap="round">

```
<path d="M430 150H330V115H260"/>
<path d="M770 150H870V115H940"/>

<path d="M430 260H330V295H260"/>
<path d="M770 260H870V295H940"/>

<circle cx="260" cy="115" r="5" fill="#00ff9d"/>
<circle cx="940" cy="115" r="5" fill="#00ff9d"/>
<circle cx="260" cy="295" r="5" fill="#00ff9d"/>
<circle cx="940" cy="295" r="5" fill="#00ff9d"/>
```

  </g>

  <!-- Animated data pulses -->

  <g fill="#00ff9d">
    <circle r="4">
      <animateMotion
        dur="2.5s"
        repeatCount="indefinite"
        path="M430 150H330V115H260"/>
    </circle>

```
<circle r="4">
  <animateMotion
    dur="2.8s"
    repeatCount="indefinite"
    path="M770 260H870V295H940"/>
</circle>
```

  </g>

  <!-- MA CORE -->

<circle cx="600" cy="205" r="108"
       fill="#07110d"
       stroke="#00ff9d"
       stroke-width="2"
       filter="url(#glow)"> <animate attributeName="stroke-opacity"
          values="0.45;1;0.45"
          dur="2.4s"
          repeatCount="indefinite"/> </circle>

<circle cx="600" cy="205" r="88"
       fill="none"
       stroke="#00eaff"
       stroke-opacity="0.35"
       stroke-width="1"
       stroke-dasharray="4 8"> <animateTransform
   attributeName="transform"
   type="rotate"
   from="0 600 205"
   to="360 600 205"
   dur="8s"
   repeatCount="indefinite"/> </circle>

  <!-- MA -->

<text x="600" y="222"
     text-anchor="middle"
     font-family="Arial, Helvetica, sans-serif"
     font-size="82"
     font-weight="900"
     letter-spacing="-8"
     fill="url(#maGradient)"
     filter="url(#glow)">
MA <animate attributeName="opacity"
          values="0.75;1;0.75"
          dur="2.2s"
          repeatCount="indefinite"/> </text>

  <!-- Core label -->

<text x="600" y="255"
     text-anchor="middle"
     fill="#8affd1"
     font-family="monospace"
     font-size="11"
     letter-spacing="4">
MA // CORE </text>

  <!-- Side modules -->

<g font-family="monospace"
  font-size="13"
  letter-spacing="2"
  fill="#8affd1">

```
<text x="180" y="108">SECURITY</text>
<text x="885" y="108">NETWORK</text>

<text x="190" y="315">LINUX</text>
<text x="895" y="315">CTF</text>
```

  </g>

  <!-- Scan line -->

<rect x="120" y="40"
     width="960"
     height="2"
     fill="#00ff9d"
     opacity="0.35"> <animate attributeName="y"
          values="40;378;40"
          dur="5s"
          repeatCount="indefinite"/> </rect>

  <!-- Top identity -->

<text x="600" y="28"
     text-anchor="middle"
     fill="#5affbd"
     font-family="monospace"
     font-size="11"
     letter-spacing="5">
CYBERNETIC IDENTITY // ONLINE </text>

</svg>

<br>

# `MOHAMMAD AMIN`

### `CYBERSECURITY STUDENT` · `LINUX` · `NETWORKING` · `CTF`

<br>

[![Profile](https://img.shields.io/badge/PROFILE-KALILINUXMOHAMMAD-050807?style=for-the-badge\&logo=github\&logoColor=00ff9d\&labelColor=050807\&color=00ff9d)](https://github.com/Kalilinuxmohammad)
[![Website](https://img.shields.io/badge/WEBSITE-ONLINE-050807?style=for-the-badge\&logo=googlechrome\&logoColor=00eaff\&labelColor=050807\&color=00eaff)](https://kalilinuxmohammad.github.io/)
[![Cybersecurity](https://img.shields.io/badge/FOCUS-CYBERSECURITY-050807?style=for-the-badge\&logo=hackthebox\&logoColor=00ff9d\&labelColor=050807\&color=00ff9d)](#)

</div>

---

## `01 // SYSTEM IDENTITY`

```text
┌──────────────────────────────────────────────────────────────┐
│                    MOHAMMAD AMIN                             │
├──────────────────────────────────────────────────────────────┤
│ ROLE        :: Cybersecurity Student                         │
│ FOCUS       :: Linux / Networking / Security / CTF           │
│ ENVIRONMENT :: Linux                                          │
│ MODE        :: Learn → Build → Break → Analyze → Improve     │
│ STATUS      :: ONLINE                                         │
└──────────────────────────────────────────────────────────────┘
```

> I build my cybersecurity foundation from the ground up —
> understanding systems, networks, Linux environments and security concepts through hands-on practice.

---

## `02 // CYBER CORE`

<div align="center">

```text
                    ┌─────────────────┐
                    │   MA // CORE    │
                    │   CYBER NODE    │
                    └────────┬────────┘
                             │
          ┌──────────────────┼──────────────────┐
          │                  │                  │
          ▼                  ▼                  ▼
     ┌──────────┐       ┌──────────┐       ┌──────────┐
     │ SECURITY │       │  LINUX   │       │ NETWORK  │
     └──────────┘       └──────────┘       └──────────┘
          │                  │                  │
          └──────────────────┼──────────────────┘
                             │
                             ▼
                       ┌──────────┐
                       │   CTF    │
                       └──────────┘
```

</div>

### `SECURITY ENGINE`

* Cybersecurity fundamentals
* Security concepts
* Reconnaissance concepts
* Web security fundamentals
* Vulnerability analysis
* Defensive thinking
* Security experimentation in controlled environments

### `LINUX CORE`

* Linux command line
* Filesystem architecture
* Permissions
* Processes
* Networking tools
* Shell workflows
* System administration fundamentals

### `NETWORK CORE`

* TCP/IP
* OSI model
* IPv4 / IPv6 fundamentals
* Ports & protocols
* DNS
* DHCP
* Routing
* Switching concepts
* Packet analysis

### `CTF MODE`

* Enumeration
* Recon
* Web challenges
* Linux challenges
* Network challenges
* Logic & problem solving
* Learning through controlled labs

---

## `03 // CYBER ARSENAL`

<div align="center">

| DOMAIN     | TECHNOLOGIES / CONCEPTS                       |
| :--------- | :-------------------------------------------- |
| `OS`       | Linux · Kali Linux                            |
| `NETWORK`  | TCP/IP · DNS · DHCP · Routing · Switching     |
| `SECURITY` | Web Security · Recon · Enumeration · Analysis |
| `CTF`      | Linux · Web · Network · Logic                 |
| `TOOLS`    | Nmap · Wireshark · Git · Bash                 |
| `DEV`      | Python · HTML · CSS                           |
| `WORKFLOW` | Terminal · GitHub · CLI                       |

</div>

---

## `04 // TOOLCHAIN`

<div align="center">

![Linux](https://img.shields.io/badge/LINUX-111111?style=for-the-badge\&logo=linux\&logoColor=00ff9d)
![Kali Linux](https://img.shields.io/badge/KALI_LINUX-111111?style=for-the-badge\&logo=kalilinux\&logoColor=00eaff)
![Python](https://img.shields.io/badge/PYTHON-111111?style=for-the-badge\&logo=python\&logoColor=00ff9d)
![Bash](https://img.shields.io/badge/BASH-111111?style=for-the-badge\&logo=gnubash\&logoColor=00eaff)
![Git](https://img.shields.io/badge/GIT-111111?style=for-the-badge\&logo=git\&logoColor=00ff9d)
![GitHub](https://img.shields.io/badge/GITHUB-111111?style=for-the-badge\&logo=github\&logoColor=ffffff)
![Wireshark](https://img.shields.io/badge/WIRESHARK-111111?style=for-the-badge\&logo=wireshark\&logoColor=00eaff)
![Nmap](https://img.shields.io/badge/NMAP-111111?style=for-the-badge\&logoColor=00ff9d)

</div>

---

## `05 // OPERATIONS`

### `OP-01` — WEB PRESENCE

**Repository:** `kalilinuxmohammad.github.io`

Personal web presence and experimental frontend work.

**Stack**

```text
HTML
CSS
Web Design
GitHub Pages
```

---

### `OP-02` — PROFILE CORE

**Repository:** `Kalilinuxmohammad`

The central GitHub profile and identity layer.

```text
STATUS  :: ACTIVE
NODE    :: GITHUB
OWNER   :: MOHAMMAD AMIN
```

---

## `06 // GITHUB TELEMETRY`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Kalilinuxmohammad&show_icons=true&hide_border=true&bg_color=050807&title_color=00ff9d&text_color=8affd1&icon_color=00eaff&ring_color=00ff9d" width="49%"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Kalilinuxmohammad&hide_border=true&background=050807&ring=00ff9d&fire=00eaff&currStreakLabel=00ff9d&sideLabels=8affd1&currStreakNum=ffffff&sideNums=ffffff&dates=5c756b" width="49%"/>

</div>

<br>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Kalilinuxmohammad&bg_color=050807&color=00ff9d&line=00ff9d&point=00eaff&area=true&hide_border=true" width="96%"/>

</div>

---

## `07 // CURRENT DIRECTIVE`

```text
[01] Strengthen Linux fundamentals
[02] Master networking concepts
[03] Build cybersecurity foundations
[04] Practice through controlled labs
[05] Improve Python & automation
[06] Solve more CTF challenges
[07] Build real projects
[08] Document the journey
```

---

## `08 // LEARNING NODE`

<div align="center">

```text
╔══════════════════════════════════════════════╗
║              EDUCATION NODE                  ║
╠══════════════════════════════════════════════╣
║                                              ║
║              RAVIN ACADEMY                   ║
║                                              ║
║     Cybersecurity / Networking Education     ║
║                                              ║
╚══════════════════════════════════════════════╝
```

**Educational affiliation — not a personal brand.**

</div>

---

## `09 // OPERATING PHILOSOPHY`

```text
┌─────────────────────────────────────────────────────────┐
│                                                         │
│  LEARN THE SYSTEM                                       │
│       ↓                                                 │
│  UNDERSTAND THE NETWORK                                 │
│       ↓                                                 │
│  BUILD THE ENVIRONMENT                                  │
│       ↓                                                 │
│  TEST THE ASSUMPTIONS                                   │
│       ↓                                                 │
│  ANALYZE THE RESULT                                     │
│       ↓                                                 │
│  IMPROVE THE SYSTEM                                     │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

> **Don't just use the tools. Understand what happens underneath them.**

---

## `10 // ROADMAP`

```text
CYBERSECURITY
│
├── Linux
│   ├── CLI
│   ├── Permissions
│   ├── Processes
│   └── Administration
│
├── Networking
│   ├── TCP/IP
│   ├── DNS
│   ├── Routing
│   └── Packet Analysis
│
├── Security
│   ├── Recon
│   ├── Enumeration
│   ├── Web Security
│   └── Vulnerability Analysis
│
├── CTF
│   ├── Web
│   ├── Linux
│   ├── Network
│   └── Logic
│
└── Development
    ├── Python
    ├── Bash
    ├── Automation
    └── Security Tools
```

---

<div align="center">

<!-- ========================================================= -->

<!--                    FINAL MA CORE                           -->

<!-- ========================================================= -->

<svg width="320" height="180" viewBox="0 0 320 180"
  xmlns="http://www.w3.org/2000/svg">

  <defs>

```
<linearGradient id="footerMA" x1="0%" y1="0%" x2="100%" y2="100%">
  <stop offset="0%" stop-color="#00ff9d"/>
  <stop offset="50%" stop-color="#00eaff"/>
  <stop offset="100%" stop-color="#00ff9d"/>
</linearGradient>

<filter id="footerGlow">
  <feGaussianBlur stdDeviation="4" result="blur"/>
  <feMerge>
    <feMergeNode in="blur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>
```

  </defs>

<circle cx="160" cy="82" r="58"
       fill="#06100c"
       stroke="#00ff9d"
       stroke-width="2"
       filter="url(#footerGlow)"> <animate attributeName="r"
          values="52;62;52"
          dur="3s"
          repeatCount="indefinite"/> </circle>

<circle cx="160" cy="82" r="45"
       fill="none"
       stroke="#00eaff"
       stroke-opacity="0.4"
       stroke-dasharray="3 7"> <animateTransform
   attributeName="transform"
   type="rotate"
   from="0 160 82"
   to="360 160 82"
   dur="6s"
   repeatCount="indefinite"/> </circle>

<text x="160" y="96"
     text-anchor="middle"
     font-family="Arial, Helvetica, sans-serif"
     font-size="48"
     font-weight="900"
     letter-spacing="-5"
     fill="url(#footerMA)"
     filter="url(#footerGlow)">
MA </text>

<text x="160" y="150"
     text-anchor="middle"
     font-family="monospace"
     font-size="10"
     letter-spacing="3"
     fill="#8affd1">
CONNECTION ESTABLISHED </text>

</svg>

### `NODE: MOHAMMAD-AMIN`

`STATUS :: ONLINE`   `MODE :: LEARNING`   `SIGNAL :: ACTIVE`

<br>

[![GitHub](https://img.shields.io/badge/GITHUB-Kalilinuxmohammad-050807?style=for-the-badge\&logo=github\&logoColor=00ff9d)](https://github.com/Kalilinuxmohammad)

</div>

<!--
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MA // CYBERNETIC IDENTITY
Mohammad Amin
Cybersecurity Student | Linux | Networking | CTF
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
-->
