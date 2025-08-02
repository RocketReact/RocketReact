![](https://komarev.com/ghpvc/?username=RocketReact&color=blue&style=flat)

<svg width="1200" height="400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Gradient background -->
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a1a2e"/>
      <stop offset="25%" style="stop-color:#16213e"/>
      <stop offset="50%" style="stop-color:#0f3460"/>
      <stop offset="75%" style="stop-color:#533483"/>
      <stop offset="100%" style="stop-color:#e94560"/>
    </linearGradient>
    
    <!-- Text gradient -->
    <linearGradient id="textGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f5ff"/>
      <stop offset="25%" style="stop-color:#00d4ff"/>
      <stop offset="50%" style="stop-color:#36bcf7"/>
      <stop offset="75%" style="stop-color:#7dd3fc"/>
      <stop offset="100%" style="stop-color:#a7f3d0"/>
    </linearGradient>
    
    <!-- Glow effect -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <!-- Floating particles -->
    <circle id="particle" r="2" fill="#36bcf7" opacity="0.6">
      <animate attributeName="cy" values="400;-20;400" dur="15s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.8;0" dur="15s" repeatCount="indefinite"/>
    </circle>
  </defs>
  
  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#bgGradient)"/>
  
  <!-- Animated background shapes -->
  <circle cx="100" cy="100" r="60" fill="#36bcf7" opacity="0.1">
    <animate attributeName="r" values="60;80;60" dur="8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1100" cy="300" r="40" fill="#a7f3d0" opacity="0.15">
    <animate attributeName="r" values="40;60;40" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="300" cy="350" r="30" fill="#7dd3fc" opacity="0.1">
    <animate attributeName="r" values="30;50;30" dur="10s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Floating particles -->
  <use href="#particle" x="200" y="50">
    <animate attributeName="x" values="200;250;200" dur="12s" repeatCount="indefinite"/>
  </use>
  <use href="#particle" x="800" y="100">
    <animate attributeName="x" values="800;750;800" dur="14s" repeatCount="indefinite"/>
  </use>
  <use href="#particle" x="1000" y="200">
    <animate attributeName="x" values="1000;1050;1000" dur="16s" repeatCount="indefinite"/>
  </use>
  <use href="#particle" x="150" y="250">
    <animate attributeName="x" values="150;200;150" dur="11s" repeatCount="indefinite"/>
  </use>
  <use href="#particle" x="950" y="80">
    <animate attributeName="x" values="950;900;950" dur="13s" repeatCount="indefinite"/>
  </use>
  
  <!-- Cursor icon -->
  <g transform="translate(780, 230)">
    <path d="M0,0 L0,20 L6,15 L12,24 L18,20 L8,12 L20,12 Z" fill="#ffffff" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" values="0,0; 5,5; 0,0" dur="3s" repeatCount="indefinite"/>
    </path>
  </g>
  
  <!-- Main text -->
  <text x="600" y="180" text-anchor="middle" font-family="Arial, sans-serif" font-size="48" font-weight="300" fill="#ffffff" opacity="0.9">
    Hi 👋, I'm
  </text>
  
  <!-- Name with gradient and glow -->
  <text x="600" y="260" text-anchor="middle" font-family="Arial, sans-serif" font-size="72" font-weight="bold" fill="url(#textGradient)" filter="url(#glow)">
    Shapoval Oleg
  </text>
  
  <!-- Decorative lines -->
  <line x1="200" y1="320" x2="1000" y2="320" stroke="url(#textGradient)" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,1000;1000,0;0,1000" dur="8s" repeatCount="indefinite"/>
  </line>
  
  <!-- Code-like decorative elements -->
  <text x="100" y="50" font-family="monospace" font-size="14" fill="#36bcf7" opacity="0.5">&lt;developer&gt;</text>
  <text x="1000" y="370" font-family="monospace" font-size="14" fill="#a7f3d0" opacity="0.5">&lt;/creative&gt;</text>
  
  <!-- Subtle grid pattern -->
  <defs>
    <pattern id="grid" width="50" height="50" patternUnits="userSpaceOnUse">
      <path d="M 50 0 L 0 0 0 50" fill="none" stroke="#36bcf7" stroke-width="0.5" opacity="0.1"/>
    </pattern>
  </defs>
  <rect width="100%" height="100%" fill="url(#grid)"/>
</svg>
<!--
**RocketReact/RocketReact** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=RocketReact&show_icons=true&theme=tokyonight" alt="GitHub Stats"/>
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RocketReact&layout=compact&theme=tokyonight" alt="Top Languages"/>
</div>
