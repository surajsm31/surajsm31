# Hi there, I'm Suraj More! 👋

Welcome to my GitHub profile! I’m a passionate Full Stack Python Developer focused on building robust, scalable backend architectures and user-centric web applications. I specialize in designing and engineering high-performance Python backends, optimizing databases, and integrating custom 3D web interfaces.

<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 300" width="100%" height="300" style="background:#07070e; font-family:'Outfit', system-ui, -apple-system, sans-serif; border-radius:16px; border:1px solid rgba(139,92,246,0.25);">
    <defs>
      <!-- Grid Pattern -->
      <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(139, 92, 246, 0.08)" stroke-width="1"/>
      </pattern>
      <!-- Glow Gradients -->
      <radialGradient id="glow-primary" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#8b5cf6" stop-opacity="0.25"/>
        <stop offset="100%" stop-color="#8b5cf6" stop-opacity="0"/>
      </radialGradient>
      <radialGradient id="glow-secondary" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#06b6d4" stop-opacity="0.2"/>
        <stop offset="100%" stop-color="#06b6d4" stop-opacity="0"/>
      </radialGradient>
      <!-- Isometric Cube Fills -->
      <linearGradient id="cubeTop" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#a78bfa" stop-opacity="0.75"/>
        <stop offset="100%" stop-color="#7c3aed" stop-opacity="0.6"/>
      </linearGradient>
      <linearGradient id="cubeLeft" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#22d3ee" stop-opacity="0.65"/>
        <stop offset="100%" stop-color="#0891b2" stop-opacity="0.4"/>
      </linearGradient>
      <linearGradient id="cubeRight" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#f472b6" stop-opacity="0.65"/>
        <stop offset="100%" stop-color="#db2777" stop-opacity="0.4"/>
      </linearGradient>
    </defs>

    <style>
      @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500&amp;family=Outfit:wght@400;600;800&amp;display=swap');
      @keyframes float {
        0% { transform: translateY(0px) rotate(0deg); }
        50% { transform: translateY(-8px) rotate(0.5deg); }
        100% { transform: translateY(0px) rotate(0deg); }
      }
      @keyframes pulse {
        0%, 100% { opacity: 0.6; }
        50% { opacity: 1; }
      }
      @keyframes blink {
        0%, 100% { opacity: 0.4; }
        50% { opacity: 1; }
      }
      @keyframes orbit1 {
        0% { transform: rotate(0deg) translate(75px, 0px); }
        100% { transform: rotate(360deg) translate(75px, 0px); }
      }
      @keyframes orbit2 {
        0% { transform: rotate(180deg) translate(90px, 0px); }
        100% { transform: rotate(540deg) translate(90px, 0px); }
      }
      .floating {
        animation: float 6s ease-in-out infinite;
      }
      .pulse {
        animation: pulse 3s ease-in-out infinite;
      }
      .blinking-dot {
        animation: blink 2s infinite;
      }
      .orbit-dot-1 {
        animation: orbit1 8s linear infinite;
        transform-origin: 0px 0px;
      }
      .orbit-dot-2 {
        animation: orbit2 12s linear infinite;
        transform-origin: 0px 0px;
      }
      .text-title {
        font-size: 34px;
        font-weight: 800;
        fill: #ffffff;
        letter-spacing: -0.5px;
      }
      .text-subtitle {
        font-size: 12px;
        font-weight: 700;
        fill: #8b5cf6;
        letter-spacing: 1.5px;
      }
      .text-desc {
        font-size: 14px;
        fill: #94a3b8;
        font-weight: 400;
      }
      .terminal-box {
        fill: rgba(13, 13, 29, 0.7);
        stroke: rgba(139, 92, 246, 0.15);
        stroke-width: 1;
      }
    </style>

    <!-- Background Grid -->
    <rect width="100%" height="100%" fill="url(#grid)" />
    
    <!-- Background glows -->
    <circle cx="200" cy="150" r="180" fill="url(#glow-primary)" />
    <circle cx="630" cy="150" r="200" fill="url(#glow-secondary)" />

    <!-- Left Content Group -->
    <g transform="translate(60, 65)">
      <!-- Status Pill -->
      <g transform="translate(0, 0)">
        <rect width="250" height="24" rx="12" fill="rgba(6, 182, 212, 0.08)" stroke="rgba(6, 182, 212, 0.2)" stroke-width="1" />
        <circle class="blinking-dot" cx="16" cy="12" r="4" fill="#22c55e" />
        <text x="28" y="16" font-size="10.5" font-weight="600" fill="#06b6d4" letter-spacing="0.5px">AVAILABLE FOR OPPORTUNITIES</text>
      </g>

      <text class="text-title" x="0" y="55">Suraj More</text>
      <text class="text-subtitle" x="0" y="85">FULL STACK PYTHON DEVELOPER</text>
      
      <text class="text-desc" x="0" y="115">Designing high-performance APIs and scalable architectures.</text>
      <text class="text-desc" x="0" y="135">Specializing in database query tuning &amp; custom 3D web interfaces.</text>
      
      <!-- Terminal Block -->
      <g transform="translate(0, 160)">
        <rect class="terminal-box" width="320" height="40" rx="8" />
        <!-- Window Controls -->
        <circle cx="15" cy="20" r="3.5" fill="#ef4444" />
        <circle cx="27" cy="20" r="3.5" fill="#eab308" />
        <circle cx="39" cy="20" r="3.5" fill="#22c55e" />
        <text x="60" y="24" font-family="Fira Code, monospace" font-size="11.5" fill="#c084fc">npx suraj-more --info</text>
      </g>
    </g>

    <!-- Floating 3D Isometric Cube & Orbiting Particles -->
    <g class="floating" transform="translate(630, 140)">
      <!-- Drop Shadow -->
      <ellipse cx="0" cy="95" rx="60" ry="12" fill="rgba(0,0,0,0.4)" filter="blur(8px)" />

      <!-- Isometric Cube -->
      <g transform="scale(1.15)">
        <!-- Top Face -->
        <polygon points="0,-35 60,-15 0,5 -60,-15" fill="url(#cubeTop)" stroke="#a78bfa" stroke-width="1.2" />
        <!-- Left Face -->
        <polygon points="-60,-15 0,5 0,75 -60,55" fill="url(#cubeLeft)" stroke="#22d3ee" stroke-width="1.2" />
        <!-- Right Face -->
        <polygon points="0,5 60,-15 60,55 0,75" fill="url(#cubeRight)" stroke="#f472b6" stroke-width="1.2" />
        <!-- Glowing Inner Edges -->
        <line x1="0" y1="5" x2="0" y2="75" stroke="#ffffff" stroke-width="1.2" opacity="0.6" />
        <line x1="0" y1="5" x2="-60" y2="-15" stroke="#ffffff" stroke-width="0.8" opacity="0.4" />
        <line x1="0" y1="5" x2="60" y2="-15" stroke="#ffffff" stroke-width="0.8" opacity="0.4" />
      </g>

      <!-- Orbiting Particles -->
      <circle class="orbit-dot-1" cx="0" cy="0" r="4.5" fill="#06b6d4" style="filter: drop-shadow(0 0 4px #06b6d4);" />
      <circle class="orbit-dot-2" cx="0" cy="0" r="3.5" fill="#ec4899" style="filter: drop-shadow(0 0 3px #ec4899);" />
    </g>
  </svg>
