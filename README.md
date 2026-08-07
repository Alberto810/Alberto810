# Alberto Henrique | Estudante de Engenharia de Software 💻 

<svg width="1200" height="800" viewBox="0 0 1200 800" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#03060d"/>
      <stop offset="100%" stop-color="#060b16"/>
    </linearGradient>
    <linearGradient id="cyanFill" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#0891b2"/>
      <stop offset="100%" stop-color="#22d3ee"/>
    </linearGradient>
    <radialGradient id="coreGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#22d3ee" stop-opacity="0.35"/>
      <stop offset="70%" stop-color="#0891b2" stop-opacity="0.08"/>
      <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
    </radialGradient>
    <filter id="glow" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softGlow" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="2"/>
    </filter>
    <style>
      .mono { font-family: 'Consolas','Menlo','Courier New',monospace; }
      .head { font-family: 'Arial Black','Segoe UI',sans-serif; font-weight:900; letter-spacing: 4px; }
      .cyan { fill:#5eead4; }
      .cyanBright { fill:#67e8f9; }
      .dim { fill:#5b7185; }
      .green { fill:#34d399; }
      .purple { fill:#a78bfa; }
      .lineCyan { stroke:#0e7490; }
    </style>
  </defs>

  <!-- background -->
  <rect x="0" y="0" width="1200" height="800" fill="url(#bg)"/>

  <!-- outer frame with cut corners -->
  <path d="M40,20 L1120,20 L1160,60 L1160,740 L1120,780 L40,780 L20,760 L20,60 Z"
        fill="none" stroke="#0e7490" stroke-width="1.5" opacity="0.8"/>
  <path d="M40,20 L1120,20 L1160,60 L1160,740 L1120,780 L40,780 L20,760 L20,60 Z"
        fill="none" stroke="#22d3ee" stroke-width="0.6" opacity="0.35"/>

  <!-- corner ticks -->
  <g stroke="#22d3ee" stroke-width="2" opacity="0.9">
    <path d="M20,60 L20,90 M20,60 L50,60" fill="none"/>
    <path d="M1160,60 L1160,90 M1160,60 L1130,60" fill="none"/>
    <path d="M20,760 L20,730 M20,760 L50,760" fill="none"/>
    <path d="M1160,760 L1160,730 M1160,760 L1130,760" fill="none"/>
  </g>

  <!-- top bar -->
  <text x="55" y="65" class="mono head" font-size="20" fill="#67e8f9">JARVIS OS</text>
  <text x="205" y="65" class="mono" font-size="15" fill="#5b7185">v2.7.1</text>

  <g class="mono" font-size="12" fill="#22d3ee">
    <rect x="470" y="52" width="10" height="6" fill="#22d3ee"/>
    <rect x="484" y="52" width="10" height="6" fill="#22d3ee"/>
    <rect x="498" y="52" width="10" height="6" fill="#22d3ee">
      <animate attributeName="opacity" values="1;0.2;1" dur="1.2s" repeatCount="indefinite"/>
    </rect>
    <rect x="512" y="52" width="10" height="6" fill="#0e7490"/>
    <rect x="526" y="52" width="10" height="6" fill="#0e7490"/>
  </g>
  <rect x="560" y="53" width="220" height="4" fill="#22d3ee" opacity="0.9"/>
  <g fill="#0e7490">
    <rect x="800" y="53" width="10" height="4"/>
    <rect x="818" y="53" width="10" height="4"/>
    <rect x="836" y="53" width="10" height="4"/>
    <rect x="854" y="53" width="10" height="4"/>
    <rect x="872" y="53" width="10" height="4"/>
  </g>

  <text x="1145" y="65" text-anchor="end" class="mono" font-size="14" fill="#e2e8f0">USER: ENGINEER</text>

  <!-- title -->
  <text x="600" y="120" text-anchor="middle" class="mono" font-size="22" fill="#67e8f9" letter-spacing="8" filter="url(#glow)">— SYSTEM BOOT —</text>

  <!-- ============ LEFT PANEL: SYSTEM STATUS ============ -->
  <g>
    <path d="M55,165 L375,165 L375,600 L345,630 L55,630 Z" fill="#040810" fill-opacity="0.55" stroke="#0e7490" stroke-width="1"/>
    <text x="75" y="200" class="mono" font-size="16" fill="#67e8f9" letter-spacing="1">SYSTEM STATUS <tspan fill="#0e7490">]</tspan></text>
    <line x1="75" y1="212" x2="355" y2="212" stroke="#0e7490" stroke-width="1" opacity="0.5"/>

    <g class="mono" font-size="14">
      <!-- items -->
      <text x="80" y="245" fill="#22d3ee">&gt;</text><text x="98" y="245" fill="#cbd5e1">CORE SYSTEM</text><text x="345" y="245" text-anchor="end" fill="#34d399">OK</text>
      <text x="80" y="277" fill="#22d3ee">&gt;</text><text x="98" y="277" fill="#cbd5e1">MEMORY MODULES</text><text x="345" y="277" text-anchor="end" fill="#34d399">OK</text>
      <text x="80" y="309" fill="#22d3ee">&gt;</text><text x="98" y="309" fill="#cbd5e1">NEURAL NETWORK</text><text x="345" y="309" text-anchor="end" fill="#34d399">OK</text>
      <text x="80" y="341" fill="#22d3ee">&gt;</text><text x="98" y="341" fill="#cbd5e1">DATA STREAM</text><text x="345" y="341" text-anchor="end" fill="#34d399">OK</text>
      <text x="80" y="373" fill="#22d3ee">&gt;</text><text x="98" y="373" fill="#cbd5e1">CYBER INTERFACE</text><text x="345" y="373" text-anchor="end" fill="#34d399">OK</text>
      <text x="80" y="405" fill="#22d3ee">&gt;</text><text x="98" y="405" fill="#cbd5e1">VISUAL PROTOCOL</text><text x="345" y="405" text-anchor="end" fill="#34d399">OK</text>
      <text x="80" y="437" fill="#22d3ee">&gt;</text><text x="98" y="437" fill="#cbd5e1">SECURITY LAYER</text><text x="345" y="437" text-anchor="end" fill="#34d399">OK</text>
      <text x="80" y="469" fill="#22d3ee">&gt;</text><text x="98" y="469" fill="#cbd5e1">AI CORE</text>
      <text x="270" y="469" fill="#a78bfa">LOADING<tspan>
        <animate attributeName="opacity" values="1;1;0;1" keyTimes="0;0.3;0.65;1" dur="1.4s" repeatCount="indefinite"/>
      </tspan></text>
    </g>

    <line x1="80" y1="490" x2="345" y2="490" stroke="#0e7490" stroke-width="1" opacity="0.4"/>

    <text x="75" y="525" class="mono" font-size="16" fill="#67e8f9">SYSTEM LOG <tspan fill="#0e7490">}</tspan></text>
    <g class="mono" font-size="11.5" fill="#5b7185">
      <text x="80" y="550">[00:00:00] Boot Sequence Initiated</text>
      <text x="80" y="568">[00:00:01] Hardware Check ....... <tspan fill="#34d399">OK</tspan></text>
      <text x="80" y="586">[00:00:02] Memory Sync ......... <tspan fill="#34d399">OK</tspan></text>
      <text x="80" y="604">[00:00:03] Neural Link ......... <tspan fill="#34d399">OK</tspan></text>
      <text x="80" y="622">[00:00:04] AI Core Initializing <tspan fill="#a78bfa">..</tspan></text>
    </g>
  </g>

  <!-- ============ RIGHT PANEL: CORE MODULES ============ -->
  <g>
    <path d="M1145,165 L825,165 L825,600 L855,630 L1145,630 Z" fill="#040810" fill-opacity="0.55" stroke="#0e7490" stroke-width="1"/>
    <text x="1125" y="200" text-anchor="end" class="mono" font-size="16" fill="#67e8f9">CORE MODULES <tspan fill="#0e7490">]</tspan></text>
    <line x1="820" y1="212" x2="1125" y2="212" stroke="#0e7490" stroke-width="1" opacity="0.5"/>

    <!-- module rows: icon substitute + label + bar -->
    <g class="mono" font-size="13" fill="#cbd5e1">
      <!-- PROCESSOR -->
      <rect x="820" y="235" width="26" height="26" rx="4" fill="none" stroke="#22d3ee"/>
      <rect x="828" y="243" width="10" height="10" fill="#22d3ee"/>
      <text x="858" y="240">PROCESSOR UNIT</text>
      <text x="1125" y="240" text-anchor="end" fill="#67e8f9">100%</text>
      <rect x="858" y="250" width="267" height="7" rx="3" fill="#0b1723" stroke="#0e7490" stroke-width="0.5"/>
      <rect x="858" y="250" width="267" height="7" rx="3" fill="url(#cyanFill)"/>

      <!-- MEMORY -->
      <rect x="820" y="283" width="26" height="26" rx="4" fill="none" stroke="#22d3ee"/>
      <line x1="826" y1="291" x2="840" y2="291" stroke="#22d3ee"/>
      <line x1="826" y1="297" x2="840" y2="297" stroke="#22d3ee"/>
      <line x1="826" y1="303" x2="840" y2="303" stroke="#22d3ee"/>
      <text x="858" y="288">MEMORY BANK</text>
      <text x="1125" y="288" text-anchor="end" fill="#67e8f9">100%</text>
      <rect x="858" y="298" width="267" height="7" rx="3" fill="#0b1723" stroke="#0e7490" stroke-width="0.5"/>
      <rect x="858" y="298" width="267" height="7" rx="3" fill="url(#cyanFill)"/>

      <!-- NEURAL ENGINE -->
      <circle cx="833" cy="343" r="13" fill="none" stroke="#22d3ee"/>
      <circle cx="833" cy="343" r="4" fill="#22d3ee"/>
      <text x="858" y="336">NEURAL ENGINE</text>
      <text x="1125" y="336" text-anchor="end" fill="#67e8f9">82%</text>
      <rect x="858" y="346" width="267" height="7" rx="3" fill="#0b1723" stroke="#0e7490" stroke-width="0.5"/>
      <rect x="858" y="346" width="0" height="7" rx="3" fill="url(#cyanFill)">
        <animate attributeName="width" values="0;219;219" keyTimes="0;0.6;1" dur="3s" repeatCount="indefinite" fill="freeze"/>
      </rect>

      <!-- LEARNING MODEL -->
      <path d="M820,378 q13,-14 26,0 q-4,14 -13,14 q-9,0 -13,-14 Z" fill="none" stroke="#22d3ee"/>
      <text x="858" y="384">LEARNING MODEL</text>
      <text x="1125" y="384" text-anchor="end" fill="#67e8f9">68%</text>
      <rect x="858" y="394" width="267" height="7" rx="3" fill="#0b1723" stroke="#0e7490" stroke-width="0.5"/>
      <rect x="858" y="394" width="0" height="7" rx="3" fill="url(#cyanFill)">
        <animate attributeName="width" values="0;182;182" keyTimes="0;0.6;1" dur="3s" repeatCount="indefinite" fill="freeze"/>
      </rect>

      <!-- PREDICTION SYSTEM -->
      <circle cx="833" cy="428" r="13" fill="none" stroke="#22d3ee"/>
      <circle cx="833" cy="428" r="6" fill="none" stroke="#22d3ee"/>
      <text x="858" y="432">PREDICTION SYSTEM</text>
      <text x="1125" y="432" text-anchor="end" fill="#67e8f9">76%</text>
      <rect x="858" y="442" width="267" height="7" rx="3" fill="#0b1723" stroke="#0e7490" stroke-width="0.5"/>
      <rect x="858" y="442" width="0" height="7" rx="3" fill="url(#cyanFill)">
        <animate attributeName="width" values="0;203;203" keyTimes="0;0.6;1" dur="3s" repeatCount="indefinite" fill="freeze"/>
      </rect>
    </g>
  </g>

  <!-- ============ CENTER: AI CORE ============ -->
  <g transform="translate(600,400)">
    <circle r="210" fill="url(#coreGlow)"/>

    <!-- outer rotating dashed ring -->
    <circle r="200" fill="none" stroke="#0e7490" stroke-width="1.5" stroke-dasharray="4 10" opacity="0.55">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="40s" repeatCount="indefinite"/>
    </circle>

    <!-- mid arc ring, partial -->
    <circle r="175" fill="none" stroke="#22d3ee" stroke-width="3" stroke-linecap="round"
            stroke-dasharray="360 720" filter="url(#glow)">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="6s" repeatCount="indefinite"/>
    </circle>

    <!-- inner thin ring -->
    <circle r="150" fill="none" stroke="#0e7490" stroke-width="1" opacity="0.6"/>
    <circle r="150" fill="none" stroke="#22d3ee" stroke-width="2" stroke-dasharray="60 883" stroke-linecap="round">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="5s" repeatCount="indefinite"/>
    </circle>

    <!-- arrow markers left/right -->
    <path d="M-222,0 L-207,-8 L-207,8 Z" fill="#a78bfa"/>
    <path d="M222,0 L207,-8 L207,8 Z" fill="#a78bfa"/>

    <!-- small triangle top/bottom -->
    <path d="M0,-218 L-7,-205 L7,-205 Z" fill="#22d3ee"/>
    <path d="M0,218 L-7,205 L7,205 Z" fill="#22d3ee"/>

    <!-- core text -->
    <text x="0" y="-32" text-anchor="middle" class="mono" font-size="18" fill="#94a3b8" letter-spacing="6">INITIALIZING</text>
    <text x="0" y="20" text-anchor="middle" class="head" font-size="56" fill="#5eead4" filter="url(#glow)" letter-spacing="4">AI CORE</text>

    <!-- progress bar -->
    <rect x="-165" y="55" width="330" height="20" rx="4" fill="#0b1723" stroke="#0e7490" stroke-width="1"/>
    <rect x="-165" y="55" width="0" height="20" rx="4" fill="url(#cyanFill)">
      <animate attributeName="width" values="0;251;251" keyTimes="0;0.7;1" dur="3s" repeatCount="indefinite" fill="freeze"/>
    </rect>
    <text x="0" y="102" text-anchor="middle" class="mono head" font-size="26" fill="#67e8f9" filter="url(#glow)">76%</text>
  </g>

  <!-- tagline -->
  <line x1="60" y1="700" x2="500" y2="700" stroke="#0e7490" opacity="0.5"/>
  <line x1="700" y1="700" x2="1140" y2="700" stroke="#0e7490" opacity="0.5"/>
  <text x="600" y="706" text-anchor="middle" class="mono" font-size="15" fill="#7dd3fc" letter-spacing="2">// THE FUTURE IS CODED. THE LIMIT IS YOU. //</text>

  <!-- footer icons -->
  <g class="mono" font-size="13">
    <!-- TERMINAL -->
    <rect x="65" y="735" width="34" height="34" rx="6" fill="none" stroke="#22d3ee"/>
    <text x="76" y="757" fill="#22d3ee" font-size="14">&gt;_</text>
    <text x="112" y="750" fill="#cbd5e1">TERMINAL</text>
    <text x="112" y="766" fill="#34d399" font-size="11">ONLINE</text>

    <!-- DATABASE -->
    <g transform="translate(295,735)">
      <rect width="34" height="34" rx="6" fill="none" stroke="#22d3ee"/>
      <ellipse cx="17" cy="10" rx="9" ry="3.5" fill="none" stroke="#22d3ee"/>
      <path d="M8,10 L8,24 A9,3.5 0 0,0 26,24 L26,10" fill="none" stroke="#22d3ee"/>
    </g>
    <text x="342" y="750" fill="#cbd5e1">DATABASE</text>
    <text x="342" y="766" fill="#34d399" font-size="11">CONNECTED</text>

    <!-- NETWORK -->
    <g transform="translate(548,735)">
      <circle cx="17" cy="17" r="16" fill="none" stroke="#22d3ee"/>
      <ellipse cx="17" cy="17" rx="16" ry="6.5" fill="none" stroke="#22d3ee" opacity="0.7"/>
      <line x1="1" y1="17" x2="33" y2="17" stroke="#22d3ee" opacity="0.7"/>
      <line x1="17" y1="1" x2="17" y2="33" stroke="#22d3ee" opacity="0.5"/>
    </g>
    <text x="595" y="750" fill="#cbd5e1">NETWORK</text>
    <text x="595" y="766" fill="#34d399" font-size="11">SECURE</text>

    <!-- AI CORE -->
    <g transform="translate(790,735)">
      <rect width="34" height="34" rx="6" fill="none" stroke="#22d3ee"/>
      <circle cx="17" cy="17" r="9" fill="none" stroke="#22d3ee"/>
      <circle cx="17" cy="17" r="3" fill="#22d3ee"/>
      <circle cx="17" cy="17" r="14" fill="none" stroke="#22d3ee" opacity="0.4">
        <animate attributeName="r" values="9;15;9" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0.6;0;0.6" dur="2s" repeatCount="indefinite"/>
      </circle>
    </g>
    <text x="837" y="750" fill="#cbd5e1">AI CORE</text>
    <text x="837" y="766" fill="#34d399" font-size="11">ACTIVE</text>

    <!-- STATUS -->
    <g transform="translate(1030,735)">
      <rect width="34" height="34" rx="6" fill="none" stroke="#22d3ee"/>
      <path d="M5,20 L11,20 L14,10 L19,28 L23,17 L26,20 L29,20" fill="none" stroke="#22d3ee" stroke-width="1.6" stroke-linejoin="round" stroke-linecap="round"/>
    </g>
    <text x="1077" y="750" fill="#cbd5e1">STATUS</text>
    <text x="1077" y="766" fill="#34d399" font-size="11">OPTIMAL</text>
  </g>

</svg>

<a href="https://alberto-portfolio-engenheiro-software.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=vercel&logoColor=white">
</a>
<a href="linkedin.com/in/alberto-henrique-1a9317365" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="https://www.instagram.com/alberto_henrique18/" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>
<a href="mailto:contato@email.com" target="_blank">
<img src="https://camo.githubusercontent.com/590734ce10f8c7025507e353487a86f7ebca5792ff3d282562bc111f91d4c10e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d476d61696c2d2532333333333f7374796c653d666f722d7468652d6261646765266c6f676f3d676d61696c266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&amp;logo=gmail&amp;logoColor=white">
</a>

---

# Sobre Mim: 

Prazer! Me chamo Alberto Henrique, sou estudante de Engenharia de Software, movido pela curiosidade e pelo desafio de transformar ideias em soluções reais por meio da tecnologia. Tenho grande interesse no desenvolvimento de sistemas, APIs, inteligência artificial e boas práticas de programação.

Estou em constante evolução, buscando aprofundar meus conhecimentos em desenvolvimento back-end, arquitetura de software, front-and e tecnologias modernas que impulsionam a transformação digital. Valorizo código limpo, aprendizado contínuo e a construção de soluções eficientes e escaláveis.

💡 Principais interesses:

-Desenvolvimento de Software;

-APIs e Engenharia de Dados;

-Inteligência Artificial;

-Desenvolvimento Back-and com Python;

-Arquitetura de Sistemas.

🎯 Objetivo: conquistar oportunidades que me permitam crescer profissionalmente, contribuir com projetos inovadores e gerar impacto positivo através da tecnologia.

---

# Minhas Skills: 

</div>

#### 🚀 Linguagens:
<div style="display: inline_block">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/Python-32547e?style=for-the-badge&logo=python&logoColor=white">
<!--<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"> -->
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

</div> 

#### ⚙️ Frameworks Back-end:

<div style="display: inline_block">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/DJANGO-004027?style=for-the-badge&logo=django&logoColor=white">
</div>

#### ⚙️ Frameworks Front-end:

<div style="display: inline_block">

<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/BOOTSTRAP-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/REACT-61DAFB?style=for-the-badge&logo=react&logoColor=white">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/ANGULAR-DD1100?style=for-the-badge&logo=angular&logoColor=white">
</div>


#### 🧪 Ferramentas & Ambiente:
<div style="display: inline_block">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/VSCODE-2F80ED?style=for-the-badge&logo=codeceptjs&logoColor=white">
</div> 


#### 🗄️ Banco de Dados:

<div style="display: inline_block">
<img align="center" alt="MySQL" height="" width="" src="https://img.shields.io/badge/MySQL-110595?style=for-the-badge&logo=mysql&logoColor=white">
<img align="center" alt="" height=""
width="" src="https://img.shields.io/badge/POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
<img align="center" alt="" height=""
width="" src="https://img.shields.io/badge/MONGODB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
</div> 


#### 🧩 Conhecimentos Complementares (Front-end):

<div style="display: inline_block">
<img align="center" alt="" height="" width="" src="https://img.shields.io/badge/HTML-a00909?style=for-the-badge&logo=html5&logoColor=white">
<img align="center" alt="CSS" height="" width="" src="https://img.shields.io/badge/CSS-002fff?style=for-the-badge&logo=css3&logoColor=white">
</div>
  
</div>  

  
</div>  
 
</br>
</div>  



