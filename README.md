<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0A0A0A"/>
      <stop offset="100%" stop-color="#111014"/>
    </linearGradient>
    <radialGradient id="glow1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#F9A8D4" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#F9A8D4" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glow2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#FBCFE8" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#FBCFE8" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="pinkText" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#F9A8D4"/>
      <stop offset="100%" stop-color="#FDE2E4"/>
    </linearGradient>
    <linearGradient id="chipBorder" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#F9A8D4"/>
      <stop offset="100%" stop-color="#FBCFE8"/>
    </linearGradient>
    <filter id="blurBig" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="45"/>
    </filter>
    <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="1200" height="300" rx="18" fill="url(#bg)"/>

  <circle cx="140" cy="60" r="120" fill="url(#glow1)" filter="url(#blurBig)"/>
  <circle cx="1080" cy="250" r="140" fill="url(#glow2)" filter="url(#blurBig)"/>

  <g opacity="0.18" stroke="#F9A8D4" stroke-width="1">
    <line x1="0" y1="40" x2="220" y2="40"/>
    <line x1="220" y1="40" x2="260" y2="80"/>
    <circle cx="260" cy="80" r="3" fill="#F9A8D4"/>
    <line x1="1000" y1="260" x2="1200" y2="260"/>
    <line x1="960" y1="230" x2="1000" y2="260"/>
    <circle cx="960" cy="230" r="3" fill="#F9A8D4"/>
  </g>

  <g transform="translate(48,58)">
    <rect width="430" height="190" rx="12" fill="#0E0D11" stroke="#2A2228" stroke-width="1"/>
    <rect width="430" height="30" rx="12" fill="#161318"/>
    <rect width="430" height="15" y="15" fill="#161318"/>
    <circle cx="20" cy="15" r="5" fill="#F87171"/>
    <circle cx="38" cy="15" r="5" fill="#FBCFE8"/>
    <circle cx="56" cy="15" r="5" fill="#86EFAC"/>
    <text x="20" y="55" font-family="'JetBrains Mono', monospace" font-size="13" fill="#F9A8D4">const developer = {</text>
    <text x="36" y="78" font-family="'JetBrains Mono', monospace" font-size="13" fill="#E8E8EA">name: <tspan fill="#FDE2E4">"Santoshi Kumbhar"</tspan>,</text>
    <text x="36" y="101" font-family="'JetBrains Mono', monospace" font-size="13" fill="#E8E8EA">role: <tspan fill="#FDE2E4">"Full Stack Developer"</tspan>,</text>
    <text x="36" y="124" font-family="'JetBrains Mono', monospace" font-size="13" fill="#E8E8EA">stack: [<tspan fill="#FBCFE8">React, Node, Mongo</tspan>],</text>
    <text x="36" y="147" font-family="'JetBrains Mono', monospace" font-size="13" fill="#E8E8EA">openSource: <tspan fill="#86EFAC">true</tspan></text>
    <text x="20" y="170" font-family="'JetBrains Mono', monospace" font-size="13" fill="#F9A8D4">};</text>
  </g>

  <g transform="translate(560,0)">
    <text x="0" y="118" font-family="'Segoe UI', Arial, sans-serif" font-size="46" font-weight="700" fill="#F5F5F7">Santoshi Kumbhar</text>
    <text x="2" y="150" font-family="'Segoe UI', Arial, sans-serif" font-size="18" fill="url(#pinkText)">Computer Engineering Student  ·  Open Source Contributor</text>

    <g font-family="'JetBrains Mono', monospace" font-size="12" font-weight="600">
      <g transform="translate(0,180)" filter="url(#softGlow)">
        <rect width="76" height="30" rx="15" fill="#151217" stroke="url(#chipBorder)" stroke-width="1.2"/>
        <text x="38" y="19" text-anchor="middle" fill="#FDE2E4">React</text>
      </g>
      <g transform="translate(88,180)" filter="url(#softGlow)">
        <rect width="92" height="30" rx="15" fill="#151217" stroke="url(#chipBorder)" stroke-width="1.2"/>
        <text x="46" y="19" text-anchor="middle" fill="#FDE2E4">Node.js</text>
      </g>
      <g transform="translate(192,180)" filter="url(#softGlow)">
        <rect width="106" height="30" rx="15" fill="#151217" stroke="url(#chipBorder)" stroke-width="1.2"/>
        <text x="53" y="19" text-anchor="middle" fill="#FDE2E4">MongoDB</text>
      </g>
      <g transform="translate(310,180)" filter="url(#softGlow)">
        <rect width="130" height="30" rx="15" fill="#151217" stroke="url(#chipBorder)" stroke-width="1.2"/>
        <text x="65" y="19" text-anchor="middle" fill="#FDE2E4">Open Source</text>
      </g>
    </g>
  </g>

  <rect x="0.5" y="0.5" width="1199" height="299" rx="18" fill="none" stroke="#2A2228" stroke-width="1"/>
</svg>
