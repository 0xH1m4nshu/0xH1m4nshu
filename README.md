<div align="center">

<!-- NETWORK ANIMATION SVG START -->
<svg width="680" height="480" viewBox="0 0 680 480" xmlns="http://www.w3.org/2000/svg">

  <!-- Background -->
  <rect width="680" height="480" rx="12" fill="#0d1117"/>

  <!-- Simple demo (shortened for GitHub safety) -->
  <!-- Router -->
  <circle cx="340" cy="120" r="30" fill="#1d3a6e" stroke="#58a6ff" stroke-width="2"/>
  <text x="340" y="125" fill="#c9d1d9" font-size="12" text-anchor="middle">R1</text>

  <!-- Switch -->
  <rect x="310" y="240" width="60" height="30" rx="5" fill="#1a3d1a" stroke="#3fb950"/>
  <text x="340" y="290" fill="#c9d1d9" font-size="12" text-anchor="middle">SW1</text>

  <!-- Server -->
  <rect x="600" y="80" width="40" height="60" rx="5" fill="#2d1f5e" stroke="#7F77DD"/>
  <text x="620" y="155" fill="#c9d1d9" font-size="10" text-anchor="middle">WEB</text>

  <!-- Lines -->
  <line x1="340" y1="150" x2="340" y2="240" stroke="#30363d"/>
  <line x1="340" y1="120" x2="600" y2="100" stroke="#30363d"/>

  <!-- Animated Packet -->
  <circle r="6" fill="#58a6ff">
    <animateMotion dur="4s" repeatCount="indefinite">
      <mpath href="#path1"/>
    </animateMotion>
  </circle>

  <path id="path1" d="M340,120 L600,100" fill="none"/>

</svg>
<!-- NETWORK ANIMATION SVG END -->

<br/>
