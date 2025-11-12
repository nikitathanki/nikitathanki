<!-- =======================================================
      ✨ Nikita Thanki | Animated • Colorful • Modern ✨
======================================================= -->

<p align="center">
  <img src="assets/banner.svg" alt="Nikita Thanki - Animated Banner" width="100%"/>
<!-- assets/banner.svg - Vibrant animated gradient banner for Nikita -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1400 300" preserveAspectRatio="xMidYMid slice">
  <defs>
    <linearGradient id="g" x1="0" x2="1">
      <stop offset="0" stop-color="#ff6b6b">
        <animate attributeName="stop-color" values="#ff6b6b;#f39c12;#6a11cb;#1dd1a1;#ff6b6b" dur="10s" repeatCount="indefinite"/>
      </stop>
      <stop offset="1" stop-color="#6a11cb">
        <animate attributeName="stop-color" values="#6a11cb;#1dd1a1;#ff6b6b;#f39c12;#6a11cb" dur="10s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <filter id="softblur">
      <feGaussianBlur stdDeviation="14"/>
    </filter>
  </defs>

  <rect width="1400" height="300" fill="url(#g)"/>

  <!-- floating soft shapes -->
  <g opacity="0.14" filter="url(#softblur)">
    <circle cx="160" cy="70" r="80" fill="#ffffff"/>
    <circle cx="440" cy="200" r="120" fill="#ffffff"/>
    <rect x="980" y="40" rx="28" ry="28" width="300" height="170" fill="#ffffff"/>
  </g>

  <!-- dynamic ribbon -->
  <path d="M-200 200 C 120 60, 360 260, 700 120 C 1040 -20, 1260 200, 1700 120 L1700 300 L-200 300 Z"
        fill="rgba(255,255,255,0.06)">
    <animate attributeName="d" dur="12s" repeatCount="indefinite"
      values="
        M-200 200 C 120 60, 360 260, 700 120 C 1040 -20, 1260 200, 1700 120 L1700 300 L-200 300 Z;
        M-200 220 C 140 100, 420 160, 740 140 C 1060 120, 1240 240, 1700 160 L1700 300 L-200 300 Z;
        M-200 180 C 100 40, 340 200, 680 100 C 1020 0, 1240 220, 1700 120 L1700 300 L-200 300 Z;
        M-200 200 C 120 60, 360 260, 700 120 C 1040 -20, 1260 200, 1700 120 L1700 300 L-200 300 Z"/>
  </path>

  <!-- main text -->
  <text x="70" y="120" font-family="Inter,Segoe UI, Roboto, Arial" font-size="46" font-weight="700" fill="#ffffff">
    Nikita Thanki
  </text>
  <text x="70" y="160" font-family="Inter,Segoe UI, Roboto, Arial" font-size="20" fill="#ffffff" opacity="0.95">
    BCA Student • Aspiring Full Stack Developer • UI/UX Learner
  </text>

  <!-- projects card -->
  <g transform="translate(1060,40)" opacity="0.95">
    <rect x="0" y="0" rx="12" width="300" height="160" fill="rgba(255,255,255,0.06)"/>
    <text x="22" y="48" font-family="Inter, Arial" font-size="18" fill="#fff">Featured</text>
    <text x="22" y="76" font-family="Inter, Arial" font-size="12" fill="#fff" opacity="0.95">Crème Studio • Institute Management</text>
  </g>
</svg>
</p>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Playfair+Display&size=34&color=ffffff&center=true&vCenter=true&width=760&lines=Hi+There!+%F0%9F%91%8B+I'm+Nikita+Thanki;BCA+Student+%7C+Aspiring+Full+Stack+Developer;UI%2FUX+Enthusiast+%7C+Creative+Thinker" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZ21jdHl3YW53czYwZjZsZnlsc3N3ajJkN3M1b3ZyMzhqNm14eHcxcyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/qgQUggAC3Pfv687qPC/giphy.gif" width="140" alt="avatar gif"/>
</p>

<p align="center">
  <img alt="Status" src="https://img.shields.io/badge/Status-Open%20to%20Work-2db84c?style=for-the-badge" />
  <img alt="Location" src="https://img.shields.io/badge/Location-India-ffb86b?style=for-the-badge" />
  <img alt="Email" src="https://img.shields.io/badge/Email-thankinikita32%40gmail.com-7B61FF?style=for-the-badge&logo=gmail" />
  <img alt="License" src="https://img.shields.io/badge/License-MIT-ff6b6b?style=for-the-badge" />
</p>

---

## 💻 About me
I build modern, responsive web and desktop apps using ASP.NET, C#, and SQL Server — with polished UI and clear, maintainable code. I enjoy turning small ideas into complete systems that are both functional and beautiful.

> “Code with clarity. Design with intention.”

---

## 🧠 Technical skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,bootstrap,cs,dotnet,visualstudio,vscode,mysql,figma,github,git" alt="skills" />
</p>

| Category | Tools / Frameworks |
|---|---|
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Backend** | ASP.NET (Web Forms & MVC), C# |
| **Database** | SQL Server, MySQL |
| **Architecture** | 2-Tier (Desktop), 3-Tier (Web) |
| **UI Framework** | Guna.UI2 |
| **Version Control** | Git, GitHub |
| **Design Tools** | Figma, Canva, Photoshop |

---

## 🏫 Featured Projects

### 🎓 Institute Management System (Desktop App)
**Overview:** C#.NET (WinForms) + SQL Server app to manage admissions, staff, exams, fees.  
**Highlights:** 3-tier-ready design, role-based flows, CRUD, modern Guna UI.  
**Tech:** C# · WinForms · SQL Server · Visual Studio  
🔗 https://github.com/nikitathanki/INSTITUTEMANAGEMENT

### 💎 Crème Studio — Luxury E-commerce (Web)
**Overview:** ASP.NET Web Forms e-commerce demo with luxury UI and animations.  
**Highlights:** Product listing, wishlist, session cart, checkout, profile & orders.  
**Tech:** ASP.NET Web Forms · C# · SQL Server · HTML/CSS/JS  
🔗 https://github.com/nikitathanki/Cremestudio

---

## 🌱 Currently exploring
<img src="https://readme-typing-svg.demolab.com?font=Josefin+Sans&weight=600&size=18&pause=1400&color=ffd8a8&center=true&width=560&lines=ASP.NET+MVC+%26+Razor+Pages;Advanced+C%23+and+LINQ;UI%2FUX+Animations+%26+SVG;Database+Optimization" alt="currently learning" />

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nikitathanki&show_icons=true&theme=radical&count_private=true" alt="Nikita's GitHub stats" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nikitathanki&layout=compact&theme=radical" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nikitathanki&theme=radical" alt="GitHub streak" />
</p>

---

## 🤝 Connect with me

<p align="center">
  <a href="https://www.linkedin.com/in/nikita-thanki-543a7b397" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://www.instagram.com/thewordsofnikita" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-@thewordsofnikita-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  &nbsp;
  <a href="mailto:thankinikita32@gmail.com">
    <img src="https://img.shields.io/badge/Email-thankinikita32%40gmail.com-7B61FF?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
</p>

---

<p align="center">
  <sub>Made with care • Nikita Thanki</sub>
</p>
