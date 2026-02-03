<!-- =============================== -->
<!--        BABLU MIA PROFILE        -->
<!-- =============================== -->

<!-- 🔥 Animated Developer Cover Banner -->
<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" width="1920" height="480" viewBox="0 0 1920 480">
  <defs>
    <!-- Animated gradient background -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#3b3f8f">
        <animate attributeName="stop-color" dur="10s" repeatCount="indefinite"
          values="#3b3f8f;#1b2a6f;#6d3c8e;#3b3f8f" />
      </stop>
      <stop offset="55%" stop-color="#8a6aa1">
        <animate attributeName="stop-color" dur="12s" repeatCount="indefinite"
          values="#8a6aa1;#5b7bb3;#b26a8f;#8a6aa1" />
      </stop>
      <stop offset="100%" stop-color="#b08a92">
        <animate attributeName="stop-color" dur="11s" repeatCount="indefinite"
          values="#b08a92;#8aa7c8;#c58aa0;#b08a92" />
      </stop>
    </linearGradient>

    <!-- Subtle galaxy / nebula glow -->
    <radialGradient id="nebula1" cx="32%" cy="38%" r="70%">
      <stop offset="0%" stop-color="#7c3aed" stop-opacity="0.55"/>
      <stop offset="45%" stop-color="#22d3ee" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#000" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="nebula2" cx="72%" cy="52%" r="75%">
      <stop offset="0%" stop-color="#fb7185" stop-opacity="0.42"/>
      <stop offset="50%" stop-color="#a78bfa" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#000" stop-opacity="0"/>
    </radialGradient>

    <!-- Glow filters -->
    <filter id="softGlow" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur stdDeviation="8" result="b"/>
      <feMerge>
        <feMergeNode in="b"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <filter id="textGlow" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Moon shading -->
    <radialGradient id="moonShade" cx="35%" cy="35%" r="70%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.98"/>
      <stop offset="55%" stop-color="#e5e7eb" stop-opacity="0.95"/>
      <stop offset="100%" stop-color="#9ca3af" stop-opacity="0.9"/>
    </radialGradient>

    <style><![CDATA[
      /* Font stacks: gives a noticeably different look vs plain system sans. 
         Still not guaranteed across all devices (GitHub limitation). */
      .name {
        font-family: "Space Grotesk","Montserrat","Poppins","Inter","Segoe UI",Arial,sans-serif;
        font-weight: 900;
        letter-spacing: 1.2px;
      }
      .title {
        font-family: "Space Grotesk","Montserrat","Inter","Segoe UI",Arial,sans-serif;
        font-weight: 500;
        letter-spacing: 1px;
      }

      /* Nebula drift */
      .driftA { animation: driftA 14s ease-in-out infinite; }
      .driftB { animation: driftB 18s ease-in-out infinite; }
      @keyframes driftA { 0%,100%{transform:translate(-24px,-10px);opacity:.85} 50%{transform:translate(32px,12px);opacity:1} }
      @keyframes driftB { 0%,100%{transform:translate(22px,10px);opacity:.75} 50%{transform:translate(-30px,-14px);opacity:1} }

      /* Stars: drift + twinkle */
      .stars { animation: starDrift 26s linear infinite; }
      @keyframes starDrift { from{transform:translateX(0)} to{transform:translateX(-260px)} }

      .tw1 { animation: tw 2.7s ease-in-out infinite; }
      .tw2 { animation: tw 3.6s ease-in-out infinite; }
      .tw3 { animation: tw 4.4s ease-in-out infinite; }
      @keyframes tw { 0%,100%{opacity:.25;transform:scale(1)} 50%{opacity:1;transform:scale(1.25)} }

      /* Moon float */
      .moon { animation: moon 20s ease-in-out infinite; transform-origin: 1600px 120px; }
      @keyframes moon { 0%,100%{transform:translate(0,0)} 50%{transform:translate(-58px,18px)} }

      /* Waves: like your image, but animated */
      .wave1 { animation: wave1 10s ease-in-out infinite; }
      .wave2 { animation: wave2 14s ease-in-out infinite; }
      .wave3 { animation: wave3 18s ease-in-out infinite; }

      @keyframes wave1 { 0%,100%{transform:translateX(0)} 50%{transform:translateX(-45px)} }
      @keyframes wave2 { 0%,100%{transform:translateX(0)} 50%{transform:translateX(55px)} }
      @keyframes wave3 { 0%,100%{transform:translateX(0)} 50%{transform:translateX(-70px)} }

      /* Shooting star */
      .shoot { animation: shoot 7.5s linear infinite; }
      @keyframes shoot {
        0%   { transform: translate(-260px,-140px); opacity: 0; }
        10%  { opacity: 1; }
        22%  { transform: translate(620px,210px); opacity: 0; }
        100% { opacity: 0; }
      }
    ]]></style>
  </defs>

  <!-- Background -->
  <rect width="1920" height="480" fill="url(#bgGrad)"/>

  <!-- Galaxy / nebula glow -->
  <g filter="url(#softGlow)">
    <ellipse class="driftA" cx="740" cy="220" rx="820" ry="350" fill="url(#nebula1)"/>
    <ellipse class="driftB" cx="1260" cy="280" rx="860" ry="370" fill="url(#nebula2)"/>
  </g>

  <!-- Moon -->
  <g class="moon" filter="url(#softGlow)">
    <circle cx="1600" cy="120" r="56" fill="url(#moonShade)"/>
    <circle cx="1582" cy="110" r="8" fill="#cbd5e1" opacity="0.7"/>
    <circle cx="1618" cy="136" r="6" fill="#cbd5e1" opacity="0.55"/>
    <circle cx="1595" cy="146" r="4" fill="#cbd5e1" opacity="0.5"/>
    <circle cx="1622" cy="120" r="56" fill="#0b1026" opacity="0.16"/>
  </g>

  <!-- Shooting star -->
  <g class="shoot" filter="url(#softGlow)">
    <path d="M0 0 L160 56" stroke="#ffffff" stroke-width="2.3" stroke-linecap="round" opacity="0.9"/>
    <path d="M10 5 L180 68" stroke="#a78bfa" stroke-width="1.5" stroke-linecap="round" opacity="0.7"/>
  </g>

  <!-- Stars (two layers for looping drift) -->
  <g class="stars">
    <g>
      <!-- bright -->
      <circle class="tw1" cx="160" cy="92" r="2.2" fill="#fff"/>
      <circle class="tw2" cx="420" cy="68" r="1.8" fill="#e0f2fe"/>
      <circle class="tw3" cx="690" cy="120" r="2.0" fill="#fff7ed"/>
      <circle class="tw2" cx="1030" cy="86" r="2.3" fill="#fff"/>
      <circle class="tw3" cx="1410" cy="130" r="1.9" fill="#e9d5ff"/>
      <circle class="tw1" cx="1700" cy="88" r="2.2" fill="#fff"/>

      <!-- small field -->
      <circle class="tw3" cx="260" cy="200" r="1.1" fill="#fff"/>
      <circle class="tw2" cx="320" cy="255" r="1.0" fill="#fff"/>
      <circle class="tw1" cx="520" cy="220" r="1.0" fill="#fff"/>
      <circle class="tw2" cx="600" cy="285" r="1.1" fill="#fff"/>
      <circle class="tw3" cx="760" cy="305" r="1.0" fill="#fff"/>
      <circle class="tw2" cx="900" cy="245" r="1.0" fill="#fff"/>
      <circle class="tw1" cx="980" cy="318" r="1.1" fill="#fff"/>
      <circle class="tw3" cx="1140" cy="225" r="1.0" fill="#fff"/>
      <circle class="tw2" cx="1265" cy="302" r="1.0" fill="#fff"/>
      <circle class="tw1" cx="1340" cy="242" r="1.0" fill="#fff"/>
      <circle class="tw3" cx="1520" cy="282" r="1.1" fill="#fff"/>
      <circle class="tw2" cx="1620" cy="240" r="1.0" fill="#fff"/>
      <circle class="tw1" cx="1780" cy="265" r="1.0" fill="#fff"/>
    </g>

    <!-- duplicate shifted for seamless drift -->
    <g transform="translate(260,0)">
      <circle class="tw1" cx="1880" cy="92" r="2.2" fill="#fff"/>
      <circle class="tw2" cx="1640" cy="68" r="1.8" fill="#e0f2fe"/>
      <circle class="tw3" cx="1410" cy="120" r="2.0" fill="#fff7ed"/>
      <circle class="tw2" cx="1100" cy="86" r="2.3" fill="#fff"/>
      <circle class="tw3" cx="860"  cy="130" r="1.9" fill="#e9d5ff"/>
      <circle class="tw1" cx="640"  cy="88" r="2.2" fill="#fff"/>
    </g>
  </g>

  <!-- Text -->
  <g filter="url(#textGlow)">
    <text x="960" y="215" text-anchor="middle" font-size="98" fill="#ffffff" class="name">
      Bablu Mia
    </text>
    <text x="960" y="276" text-anchor="middle" font-size="30" fill="#f3f4f6" class="title">
      Software Developer  |  Frontend Engineer
    </text>
  </g>

  <!-- Waves like your reference (layered + animated) -->
  <g opacity="0.95">
    <path class="wave1"
      d="M0,360 C240,320 520,410 820,374 C1120,336 1420,300 1720,372 C1840,402 1920,392 1920,392 L1920,480 L0,480 Z"
      fill="#0b0f1f" opacity="0.35"/>

    <path class="wave2"
      d="M0,382 C280,350 520,430 820,398 C1120,366 1440,334 1720,405 C1840,434 1920,420 1920,420 L1920,480 L0,480 Z"
      fill="#070a14" opacity="0.45"/>

    <path class="wave3"
      d="M0,404 C300,376 560,452 860,420 C1160,388 1460,356 1720,430 C1845,465 1920,448 1920,448 L1920,480 L0,480 Z"
      fill="#050611" opacity="0.6"/>
  </g>
