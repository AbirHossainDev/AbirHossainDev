<svg width="1200" height="2500" viewBox="0 0 1200 2500"
     xmlns="http://www.w3.org/2000/svg">

  <defs>
    <!-- Background -->
    <linearGradient id="bg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#061b3d"/>
      <stop offset="45%" stop-color="#03142d"/>
      <stop offset="100%" stop-color="#000814"/>
    </linearGradient>

    <!-- Cards -->
    <linearGradient id="card" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0b274c"/>
      <stop offset="100%" stop-color="#06172f"/>
    </linearGradient>

    <!-- Gold -->
    <linearGradient id="gold" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ffd21f"/>
      <stop offset="50%" stop-color="#ffdf45"/>
      <stop offset="100%" stop-color="#f5b800"/>
    </linearGradient>

    <filter id="shadow">
      <feDropShadow dx="0" dy="8" stdDeviation="10"
                    flood-color="#000000" flood-opacity=".5"/>
    </filter>

    <style>
      .title{font-family:Arial,sans-serif;font-weight:700;fill:#fff}
      .text{font-family:Arial,sans-serif;fill:#d9e3ef}
      .small{font-family:Arial,sans-serif;fill:#aebdd0}
      .gold{fill:#ffd21f}
      .card{fill:url(#card);stroke:#284669;stroke-width:2}
    </style>
  </defs>

  <!-- ================================================= -->
  <!-- BACKGROUND -->
  <!-- ================================================= -->

  <rect width="1200" height="2500" fill="url(#bg)"/>

  <!-- Background decoration -->
  <g opacity=".15" stroke="#3970a8" fill="none">
    <path d="M0 200L250 0"/>
    <path d="M950 0L1200 250"/>
    <path d="M0 600L300 300"/>
    <path d="M900 500L1200 200"/>
    <path d="M0 1500L250 1250"/>
    <path d="M950 1400L1200 1150"/>
  </g>

  <!-- Dots -->
  <g fill="#ffd21f" opacity=".5">
    <circle cx="60" cy="80" r="4"/>
    <circle cx="90" cy="55" r="3"/>
    <circle cx="120" cy="90" r="2"/>
    <circle cx="1080" cy="100" r="3"/>
    <circle cx="1110" cy="70" r="2"/>
    <circle cx="1140" cy="120" r="4"/>
  </g>

  <!-- ================================================= -->
  <!-- HEADER -->
  <!-- ================================================= -->

  <rect x="35" y="35" width="1130" height="470"
        rx="30" class="card"/>

  <!-- Profile circle -->
  <circle cx="260" cy="270" r="190"
          fill="#061a36"
          stroke="#ffd21f"
          stroke-width="8"
          filter="url(#shadow)"/>

  <!-- Simple person portrait -->
  <g transform="translate(260 130)">

    <!-- Head -->
    <circle cx="0" cy="75" r="65" fill="#b87955"/>

    <!-- Hair -->
    <path d="M-62 65
             Q-55 0 5 5
             Q65 10 66 70
             Q40 45 15 50
             Q-20 55 -62 65Z"
          fill="#101820"/>

    <!-- Neck -->
    <rect x="-25" y="125" width="50" height="55"
          rx="15" fill="#a96849"/>

    <!-- Shirt -->
    <path d="M-95 180
             Q-55 145 0 160
             Q55 145 95 180
             L125 360
             L-125 360Z"
          fill="#f3f5f7"/>

    <!-- Suit -->
    <path d="M-90 180
             L-25 155
             L0 205
             L25 155
             L90 180
             L120 360
             L-120 360Z"
          fill="#182638"/>

    <!-- Tie -->
    <path d="M0 170 L-20 215 L0 270 L20 215Z"
          fill="#ffd21f"/>

    <!-- Face -->
    <circle cx="-23" cy="82" r="5" fill="#111"/>
    <circle cx="23" cy="82" r="5" fill="#111"/>
    <path d="M-20 112 Q0 125 20 112"
          fill="none" stroke="#3c2018" stroke-width="5"
          stroke-linecap="round"/>
  </g>

  <!-- Intro -->
  <text x="500" y="145" class="title" font-size="42">
    Hi 👋, I'm
  </text>

  <text x="500" y="215" class="title" font-size="68">
    Dev.
  </text>

  <text x="670" y="215" font-family="Arial"
        font-size="68" font-weight="700"
        fill="#ffd21f">
    Abir
  </text>

  <text x="500" y="270" class="text" font-size="28">
    I build things with
  </text>

  <text x="730" y="270" font-family="Arial"
        font-size="28" font-weight="700"
        fill="#ffd21f">
    JavaScript
  </text>

  <text x="500" y="310" class="text" font-size="28">
    React, and
  </text>

  <text x="700" y="310" font-family="Arial"
        font-size="28" font-weight="700"
        fill="#ffd21f">
    Node.js
  </text>

  <!-- Social buttons -->
  <rect x="500" y="355" width="180" height="58"
        rx="15" fill="#071a34"
        stroke="#38516f" stroke-width="2"/>

  <text x="525" y="393" font-size="24">🔵</text>
  <text x="565" y="393" class="text" font-size="21">
    Facebook
  </text>

  <rect x="700" y="355" width="160" height="58"
        rx="15" fill="#071a34"
        stroke="#38516f" stroke-width="2"/>

  <text x="725" y="393" font-size="24">✉️</text>
  <text x="765" y="393" class="text" font-size="21">
    Email
  </text>

  <rect x="880" y="355" width="160" height="58"
        rx="15" fill="#071a34"
        stroke="#38516f" stroke-width="2"/>

  <text x="905" y="393" font-size="24">⚫</text>
  <text x="945" y="393" class="text" font-size="21">
    GitHub
  </text>

  <!-- ================================================= -->
  <!-- ABOUT -->
  <!-- ================================================= -->

  <text x="55" y="570" class="title" font-size="38">
    👤 About Me
  </text>

  <line x1="55" y1="590" x2="1145" y2="590"
        stroke="#ffd21f" stroke-width="3"/>

  <text x="60" y="645" class="text" font-size="24">
    I'm a passionate full-stack developer who
  </text>

  <text x="60" y="680" class="text" font-size="24">
    enjoys building modern, high-performance
  </text>

  <text x="60" y="715" class="text" font-size="24">
    web applications. I love working with
  </text>

  <text x="60" y="750" class="text" font-size="24">
    JavaScript, React, and Node.js.
  </text>

  <text x="60" y="805" class="text" font-size="24">
    Currently, I'm focused on expanding my
  </text>

  <text x="60" y="840" class="text" font-size="24">
    knowledge and building exciting projects.
  </text>

  <text x="60" y="895" class="gold" font-size="24">
    🚀 Always learning. Always building.
  </text>

  <!-- Coding illustration -->
  <rect x="650" y="635" width="440" height="270"
        rx="25" fill="#020d1e"
        stroke="#29496d" stroke-width="3"/>

  <!-- Monitor -->
  <rect x="700" y="680" width="330" height="180"
        rx="12" fill="#071a32"
        stroke="#54708f" stroke-width="5"/>

  <rect x="720" y="700" width="290" height="140"
        fill="#020b17"/>

  <!-- Code -->
  <g font-family="monospace" font-size="18">
    <text x="735" y="730" fill="#ffd21f">
      const developer =
    </text>
    <text x="735" y="758" fill="#65d8ff">
      &quot;Abir&quot;;
    </text>
    <text x="735" y="786" fill="#a878ff">
      function build() {
    </text>
    <text x="735" y="814" fill="#63e68a">
      return &quot;awesome&quot;;
    </text>
  </g>

  <!-- Monitor stand -->
  <path d="M820 860 L900 860 L925 905
           L795 905Z" fill="#243a55"/>

  <!-- Desk -->
  <rect x="635" y="900" width="510" height="25"
        rx="10" fill="#344b65"/>

  <!-- Sitting developer -->
  <circle cx="790" cy="850" r="42" fill="#b87955"/>

  <path d="M750 840 Q760 795 805 805
           Q830 815 825 850
           Q800 830 750 840Z"
        fill="#111820"/>

  <path d="M755 895 Q790 875 830 900
           L890 1010 L735 1010Z"
        fill="#17283d"/>

  <!-- Arms -->
  <path d="M770 920 Q820 935 850 960"
        fill="none" stroke="#b87955"
        stroke-width="25" stroke-linecap="round"/>

  <!-- Chair -->
  <path d="M880 875
           Q960 850 1000 930
           L1000 1080
           L850 1080
           L850 930Z"
        fill="#102239"
        stroke="#3b5876" stroke-width="4"/>

  <!-- Keyboard -->
  <rect x="825" y="865" width="130" height="30"
        rx="6" fill="#536a82"/>

  <!-- ================================================= -->
  <!-- TECH STACK -->
  <!-- ================================================= -->

  <text x="55" y="1010" class="title" font-size="38">
    ⚙️ Tech Stack
  </text>

  <!-- Frontend -->
  <rect x="45" y="1040" width="345" height="260"
        rx="25" class="card"/>

  <text x="155" y="1085" class="gold"
        font-size="28" font-weight="700">
    Frontend
  </text>

  <text x="80" y="1150" font-size="50">🌐</text>
  <text x="80" y="1190" class="small" font-size="18">HTML5</text>

  <text x="190" y="1150" font-size="50">🎨</text>
  <text x="190" y="1190" class="small" font-size="18">CSS3</text>

  <text x="295" y="1150" font-size="50">JS</text>
  <text x="290" y="1190" class="small" font-size="18">JavaScript</text>

  <text x="125" y="1250" font-size="48">⚛️</text>
  <text x="120" y="1280" class="small" font-size="18">React</text>

  <text x="255" y="1250" font-size="48">🌊</text>
  <text x="245" y="1280" class="small" font-size="18">Tailwind</text>

  <!-- Backend -->
  <rect x="425" y="1040" width="345" height="260"
        rx="25" class="card"/>

  <text x="535" y="1085" class="gold"
        font-size="28" font-weight="700">
    Backend
  </text>

  <text x="465" y="1160" font-size="48">⬢</text>
  <text x="465" y="1200" class="small" font-size="18">Node.js</text>

  <text x="575" y="1160" font-size="42">Express</text>
  <text x="590" y="1200" class="small" font-size="18">Express</text>

  <text x="690" y="1160" font-size="45">🍃</text>
  <text x="675" y="1200" class="small" font-size="18">MongoDB</text>

  <!-- Tools -->
  <rect x="805" y="1040" width="345" height="260"
        rx="25" class="card"/>

  <text x="885" y="1085" class="gold"
        font-size="28" font-weight="700">
    Tools &amp; Others
  </text>

  <text x="840" y="1160" font-size="48">🔀</text>
  <text x="850" y="1200" class="small" font-size="18">Git</text>

  <text x="950" y="1160" font-size="48">💻</text>
  <text x="930" y="1200" class="small" font-size="18">VS Code</text>

  <text x="1060" y="1160" font-size="45">🟠</text>
  <text x="1035" y="1200" class="small" font-size="18">Postman</text>

  <!-- ================================================= -->
  <!-- GITHUB STATS -->
  <!-- ================================================= -->

  <text x="55" y="1370" class="title" font-size="38">
    📊 GitHub Stats
  </text>

  <!-- Stats card -->
  <rect x="45" y="1400" width="540" height="370"
        rx="25" class="card"/>

  <text x="75" y="1450" class="gold"
        font-size="27" font-weight="700">
    AbirHossainDev
  </text>

  <text x="75" y="1500" class="text" font-size="22">
    ⭐ Total Stars
  </text>

  <text x="470" y="1500" class="gold"
        font-size="22">72+</text>

  <text x="75" y="1540" class="text" font-size="22">
    📦 Repositories
  </text>

  <text x="470" y="1540" class="gold"
        font-size="22">35+</text>

  <text x="75" y="1580" class="text" font-size="22">
    👥 Followers
  </text>

  <text x="470" y="1580" class="gold"
        font-size="22">18+</text>

  <!-- Grade -->
  <circle cx="470" cy="1680" r="70"
          fill="#071b35"
          stroke="#ffd21f" stroke-width="7"/>

  <text x="435" y="1698" class="title"
        font-size="52">A+</text>

  <!-- Language card -->
  <rect x="615" y="1400" width="540" height="370"
        rx="25" class="card"/>

  <text x="650" y="1450" class="title"
        font-size="27">
    Most Used Languages
  </text>

  <!-- language bars -->
  <text x="650" y="1500" class="text" font-size="20">
    🟡 JavaScript
  </text>

  <rect x="650" y="1515" width="400" height="14"
        rx="7" fill="#1b3859"/>
  <rect x="650" y="1515" width="275" height="14"
        rx="7" fill="#ffd21f"/>

  <text x="1060" y="1528" class="small"
        font-size="18">68.5%</text>

  <text x="650" y="1570" class="text" font-size="20">
    🔵 TypeScript
  </text>

  <rect x="650" y="1585" width="400" height="14"
        rx="7" fill="#1b3859"/>
  <rect x="650" y="1585" width="63" height="14"
        rx="7" fill="#2684ff"/>

  <text x="1060" y="1598" class="small"
        font-size="18">15.7%</text>

  <text x="650" y="1640" class="text" font-size="20">
    🟣 CSS
  </text>

  <rect x="650" y="1655" width="400" height="14"
        rx="7" fill="#1b3859"/>
  <rect x="650" y="1655" width="28" height="14"
        rx="7" fill="#9b59d0"/>

  <text x="1060" y="1668" class="small"
        font-size="18">7.1%</text>

  <text x="650" y="1710" class="text" font-size="20">
    🟠 HTML
  </text>

  <rect x="650" y="1725" width="400" height="14"
        rx="7" fill="#1b3859"/>
  <rect x="650" y="1725" width="22" height="14"
        rx="7" fill="#ff7043"/>

  <text x="1060" y="1738" class="small"
        font-size="18">5.6%</text>

  <!-- ================================================= -->
  <!-- HIGHLIGHT NUMBERS -->
  <!-- ================================================= -->

  <rect x="45" y="1810" width="1110" height="145"
        rx="25" class="card"/>

  <text x="100" y="1870" font-size="35">👁️</text>
  <text x="145" y="1870" class="title" font-size="30">
    1.2K+
  </text>
  <text x="145" y="1905" class="small" font-size="18">
    Profile Views
  </text>

  <line x1="385" y1="1840" x2="385" y2="1925"
        stroke="#38516f"/>

  <text x="430" y="1870" font-size="35">📁</text>
  <text x="475" y="1870" class="title" font-size="30">
    35+
  </text>
  <text x="475" y="1905" class="small" font-size="18">
    Repositories
  </text>

  <line x1="665" y1="1840" x2="665" y2="1925"
        stroke="#38516f"/>

  <text x="710" y="1870" font-size="35">⭐</text>
  <text x="755" y="1870" class="title" font-size="30">
    72+
  </text>
  <text x="755" y="1905" class="small" font-size="18">
    Total Stars
  </text>

  <line x1="930" y1="1840" x2="930" y2="1925"
        stroke="#38516f"/>

  <text x="975" y="1870" font-size="35">🔗</text>
  <text x="1020" y="1870" class="title" font-size="30">
    28+
  </text>
  <text x="1020" y="1905" class="small" font-size="18">
    Contributions
  </text>

  <!-- ================================================= -->
  <!-- PROJECT -->
  <!-- ================================================= -->

  <text x="55" y="2030" class="title" font-size="38">
    🚀 Project Highlight
  </text>

  <rect x="45" y="2060" width="1110" height="250"
        rx="25" class="card"/>

  <!-- Website preview -->
  <rect x="75" y="2090" width="450" height="185"
        rx="12" fill="#e8f1dc"/>

  <rect x="75" y="2090" width="450" height="35"
        fill="#ffffff"/>

  <circle cx="100" cy="2107" r="6" fill="#ff5555"/>
  <circle cx="120" cy="2107" r="6" fill="#ffd21f"/>
  <circle cx="140" cy="2107" r="6" fill="#45c85a"/>

  <text x="160" y="2115"
        font-family="Arial"
        font-size="15"
        fill="#555">
    Nature's Platter
  </text>

  <!-- Hero -->
  <rect x="95" y="2145" width="410" height="80"
        rx="8" fill="#d5e7bd"/>

  <text x="195" y="2175"
        font-family="Arial"
        font-size="22"
        font-weight="700"
        fill="#23451e">
    Fresh, Healthy &amp;
  </text>

  <text x="220" y="2200"
        font-family="Arial"
        font-size="20"
        fill="#23451e">
    100% Natural
  </text>

  <!-- Product boxes -->
  <g fill="#ffffff" stroke="#b9cfa0">
    <rect x="95" y="2238" width="90" height="45" rx="6"/>
    <rect x="195" y="2238" width="90" height="45" rx="6"/>
    <rect x="295" y="2238" width="90" height="45" rx="6"/>
    <rect x="395" y="2238" width="90" height="45" rx="6"/>
  </g>

  <!-- Project info -->
  <text x="570" y="2130"
        font-family="Arial"
        font-size="32"
        font-weight="700"
        fill="#ffd21f">
    🌿 Nature's Platter
  </text>

  <text x="570" y="2170" class="text" font-size="21">
    A modern and responsive website focused on
  </text>

  <text x="570" y="2200" class="text" font-size="21">
    fresh, healthy, and natural products.
  </text>

  <text x="570" y="2250" class="gold" font-size="19">
    React   •   Tailwind CSS   •   Node.js   •   MongoDB
  </text>

  <rect x="570" y="2270" width="170" height="42"
        rx="12" fill="#071a34"
        stroke="#38516f"/>

  <text x="600" y="2298" class="text" font-size="17">
    GitHub Repo
  </text>

  <rect x="755" y="2270" width="170" height="42"
        rx="12" fill="#071a34"
        stroke="#38516f"/>

  <text x="780" y="2298" class="text" font-size="17">
    Live Demo
  </text>

  <!-- ================================================= -->
  <!-- CONNECT -->
  <!-- ================================================= -->

  <text x="55" y="2380" class="title" font-size="36">
    🤝 Let's Connect
  </text>

  <text x="55" y="2415" class="small" font-size="18">
    Always open to learning, collaborating and building
  </text>

  <text x="55" y="2442" class="small" font-size="18">
    amazing projects with other developers.
  </text>

  <text x="700" y="2415" class="text" font-size="19">
    📧 dev.abirhossain@gmail.com
  </text>

  <text x="700" y="2445" class="text" font-size="19">
    🔵 Facebook
  </text>

  <text x="700" y="2475" class="text" font-size="19">
    ⚫ AbirHossainDev
  </text>

  <!-- Footer -->
  <line x1="45" y1="2490" x2="1155" y2="2490"
        stroke="#ffd21f" stroke-width="3"/>

</svg>