</p>

---

## 🚀 About Me

- 💼 **Full Stack Python Developer** with 1+ year of hands-on experience designing and building scalable web applications.
- 🛠️ **Backend Specialist** in Django, Flask, FastAPI, RESTful APIs, JWT Authentication, and relational schema optimization.
- 📈 **Performance-Driven:** Proven record of database tuning resulting in **35%+ latency reduction** and page load optimization.
- 🎓 **Education:**  
  - 🖥️ **Master’s in Computer Application** | AIMCAR College, Akole (2023–2025) | CGPA: 6.79  
  - 🎓 **BSc in Computer Science** | SMBST College, Sangamner (2020–2023) | CGPA: 8.25
- 📍 Pune, Maharashtra, India
- 📧 **Email:** [surajsmore315@gmail.com](mailto:surajsmore315@gmail.com)  
- 📱 **Phone:** +91-9370909318  
- 💼 **LinkedIn:** [Suraj More](https://www.linkedin.com/in/suraj-more-0a6023253)  

---

## 💼 Professional Experience

### **Software Developer** | RSL Solutions Pvt. Ltd. _(Jan 2026 – July 2026)_
*Project: Fitness App - Fitness & Wellness Platform (Backend)*
- **Architected RESTful APIs** using Flask and FastAPI for user profiles, workout plans, and meal tracking; implemented secure JWT authentication.
- **Optimized PostgreSQL/MySQL schemas** using query tuning and lazy loading, successfully reducing API response times by **35%+**.
- **Integrated Cloudinary** for scalable cloud media storage and asset management workflows.
- **Enforced MVC architecture** and Git-based collaborative workflows across the engineering team to maintain clean version control.
- **Collaborated with React Native frontend** developers to design and deliver seamless, robust API contracts with structured logging and input validation.

### **Jr. Software Developer Intern** | Cravita Technologies India Pvt. Ltd. _(Oct 2024 – Apr 2025)_
*Project: Technical & Hiring Assistance System (Full Stack)*
- **Developed a dual-module Django platform** (Admin & User) enabling domain-based developer search for HR recruiters to streamline hiring.
- **Built mock assessment features** to automate technical assessment workflows.
- **Reduced page load latency by 20%** through advanced database query optimization and caching strategies.
- **Led a team of 3 developers** to successfully deliver the customer support system ahead of schedule.

---

## 🛠️ Technical Skills

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST%20API-005571?style=for-the-badge&logo=rest&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white"/>
</p>

- **Languages:** Python, JavaScript, HTML5, CSS3, SQL  
- **Frameworks:** Django, Flask, FastAPI, Bootstrap  
- **Tools & Platforms:** Git, GitHub, VS Code, PyCharm, Cloudinary, Windsurf  
- **APIs & Security:** RESTful APIs, JWT Authentication  
- **Databases:** PostgreSQL, MySQL, SQLite, Neon DB  
- **Concepts:** MVC Architecture, API Design, Query Optimization, Caching, Structured Logging, Input Validation  
- **Languages Known:** Hindi, Marathi, English

---

## 📂 Featured Projects

### 🏋️ Fitness App - Fitness & Wellness Platform  
*Flask, FastAPI, PostgreSQL, Neon DB, JWT, Cloudinary, Git*  
- Developed high-performance, modular REST APIs representing workout plans, meal logs, and user metadata.
- Implemented robust JWT authentication middleware and secure media storage integrations with Cloudinary.
- Designed complex, optimized schema relationships to minimize overhead and database CPU utilization.

### 🛠️ Technical and Hiring Assistance System  
*Python, Django, SQLite, MySQL, Caching, HTML, CSS*  
- Engineered a dual-module developer matching platform helping recruitment teams select domain-specific talent.
- Built interactive assessment modules enabling developers to take tests with scores updated in real time.
- Integrated server-side caching and optimized SQL queries to reduce view-rendering time by 20%.

---

## 📃 Certifications

- 🏅 **Edge - Python Full Stack Web Development** | *Fortune Cloud Technology*

---

## 📈 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=surajsm31&amp;show_icons=true&amp;theme=github_dark" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=surajsm31&amp;layout=compact&amp;theme=github_dark" height="150"/>
</p>

---

## 🤝 Let's Connect!

I'm always open to collaborating on innovative projects or discussing new ideas. Connect with me via:
- 💼 **LinkedIn:** [Suraj More](https://www.linkedin.com/in/suraj-more-0a6023253)
- 📧 **Email:** [surajsmore315@gmail.com](mailto:surajsmore315@gmail.com)
- 🖥️ **Portfolio:** [Suraj More Portfolio Website](https://github.com/surajsm31)

---
<!--
**surajsm31/surajsm31** is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
