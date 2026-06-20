<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 900" width="600" height="900">
  <!-- Background - Deep Space -->
  <rect width="600" height="900" fill="#0a0a1a"/>
  
  <!-- Stars -->
  <circle cx="50" cy="80" r="1.5" fill="white" opacity="0.8"/>
  <circle cx="150" cy="40" r="1" fill="white" opacity="0.6"/>
  <circle cx="300" cy="20" r="2" fill="white" opacity="0.9"/>
  <circle cx="450" cy="60" r="1.5" fill="white" opacity="0.7"/>
  <circle cx="550" cy="30" r="1" fill="white" opacity="0.5"/>
  <circle cx="80" cy="200" r="1" fill="white" opacity="0.4"/>
  <circle cx="520" cy="180" r="1.5" fill="white" opacity="0.6"/>
  <circle cx="30" cy="350" r="1" fill="white" opacity="0.5"/>
  <circle cx="570" cy="400" r="1.5" fill="white" opacity="0.7"/>
  <circle cx="100" cy="500" r="1" fill="white" opacity="0.3"/>
  <circle cx="500" cy="550" r="1" fill="white" opacity="0.5"/>
  <circle cx="200" cy="750" r="1.5" fill="white" opacity="0.6"/>
  <circle cx="400" cy="800" r="1" fill="white" opacity="0.4"/>
  <circle cx="60" cy="650" r="1.5" fill="white" opacity="0.5"/>
  <circle cx="540" cy="700" r="1" fill="white" opacity="0.3"/>
  
  <!-- Nebula glow -->
  <ellipse cx="300" cy="450" rx="250" ry="350" fill="url(#nebula)" opacity="0.3"/>
  <defs>
    <radialGradient id="nebula" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff0044" stop-opacity="0.6"/>
      <stop offset="50%" stop-color="#4400ff" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#0a0a1a" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ffcc00"/>
      <stop offset="50%" stop-color="#ff6600"/>
      <stop offset="100%" stop-color="#ffcc00"/>
    </linearGradient>
    <linearGradient id="subGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="50%" stop-color="#ffaa00"/>
      <stop offset="100%" stop-color="#ffffff"/>
    </linearGradient>
  </defs>
  
  <!-- Nova helmet silhouette (center) -->
  <g transform="translate(300, 380)">
    <!-- Helmet base -->
    <path d="M-80,0 Q-80,-100 -40,-140 Q0,-170 40,-140 Q80,-100 80,0 Q80,40 60,80 L-60,80 Q-80,40 -80,0 Z" 
          fill="none" stroke="#ffcc00" stroke-width="3" opacity="0.6"/>
    <!-- Helmet glow -->
    <path d="M-70,0 Q-70,-90 -35,-125 Q0,-150 35,-125 Q70,-90 70,0 Q70,35 52,70 L-52,70 Q-70,35 -70,0 Z" 
          fill="url(#helmetGlow)" opacity="0.4"/>
    <defs>
      <radialGradient id="helmetGlow" cx="50%" cy="30%" r="60%">
        <stop offset="0%" stop-color="#ff6600" stop-opacity="0.8"/>
        <stop offset="100%" stop-color="#ffcc00" stop-opacity="0"/>
      </radialGradient>
    </defs>
    <!-- Star symbol on chest -->
    <polygon points="0,10 8,-10 -8,-10" fill="#ffcc00" opacity="0.9"/>
    <polygon points="0,10 5,-5 -5,-5" fill="#ffffff" opacity="0.5"/>
  </g>
  
  <!-- Title: NOVA -->
  <text x="300" y="580" text-anchor="middle" font-family="Arial Black, Impact, sans-serif" font-size="120" font-weight="900" fill="url(#titleGrad)" letter-spacing="15">
    NOVA
  </text>
  
  <!-- Subtitle -->
  <text x="300" y="630" text-anchor="middle" font-family="Arial, sans-serif" font-size="22" fill="url(#subGrad)" letter-spacing="8" font-weight="bold">
    THE HUMAN ROCKET
  </text>
  
  <!-- Tagline -->
  <text x="300" y="680" text-anchor="middle" font-family="Georgia, serif" font-size="16" fill="#cccccc" letter-spacing="3" font-style="italic">
    "From the depths of space, a new hero rises."
  </text>
  
  <!-- Bottom info bar -->
  <rect x="100" y="720" width="400" height="50" rx="5" fill="none" stroke="#ff6600" stroke-width="1.5" opacity="0.5"/>
  <text x="300" y="750" text-anchor="middle" font-family="Arial, sans-serif" font-size="12" fill="#ffaa00" letter-spacing="2">
    COMING SOON · 2026
  </text>
  
  <!-- Marvel-style corner logo -->
  <rect x="20" y="20" width="80" height="30" rx="3" fill="#ed1d24"/>
  <text x="60" y="42" text-anchor="middle" font-family="Arial, sans-serif" font-size="14" fill="white" font-weight="bold" letter-spacing="1">
    MARVEL
  </text>
  
  <!-- Studio credit -->
  <text x="300" y="860" text-anchor="middle" font-family="Arial, sans-serif" font-size="10" fill="#666666" letter-spacing="3">
    © 2026 MARVEL STUDIOS · ALL RIGHTS RESERVED
  </text>
</svg>
