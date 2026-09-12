<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1600 650">

<defs>

<linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
<stop stop-color="#020305"/>
<stop offset=".5" stop-color="#06110e"/>
<stop offset="1" stop-color="#010202"/>
</linearGradient>

<radialGradient id="glow">
<stop stop-color="#00ffb3" stop-opacity=".36"/>
<stop offset=".55" stop-color="#00ffb3" stop-opacity=".05"/>
<stop offset="1" stop-color="#00ffb3" stop-opacity="0"/>
</radialGradient>

<linearGradient id="electric">
<stop stop-color="#00ffb3"/>
<stop offset=".55" stop-color="#62ffe5"/>
<stop offset="1" stop-color="#54ddff"/>
</linearGradient>

<pattern id="grid"
 width="40"
 height="40"
 patternUnits="userSpaceOnUse">

<path
 d="M40 0H0V40"
 fill="none"
 stroke="#8affdf"
 stroke-opacity=".045"/>

</pattern>

<filter id="blur">
<feGaussianBlur stdDeviation="15"/>
</filter>

</defs>

<rect
 width="1600"
 height="650"
 rx="32"
 fill="url(#bg)"/>

<rect
 x="18"
 y="18"
 width="1564"
 height="614"
 rx="26"
 fill="url(#grid)"
 stroke="#8affdf"
 stroke-opacity=".13"/>

<circle
 cx="800"
 cy="320"
 r="320"
 fill="url(#glow)"
 filter="url(#blur)"/>

<!-- CORE RINGS -->

<g
 fill="none"
 stroke="url(#electric)">

<circle
 cx="800"
 cy="320"
 r="230"
 stroke-opacity=".12"/>

<circle
 cx="800"
 cy="320"
 r="185"
 stroke-opacity=".2"/>

<circle
 cx="800"
 cy="320"
 r="140"
 stroke-opacity=".32"/>

<circle
 cx="800"
 cy="320"
 r="100"
 stroke-opacity=".5"/>

<circle
 cx="800"
 cy="320"
 r="260"
 stroke-opacity=".28"
 stroke-dasharray="3 16">

<animateTransform
 attributeName="transform"
 type="rotate"
 from="0 800 320"
 to="360 800 320"
 dur="28s"
 repeatCount="indefinite"/>

</circle>

<path
 d="M700 320H470V210H180
 M900 320h230V210h210
 M800 220V135
 M800 420v90"
 stroke-opacity=".55"/>

</g>

<!-- NODES -->

<g fill="#00ffb3">

<circle cx="180" cy="210" r="5"/>
<circle cx="1420" cy="210" r="5"/>
<circle cx="800" cy="135" r="5"/>
<circle cx="800" cy="510" r="5"/>

</g>

<!-- HEADER -->

<g font-family="monospace">

<text
 x="70"
 y="78"
 fill="#00ffb3"
 font-size="13"
 letter-spacing="5">
MA // CYBER IDENTITY
</text>

<text
 x="1530"
 y="78"
 text-anchor="end"
 fill="#718d85"
 font-size="11"
 letter-spacing="3">
NODE 0001 / ONLINE
</text>

<text
 x="1530"
 y="104"
 text-anchor="end"
 fill="#00ffb3"
 font-size="11">
● SIGNAL STABLE
</text>

</g>

<!-- LEFT -->

<g font-family="monospace">

<text
 x="120"
 y="198"
 fill="#00ffb3"
 font-size="12"
 letter-spacing="4">
SECURITY
</text>

<text
 x="120"
 y="223"
 fill="#67847c"
 font-size="10">
WEB / RECON / LABS
</text>

<text
 x="120"
 y="390"
 fill="#00ffb3"
 font-size="12"
 letter-spacing="4">
LINUX
</text>

<text
 x="120"
 y="415"
 fill="#67847c"
 font-size="10">
KALI / BASH / CLI
</text>

</g>

<!-- RIGHT -->

<g font-family="monospace">

<text
 x="1480"
 y="198"
 text-anchor="end"
 fill="#00ffb3"
 font-size="12"
 letter-spacing="4">
NETWORK
</text>

<text
 x="1480"
 y="223"
 text-anchor="end"
 fill="#67847c"
 font-size="10">
TCP/IP / CISCO / TRAFFIC
</text>

<text
 x="1480"
 y="390"
 text-anchor="end"
 fill="#00ffb3"
 font-size="12"
 letter-spacing="4">
CTF
</text>

<text
 x="1480"
 y="415"
 text-anchor="end"
 fill="#67847c"
 font-size="10">
ENUMERATION / ANALYSIS
</text>

</g>

<!-- CENTRAL CORE -->

<circle
 cx="800"
 cy="320"
 r="82"
 fill="#010504"
 stroke="url(#electric)"
 stroke-width="2"/>

<circle
 cx="800"
 cy="320"
 r="67"
 fill="none"
 stroke="#00ffb3"
 stroke-opacity=".25"
 stroke-dasharray="3 9">

<animateTransform
 attributeName="transform"
 type="rotate"
 from="0 800 320"
 to="360 800 320"
 dur="10s"
 repeatCount="indefinite"/>

</circle>

<g
 font-family="monospace"
 text-anchor="middle">

<text
 x="800"
 y="337"
 fill="#eafff7"
 font-size="82"
 font-weight="700"
 letter-spacing="8">
MA
</text>

<text
 x="800"
 y="372"
 fill="#00ffb3"
 font-size="10"
 letter-spacing="5">
MOHAMMAD AMIN
</text>

</g>

<!-- FOOTER -->

<g
 font-family="monospace"
 text-anchor="middle">

<text
 x="800"
 y="566"
 fill="#d8fff3"
 font-size="12"
 letter-spacing="5">
CYBERSECURITY STUDENT
</text>

<text
 x="800"
 y="593"
 fill="#6b8880"
 font-size="10"
 letter-spacing="3">
LEARN → BUILD → BREAK → ANALYZE → IMPROVE
</text>

</g>

<!-- SCANLINE -->

<rect
 x="30"
 y="30"
 width="1540"
 height="2"
 fill="#00ffb3"
 opacity=".3">

<animate
 attributeName="y"
 values="30;610;30"
 dur="8s"
 repeatCount="indefinite"/>

</rect>

</svg>