</svg>

  
  
</p>

<!-- Typing Animation Intro -->
<p align="center">
  <img 
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=700&center=true&vCenter=true&width=850&lines=Hi%2C+I'm+Bablu+Mia+%F0%9F%91%8B;Software+Developer+%7C+Frontend+Engineer;Building+Scalable+HRM%2C+Chat+%26+Inventory+Systems;Clean+UI%2C+Fast+Performance%2C+Real+Products"
    alt="Typing SVG"
  />
</p>

---

## 👨‍💻 About Me

Hi, I'm **Bablu Mia**, a passionate **Software Developer** focused on building:

- ⚡ High-performance web applications  
- 🎯 Scalable HRM, Chat, and Inventory systems  
- 🎨 Modern UI/UX with clean architecture  

📍 Based in **Sylhet, Bangladesh**  
💼 Working at **Devsstream Limited** *(Feb 2022 — Present)*  

---

## 🚀 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vue.js-42b883?style=for-the-badge&logo=vue.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nuxt.js-00C58E?style=for-the-badge&logo=nuxtdotjs&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
</p>

---

## 💼 Work Experience

### **Software Developer — Devsstream Limited**
📅 **Feb 2022 — Present**

- Developed scalable web applications with strong focus on **UX + performance**
- Built **real-time chat systems** with media sharing, group chat & role control  
- Worked on enterprise-level **HRM platform** modules  
- Led frontend development ensuring smooth UI consistency  

---

## 🌟 Featured Projects

### 🔹 SnowTex — Real-time Chat Application
- Real-time messaging with media sharing  
- Group chat administration + role control  
- Enhanced multimedia interaction features  

🚀 *Tech:* React, WebSockets, Tailwind  

---

### 🔹 Kaaruj Bangladesh — Inventory Management System
- Product + stock management  
- Multi-outlet scalability  
- Role-based access, invoicing, reporting, e-commerce integration  

🚀 *Tech:* Vue, Nuxt, TypeScript  

---

## 📬 Contact Me

<p align="center">
  <a href="mailto:info.bablu1707@gmail.com">
    <img src="https://img.shields.io/badge/Email-info.bablu1707%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/bablu-mia-71a158210/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Bablu%20Mia-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://www.bablumia.site/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-bablumia.site-111827?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <i>✨ “I turn complex ideas into meaningful digital experiences.” ✨</i>
</p>
