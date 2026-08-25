<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1280 420" role="img" aria-label="Anas Saad — from aerospace systems to software and GenAI">
  <defs>
    <linearGradient id="sky" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#071018"/>
      <stop offset="45%" stop-color="#0b1a28"/>
      <stop offset="100%" stop-color="#06131d"/>
    </linearGradient>
    <radialGradient id="glowA" cx="18%" cy="20%" r="55%">
      <stop offset="0%" stop-color="#22d3ee" stop-opacity="0.28"/>
      <stop offset="100%" stop-color="#22d3ee" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowB" cx="88%" cy="80%" r="50%">
      <stop offset="0%" stop-color="#e8b84a" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#e8b84a" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="path" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="100%" stop-color="#e8b84a"/>
    </linearGradient>
    <linearGradient id="name" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#f7fbff"/>
      <stop offset="100%" stop-color="#d7eef5"/>
    </linearGradient>
    <pattern id="grid" width="32" height="32" patternUnits="userSpaceOnUse">
      <path d="M32 0H0V32" fill="none" stroke="#7dd3fc" stroke-opacity="0.07" stroke-width="1"/>
    </pattern>
    <filter id="soft" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="8" result="b"/>
      <feMerge>
        <feMergeNode in="b"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="grain">
      <feTurbulence type="fractalNoise" baseFrequency="0.85" numOctaves="3" stitchTiles="stitch"/>
      <feColorMatrix type="saturate" values="0"/>
      <feComponentTransfer>
        <feFuncA type="linear" slope="0.05"/>
      </feComponentTransfer>
    </filter>
  </defs>
  <rect width="1280" height="420" rx="28" fill="url(#sky)"/>
  <rect width="1280" height="420" rx="28" fill="url(#glowA)"/>
  <rect width="1280" height="420" rx="28" fill="url(#glowB)"/>
  <rect width="1280" height="420" rx="28" fill="url(#grid)"/>
  <rect width="1280" height="420" rx="28" filter="url(#grain)" opacity="0.35"/>
  <!-- HUD corners -->
  <g fill="none" stroke="#67e8f9" stroke-opacity="0.55" stroke-width="1.5">
    <path d="M36 78V48h30"/>
    <path d="M1244 78V48h-30"/>
    <path d="M36 342v30h30"/>
    <path d="M1244 342v30h-30"/>
  </g>
  <!-- Flight path -->
  <path d="M90 290 C 280 290, 340 150, 560 168 S 860 310, 1190 150" fill="none" stroke="url(#path)" stroke-width="2.4" stroke-linecap="round" opacity="0.9"/>
  <path d="M90 290 C 280 290, 340 150, 560 168 S 860 310, 1190 150" fill="none" stroke="url(#path)" stroke-width="10" stroke-linecap="round" opacity="0.12" filter="url(#soft)"/>
  <!-- Waypoints -->
  <g>
    <circle cx="90" cy="290" r="6" fill="#071018" stroke="#22d3ee" stroke-width="2"/>
    <circle cx="560" cy="168" r="6" fill="#071018" stroke="#7dd3fc" stroke-width="2"/>
    <circle cx="1190" cy="150" r="7" fill="#e8b84a" stroke="#fde68a" stroke-width="2"/>
  </g>
  <!-- Tiny craft at the gold node -->
  <g transform="translate(1190,150) rotate(-18)">
    <path d="M0,-10 L7,8 L0,4 L-7,8 Z" fill="#fde68a"/>
  </g>
  <!-- Telemetry -->
  <g font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" fill="#9fb6c4">
    <text x="56" y="72" font-size="12" letter-spacing="3.2">ORIGIN  ·  YYZ / TORONTO</text>
    <text x="900" y="72" font-size="12" letter-spacing="3.2" text-anchor="end">VECTOR  ·  FULL-STACK + GENAI</text>
    <text x="1224" y="72" font-size="12" letter-spacing="3.2" text-anchor="end">STATUS  ·  IN PRODUCTION</text>
  </g>
  <text x="56" y="168" font-family="Segoe UI, Helvetica Neue, Arial, sans-serif" font-size="18" letter-spacing="7" fill="#67e8f9">SOFTWARE DEVELOPER</text>
  <text x="52" y="238" font-family="Segoe UI, Helvetica Neue, Arial, sans-serif" font-size="76" font-weight="700" letter-spacing="4" fill="url(#name)">ANAS SAAD</text>
  <text x="56" y="286" font-family="Segoe UI, Helvetica Neue, Arial, sans-serif" font-size="22" fill="#d5e7ef">Aerospace systems thinking. Bank-scale software. Models that ship.</text>
  <!-- Chips -->
  <g font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace" font-size="13">
    <rect x="56" y="328" width="168" height="34" rx="17" fill="#0c2230" stroke="#22d3ee" stroke-opacity="0.35"/>
    <text x="140" y="350" text-anchor="middle" fill="#e8fbff">TypeScript</text>
    <rect x="236" y="328" width="128" height="34" rx="17" fill="#0c2230" stroke="#22d3ee" stroke-opacity="0.35"/>
    <text x="300" y="350" text-anchor="middle" fill="#e8fbff">Python</text>
    <rect x="376" y="328" width="128" height="34" rx="17" fill="#0c2230" stroke="#22d3ee" stroke-opacity="0.35"/>
    <text x="440" y="350" text-anchor="middle" fill="#e8fbff">Angular</text>
    <rect x="516" y="328" width="148" height="34" rx="17" fill="#1a1608" stroke="#e8b84a" stroke-opacity="0.45"/>
    <text x="590" y="350" text-anchor="middle" fill="#fde68a">GenAI @ BMO</text>
  </g>
</svg>
