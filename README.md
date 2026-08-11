<svg width="1200" height="600" viewBox="0 0 1200 600" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#7D0000"/>
      <stop offset="50%" stop-color="#000000"/>
      <stop offset="100%" stop-color="#000000"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7D0000" stop-opacity="0"/>
      <stop offset="50%" stop-color="#f8fafc"/>
      <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="1200" height="600" fill="url(#bg)"/>
  <rect width="1200" height="600" fill="rgba(255,255,255,0.04)"/>

  <g fill="none" stroke="url(#lineGrad)" stroke-width="6" stroke-linecap="round">
    <path d="M140 420 C300 340, 420 320, 560 270 S860 220, 1040 180">
      <animate attributeName="stroke-dasharray" values="0 1200; 1200 0; 0 1200" dur="6s" repeatCount="indefinite"/>
    </path>
    <path d="M180 500 C360 450, 500 420, 680 340 S950 280, 1010 220">
      <animate attributeName="stroke-dasharray" values="1200 0; 0 1200; 1200 0" dur="7s" repeatCount="indefinite"/>
    </path>
  </g>

  <g filter="url(#glow)">
    <circle cx="600" cy="300" r="18" fill="#7D0000">
      <animate attributeName="r" values="16;24;16" dur="2.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.8;1;0.8" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="600" cy="300" r="38" fill="none" stroke="#7D0000" stroke-opacity="0.35" stroke-width="2">
      <animate attributeName="r" values="24;44;24" dur="2.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0;0.3" dur="2.2s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>


<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=ffffff&center=true&width=500&height=80&lines=Seja+bem+vindo!" />
</p>
