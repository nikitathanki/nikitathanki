<!-- ===========================
     README — Nikita Thanki
     Polished • Animated • Stable
     Paste directly into your README.md
   =========================== -->
 <?xml version="1.0" encoding="UTF-8"?>
<svg width="1200" height="360" viewBox="0 0 1200 360" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice">
  <defs>
    <linearGradient id="g1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#fdf6f0"/>
      <stop offset="30%" stop-color="#f3e5db"/>
      <stop offset="65%" stop-color="#f7e9e6"/>
      <stop offset="100%" stop-color="#fff7f6"/>
    </linearGradient>

    <linearGradient id="g2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#b76e79"/>
      <stop offset="50%" stop-color="#d4af37"/>
      <stop offset="100%" stop-color="#b76e79"/>
    </linearGradient>

    <filter id="soft" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="18" result="blur"/>
      <feBlend in="SourceGraphic" in2="blur" mode="normal"/>
    </filter>

    <mask id="fade">
      <rect width="100%" height="100%" fill="white"/>
      <linearGradient id="maskgrad" x1="0" x2="0" y1="0" y2="1">
        <stop offset="0" stop-color="white" stop-opacity="1"/>
        <stop offset="1" stop-color="white" stop-opacity="0.92"/>
      </linearGradient>
      <rect width="100%" height="100%" fill="url(#maskgrad)"/>
    </mask>

    <style><![CDATA[
      .title { font-family: 'Inter', 'Segoe UI', Roboto, system-ui, sans-serif; font-weight:700; fill:#3b2f2f; font-size:38px; }
      .subtitle { font-family: 'Inter', 'Segoe UI', Roboto, system-ui, sans-serif; font-weight:500; fill:#3b2f2f; font-size:18px; opacity:0.95; }
      .accent { fill: url(#g2); }
      .pill { fill: rgba(255,255,255,0.06); stroke: rgba(59,47,47,0.04); stroke-width:1; rx:14; ry:14; }
    ]]></style>
  </defs>

  <!-- background -->
  <rect width="100%" height="100%" fill="url(#g1)"/>

  <!-- animated gradient blobs -->
  <g opacity="0.95" filter="url(#soft)" mask="url(#fade)">
    <ellipse cx="220" cy="120" rx="260" ry="110" fill="url(#g2)">
      <animate attributeName="cx" values="180;240;200;180" dur="9s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="120;140;110;120" dur="11s" repeatCount="indefinite"/>
      <animate attributeName="rx" values="240;280;260;240" dur="13s" repeatCount="indefinite"/>
    </ellipse>

    <ellipse cx="920" cy="220" rx="320" ry="140" fill="#f3e5db" opacity="0.85">
      <animate attributeName="cx" values="900;940;920;900" dur="10s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="220;200;230;220" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="rx" values="300;340;320;300" dur="14s" repeatCount="indefinite"/>
    </ellipse>

    <ellipse cx="640" cy="80" rx="180" ry="80" fill="#fff2ee" opacity="0.95">
      <animate attributeName="cx" values="620;660;640;620" dur="8s" repeatCount="indefinite"/>
    </ellipse>
  </g>

  <!-- overlay content -->
  <g transform="translate(60,42)">
    <rect x="0" y="0" width="1080" height="276" class="pill"/>
    <text x="40" y="64" class="title">Hi, I'm Nikita Thanki</text>
    <text x="40" y="104" class="subtitle">BCA Student · Aspiring Full Stack Developer · UI/UX Enthusiast</text>

    <g transform="translate(40,128)">
      <rect x="0" y="0" width="220" height="40" rx="10" ry="10" style="fill:white;opacity:0.02"/>
      <text x="18" y="26" class="subtitle">ASP.NET • C# • SQL Server</text>
    </g>

    <g transform="translate(300,128)">
      <rect x="0" y="0" width="300" height="40" rx="10" ry="10" style="fill:white;opacity:0.02"/>
      <text x="18" y="26" class="subtitle">Web & Desktop Apps • 2-Tier & 3-Tier</text>
    </g>

    <g transform="translate(40,186)">
      <text x="0" y="24" class="subtitle">“Building logic, designing with purpose, and learning something new every day.”</text>
    </g>

    <!-- subtle rose-gold accent line -->
    <rect x="40" y="200" width="880" height="4" rx="2" fill="url(#g2)" opacity="0.9"/>
  </g>

  <!-- small corner logo circle -->
  <g transform="translate(1000,36)">
    <circle cx="0" cy="0" r="36" fill="#fff" opacity="0.9" />
    <circle cx="0" cy="0" r="30" class="accent" />
    <text x="-8" y="6" font-family="Inter,Segoe UI" font-size="18" font-weight="700" fill="#fff">NT</text>
  </g>
</svg>



<h1 align="center">Hi there 👋 I'm <strong>Nikita Thanki</strong></h1>
<h4 align="center">BCA Student · Aspiring Full Stack Developer · UI/UX Enthusiast</h4>

<p align="center">
  <!-- Typing animation (external but stable) -->
  <img src="https://readme-typing-svg.demolab.com?font=Inter&size=20&pause=800&color=B76E79&center=true&width=760&lines=Building+modern+and+responsive+applications;Designing+clean+and+scalable+systems;Learning+ASP.NET+MVC+and+advanced+C%23" alt="typing" />
</p>

<!-- Animated contribution visualization (primary) -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" alt="contribution-snake" style="max-width:640px;width:100%;border-radius:12px;box-shadow:0 8px 24px rgba(0,0,0,0.08)" />
</p>

<!-- Fallback: if the animated SVG can't load, this avatar will always work -->
<p align="center">
  <img src="https://github.com/nikitathanki.png" alt="Nikita Thanki — avatar" width="120" style="border-radius:50%;box-shadow:0 6px 20px rgba(183,110,121,0.12)" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=nikitathanki&color=b76e79" alt="profile views" />
  &nbsp;&nbsp;
  <a href="https://github.com/nikitathanki">
    <img alt="Most Used Languages" src="https://github-readme-stats.vercel.app/api/top-langs?username=nikitathanki&layout=compact&hide_border=true&langs_count=6" />
  </a>
</p>

---

## 👩‍💻 About Me
I’m a **BCA student** building modern and efficient web and desktop applications using **ASP.NET (Web Forms & MVC), SQL Server, HTML, CSS, JavaScript, and C#** (server-side). I enjoy clean architecture, maintainable code, and thoughtful UI.

> “Building logic, designing with purpose, and learning something new every day.”

---

## 🧠 Technical Skills

| Category         | Tools / Frameworks |
|------------------|--------------------|
| **Frontend**     | HTML, CSS, JavaScript, Bootstrap |
| **Backend**      | ASP.NET (Web Forms & MVC), C# |
| **Database**     | SQL Server, MySQL |
| **Architecture** | 2-Tier (Desktop), 3-Tier (Web) |
| **UI Framework** | Guna.UI2 (WinForms) |
| **IDE**          | Visual Studio 2019, Visual Studio Code |
| **Version Ctrl** | Git, GitHub |
| **Design Tools** | Figma (UI basics), Canva |

---

## 🏫 Projects — Key Work

### Institute Management System (2-Tier Desktop App)
**Overview:** Desktop app built with **C#.NET (Windows Forms)** and **SQL Server** for admissions, staff, exams, fees, and reports.  
**Highlights:** role-based login, CRUD, ADO.NET connectivity, polished UI (Guna.UI2).  
**Tech:** C#.NET | SQL Server | Visual Studio | Guna.UI2

### Crème Studio — E-Commerce Website (3-Tier Web App)
**Overview:** Luxury-themed e-commerce website using **ASP.NET Web Forms** with a 3-tier architecture (UI → Business Logic → Data Access).  
**Highlights:** product listing, wishlist, cart, checkout, user accounts, order history, animated rose-gold UI.  
**Tech:** ASP.NET Web Forms | C# (backend) | SQL Server | HTML | CSS | JavaScript | ADO.NET

---

## 🌱 Currently Learning
- ASP.NET MVC & Razor Pages  
- Advanced C# (LINQ, async/await, SOLID)  
- UI/UX workflows & accessibility  
- Database indexing & query optimization

---

## 📁 Projects
🔹 [Institute Management System](https://github.com/nikitathanki/INSTITUTEMANAGEMENT)  
🔹 [Crème Studio (E-Commerce Website)](https://github.com/nikitathanki/Cremestudio)  
  

## 🤝 Connect With Me
<p align="center">
  <a href="www.linkedin.com/in/nikita-thanki-543a7b397" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  
⭐ **Fun fact:** I love turning small ideas into full systems — structured, functional, and beautiful.  
💫 *“Code with clarity. Design with intention.”*
