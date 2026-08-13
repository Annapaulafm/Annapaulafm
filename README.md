<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgBase" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0e17"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>

    <radialGradient id="blob1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#4facfe" stop-opacity="0.85"/>
      <stop offset="100%" stop-color="#4facfe" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="blob2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff6ec7" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#ff6ec7" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="blob3" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#8a2be2" stop-opacity="0.85"/>
      <stop offset="100%" stop-color="#8a2be2" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="blob4" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#a855f7" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#a855f7" stop-opacity="0"/>
    </radialGradient>

    <filter id="blurHeavy" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="45"/>
    </filter>

    <clipPath id="frame">
      <rect x="0" y="0" width="1200" height="300" rx="18"/>
    </clipPath>

    <linearGradient id="textFade" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="100%" stop-color="#e8e8f5"/>
    </linearGradient>
  </defs>

  <g clip-path="url(#frame)">
    <rect x="0" y="0" width="1200" height="300" fill="url(#bgBase)"/>

    <g filter="url(#blurHeavy)">
      <circle cx="150" cy="80" r="160" fill="url(#blob1)">
        <animate attributeName="cx" values="150;420;150" dur="14s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="80;220;80" dur="11s" repeatCount="indefinite"/>
      </circle>

      <circle cx="950" cy="60" r="180" fill="url(#blob2)">
        <animate attributeName="cx" values="950;700;950" dur="13s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="60;200;60" dur="16s" repeatCount="indefinite"/>
      </circle>

      <circle cx="600" cy="250" r="200" fill="url(#blob3)">
        <animate attributeName="cx" values="600;300;900;600" dur="18s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="250;100;250" dur="15s" repeatCount="indefinite"/>
      </circle>

      <circle cx="1050" cy="230" r="140" fill="url(#blob4)">
        <animate attributeName="cx" values="1050;800;1050" dur="10s" repeatCount="indefinite"/>
        <animate attributeName="cy" values="230;100;230" dur="12s" repeatCount="indefinite"/>
      </circle>
    </g>

    <rect x="0" y="0" width="1200" height="300" fill="#0a0e17" opacity="0.28"/>

    <text x="600" y="130" font-family="'Segoe UI', Arial, sans-serif" font-size="20" letter-spacing="6"
          fill="#ffd1e8" text-anchor="middle" opacity="0.85">
      &gt; COMPUTER SCIENCE STUDENT
    </text>

    <text x="600" y="195" font-family="'Segoe UI', Arial, sans-serif" font-size="62" font-weight="800"
          fill="url(#textFade)" text-anchor="middle">
      I'm Ana Paula
    </text>

    <text x="600" y="235" font-family="'Segoe UI', Arial, sans-serif" font-size="17"
          fill="#c9c9e0" text-anchor="middle" opacity="0.85">
      Welcome to my GitHub · learning, building, breaking things (on purpose)
    </text>

    <rect x="1" y="1" width="1198" height="298" rx="18" fill="none" stroke="#2a2f3a" stroke-width="1"/>
  </g>
</svg>
