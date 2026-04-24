<div align="center">

<svg width="800" height="450" viewBox="0 0 800 450" xmlns="http://www.w3.org/2000/svg">

<!-- Background -->
<rect width="800" height="450" fill="#0d1117"/>

<!-- Links -->
<g stroke="#444" stroke-width="2">
  <line x1="200" y1="200" x2="400" y2="100"/>
  <line x1="400" y1="100" x2="600" y2="200"/>
  <line x1="200" y1="200" x2="400" y2="250"/>
  <line x1="600" y1="200" x2="400" y2="250"/>
</g>

<!-- Routers -->
<circle cx="400" cy="100" r="30" fill="#1f6feb"/>
<text x="400" y="105" fill="white" font-size="12" text-anchor="middle">R1</text>

<circle cx="200" cy="200" r="30" fill="#1f6feb"/>
<text x="200" y="205" fill="white" font-size="12" text-anchor="middle">R2</text>

<circle cx="600" cy="200" r="30" fill="#1f6feb"/>
<text x="600" y="205" fill="white" font-size="12" text-anchor="middle">R3</text>

<!-- Switch -->
<rect x="370" y="240" width="60" height="30" fill="#238636"/>
<text x="400" y="290" fill="white" font-size="12" text-anchor="middle">SW1</text>

<!-- Servers -->
<rect x="100" y="60" width="40" height="60" fill="#7c3aed"/>
<text x="120" y="135" fill="white" font-size="10" text-anchor="middle">DNS</text>

<rect x="660" y="60" width="40" height="60" fill="#7c3aed"/>
<text x="680" y="135" fill="white" font-size="10" text-anchor="middle">WEB</text>

<!-- Packet Animation (SAFE) -->
<circle r="5" fill="#58a6ff">
  <animateMotion dur="4s" repeatCount="indefinite">
    <mpath href="#p"/>
  </animateMotion>
</circle>

<path id="p" d="M100,80 L200,200 L400,100 L600,200 L680,80" fill="none"/>

</svg>

</div>
