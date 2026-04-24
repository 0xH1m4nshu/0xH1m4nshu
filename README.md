<div align="center">

<svg width="900" height="520" viewBox="0 0 900 520" xmlns="http://www.w3.org/2000/svg">

<!-- BACKGROUND -->
<rect width="900" height="520" rx="15" fill="#0d1117"/>

<!-- LINKS -->
<g stroke="#30363d" stroke-width="2">
  <line x1="200" y1="200" x2="450" y2="100"/>
  <line x1="450" y1="100" x2="700" y2="200"/>
  <line x1="200" y1="200" x2="450" y2="260"/>
  <line x1="700" y1="200" x2="450" y2="260"/>
  <line x1="450" y1="260" x2="450" y2="360"/>
</g>

<!-- ROUTERS -->
<g fill="#1f6feb" stroke="#58a6ff" stroke-width="2">
  <circle cx="450" cy="100" r="35"/>
  <text x="450" y="105" fill="white" font-size="14" text-anchor="middle">R1</text>

  <circle cx="200" cy="200" r="35"/>
  <text x="200" y="205" fill="white" font-size="14" text-anchor="middle">R2</text>

  <circle cx="700" cy="200" r="35"/>
  <text x="700" y="205" fill="white" font-size="14" text-anchor="middle">R3</text>
</g>

<!-- SWITCH -->
<rect x="415" y="245" width="70" height="30" rx="8" fill="#238636"/>
<text x="450" y="285" fill="white" font-size="12" text-anchor="middle">SW1</text>

<!-- SERVERS -->
<g fill="#7c3aed">
  <rect x="120" y="70" width="40" height="60" rx="6"/>
  <text x="140" y="145" fill="#c9d1d9" font-size="10" text-anchor="middle">DNS</text>

  <rect x="760" y="70" width="40" height="60" rx="6"/>
  <text x="780" y="145" fill="#c9d1d9" font-size="10" text-anchor="middle">WEB</text>
</g>

<!-- DEVICES -->
<g fill="#d29922">
  <rect x="120" y="320" width="30" height="20" rx="4"/>
  <text x="135" y="355" fill="#c9d1d9" font-size="10" text-anchor="middle">PC</text>

  <rect x="250" y="320" width="30" height="20" rx="4"/>
  <text x="265" y="355" fill="#c9d1d9" font-size="10" text-anchor="middle">Laptop</text>

  <rect x="620" y="320" width="30" height="20" rx="4"/>
  <text x="635" y="355" fill="#c9d1d9" font-size="10" text-anchor="middle">Phone</text>
</g>

<!-- SDN -->
<rect x="425" y="370" width="50" height="35" rx="8" fill="#da3633"/>
<text x="450" y="420" fill="#c9d1d9" font-size="10" text-anchor="middle">SDN</text>

<!-- PACKET PATH -->
<path id="packetPath" d="M120,100 L200,200 L450,100 L700,200 L780,100" fill="none"/>

<!-- PACKET -->
<circle r="6" fill="#58a6ff">
  <animateMotion dur="5s" repeatCount="indefinite">
    <mpath href="#packetPath"/>
  </animateMotion>
</circle>

<!-- LEGEND -->
<g font-size="11" fill="#8b949e">
  <rect x="20" y="480" width="15" height="10" fill="#ff7b72"/>
  <text x="45" y="489">ICMP</text>

  <rect x="120" y="480" width="15" height="10" fill="#3fb950"/>
  <text x="145" y="489">HTTP</text>

  <rect x="220" y="480" width="15" height="10" fill="#d29922"/>
  <text x="245" y="489">ARP</text>

  <rect x="320" y="480" width="15" height="10" fill="#58a6ff"/>
  <text x="345" y="489">DATA</text>
</g>

</svg>

</div>

<br/>
