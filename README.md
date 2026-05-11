<div align="center">

# 👋 Hey, I'm Nazeeh Fazal

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=28&duration=3000&color=00F7FF&center=true&vCenter=true&width=1000&lines=Creative+Technologist;AI+%26+Automation+Specialist;Game+Developer+%7C+Unity+Creator;UI%2FUX+Designer+%26+Brand+Visualizer;ICT+Engineer+%26+Digital+Innovator;Motion+Designer+%7C+Web+Developer;ERP+%7C+Systems+%7C+Creative+Engineering" alt="Typing SVG" />

<br/>

### 🚀 Creativity • Technology • AI • Systems • Game Dev • Digital Innovation

<img src="https://komarev.com/ghpvc/?username=YOURUSERNAME&label=Profile%20Views&color=blueviolet&style=for-the-badge" alt="Profile Views" />

</div>

---

## 💫 About Me

I'm a multidisciplinary **Creative Technologist** combining design, development, AI, automation, game development, IT systems, branding, and digital innovation.

I work across:

- 🎨 Branding & visual identity
- 🎬 Motion graphics & video editing
- 🤖 AI agents, prompting & automation
- 🎮 Unity game development
- 🌐 Web development & UI/UX
- ⚙️ ERP, IT systems & digital infrastructure
- 📱 Social media management & content systems

> I like building things that are visually strong, technically useful, and intelligently automated.

---

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>What I Do – Nazeeh Fazal</title>
<link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@600;700&family=Poppins:wght@400;500;600&display=swap" rel="stylesheet"/>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: #080c1a;
    font-family: 'Poppins', sans-serif;
    color: #e2e8f0;
    min-height: 100vh;
    padding: 60px 24px 80px;
  }

  .wrapper {
    max-width: 960px;
    margin: 0 auto;
  }

  /* ── Header ── */
  .header {
    text-align: center;
    margin-bottom: 56px;
  }

  .header h1 {
    font-family: 'Rajdhani', sans-serif;
    font-size: clamp(38px, 6vw, 64px);
    font-weight: 700;
    letter-spacing: 4px;
    color: #ffffff;
    line-height: 1;
    margin-bottom: 16px;
  }

  .brain-icon {
    font-size: clamp(36px, 5vw, 56px);
    margin-right: 10px;
    vertical-align: middle;
  }

  .header p {
    font-size: clamp(14px, 2vw, 18px);
    color: #94a3b8;
    max-width: 540px;
    margin: 0 auto 20px;
    line-height: 1.6;
  }

  .divider {
    width: 60px;
    height: 3px;
    margin: 0 auto;
    background: linear-gradient(90deg, #ff4ecd, #00e5ff);
    border-radius: 2px;
  }

  /* ── Grid ── */
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-bottom: 20px;
  }

  .grid-single {
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
  }

  @media (max-width: 640px) {
    .grid { grid-template-columns: 1fr; }
  }

  /* ── Card ── */
  .card {
    background: rgba(10, 16, 34, 0.85);
    border: 1px solid rgba(255,255,255,0.07);
    border-radius: 18px;
    padding: 28px 24px 32px;
    position: relative;
    overflow: hidden;
    transition: transform 0.25s ease, box-shadow 0.25s ease;
  }

  .card::before {
    content: '';
    position: absolute;
    inset: 0;
    border-radius: 18px;
    padding: 1px;
    background: var(--card-glow);
    -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
    -webkit-mask-composite: xor;
    mask-composite: exclude;
    opacity: 0.35;
    pointer-events: none;
  }

  .card:hover {
    transform: translateY(-4px);
    box-shadow: 0 16px 48px rgba(0,0,0,0.5);
  }

  .card-header {
    display: flex;
    align-items: center;
    gap: 16px;
    margin-bottom: 20px;
  }

  .icon-circle {
    width: 54px;
    height: 54px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 26px;
    flex-shrink: 0;
    background: var(--icon-bg);
  }

  .card-title {
    font-family: 'Rajdhani', sans-serif;
    font-size: 20px;
    font-weight: 700;
    letter-spacing: 2px;
    color: var(--accent);
    text-transform: uppercase;
    line-height: 1.2;
  }

  .title-line {
    width: 36px;
    height: 2px;
    background: var(--accent);
    border-radius: 2px;
    margin-top: 6px;
    opacity: 0.7;
  }

  /* ── Skill Grid ── */
  .skills {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px 10px;
  }

  .skills.wide {
    grid-template-columns: repeat(6, 1fr);
  }

  .skill-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 8px;
  }

  .skill-icon {
    width: 54px;
    height: 54px;
    border-radius: 10px;
    border: 1px solid rgba(255,255,255,0.08);
    background: rgba(255,255,255,0.04);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 22px;
    color: var(--accent);
  }

  .skill-label {
    font-size: 12px;
    color: #94a3b8;
    line-height: 1.3;
  }

  /* ── Color themes ── */
  .pink  { --accent: #ff4ecd; --icon-bg: rgba(255,78,205,0.15); --card-glow: linear-gradient(135deg, #ff4ecd, transparent); }
  .cyan  { --accent: #00e5ff; --icon-bg: rgba(0,229,255,0.12);  --card-glow: linear-gradient(135deg, #00e5ff, transparent); }
  .blue  { --accent: #3b82f6; --icon-bg: rgba(59,130,246,0.15); --card-glow: linear-gradient(135deg, #3b82f6, transparent); }
  .green { --accent: #7fff4e; --icon-bg: rgba(127,255,78,0.12); --card-glow: linear-gradient(135deg, #7fff4e, transparent); }
  .gold  { --accent: #ffd700; --icon-bg: rgba(255,215,0,0.12);  --card-glow: linear-gradient(135deg, #ffd700, transparent); }

  /* ── Separator between rows ── */
  .row-gap { margin-bottom: 20px; }

  /* ── SVG icons (inline lightweight) ── */
  svg.si { width: 26px; height: 26px; fill: none; stroke: currentColor; stroke-width: 1.6; stroke-linecap: round; stroke-linejoin: round; }
</style>
</head>
<body>
<div class="wrapper">

  <!-- Header -->
  <div class="header">
    <h1><span class="brain-icon">🧠</span> WHAT I DO</h1>
    <p>A fusion of creativity, technology, and systems to build<br/>digital experiences that make an impact.</p>
    <div class="divider"></div>
  </div>

  <!-- Row 1: Creative + AI -->
  <div class="grid row-gap">

    <!-- Creative Technology -->
    <div class="card pink">
      <div class="card-header">
        <div class="icon-circle">
          <svg class="si" viewBox="0 0 24 24"><path d="M12 19l7-7-3.5-3.5M5 19l7-7M9.5 5.5L13 9"/><circle cx="5.5" cy="18.5" r="1.5"/><circle cx="18.5" cy="5.5" r="1.5"/></svg>
        </div>
        <div>
          <div class="card-title">Creative Technology</div>
          <div class="title-line"></div>
        </div>
      </div>
      <div class="skills">
        <div class="skill-item">
          <div class="skill-icon">🎨</div>
          <span class="skill-label">Branding &amp; Visual Identity</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🎞️</div>
          <span class="skill-label">Motion Graphics</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🎬</div>
          <span class="skill-label">Video Editing</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">📱</div>
          <span class="skill-label">Social Media Content</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🖥️</div>
          <span class="skill-label">UI/UX Design</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🧊</div>
          <span class="skill-label">2D &amp; 3D Visual Design</span>
        </div>
      </div>
    </div>

    <!-- AI & Automation -->
    <div class="card cyan">
      <div class="card-header">
        <div class="icon-circle">
          <svg class="si" viewBox="0 0 24 24"><rect x="3" y="8" width="18" height="10" rx="2"/><path d="M8 8V6a4 4 0 018 0v2"/><circle cx="12" cy="13" r="2"/><path d="M12 11v-1M12 15v1M9.17 11.17l-.7-.7M15.53 16.53l-.7-.7M8 13H7M17 13h-1M9.17 14.83l-.7.7M15.53 11.47l-.7.7"/></svg>
        </div>
        <div>
          <div class="card-title">AI &amp; Automation</div>
          <div class="title-line"></div>
        </div>
      </div>
      <div class="skills">
        <div class="skill-item">
          <div class="skill-icon">⌨️</div>
          <span class="skill-label">AI Prompt Engineering</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🤖</div>
          <span class="skill-label">AI Agents</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">⚡</div>
          <span class="skill-label">Workflow Automation</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">💻</div>
          <span class="skill-label">AI-Assisted Development</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🎵</div>
          <span class="skill-label">Vibe Coding</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🧠</div>
          <span class="skill-label">AI Content Systems</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Row 2: Web + Game -->
  <div class="grid row-gap">

    <!-- Web & Digital -->
    <div class="card blue">
      <div class="card-header">
        <div class="icon-circle">
          <svg class="si" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M3.6 9h16.8M3.6 15h16.8M12 3a15 15 0 010 18M12 3a15 15 0 000 18"/></svg>
        </div>
        <div>
          <div class="card-title">Web &amp; Digital</div>
          <div class="title-line"></div>
        </div>
      </div>
      <div class="skills">
        <div class="skill-item">
          <div class="skill-icon">🖥️</div>
          <span class="skill-label">Website Development</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🅆</div>
          <span class="skill-label">WordPress / Wix / Elementor</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">📄</div>
          <span class="skill-label">Landing Pages</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🛒</div>
          <span class="skill-label">E-commerce UI</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">📊</div>
          <span class="skill-label">ERP UI Optimization</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🔗</div>
          <span class="skill-label">Digital Platforms</span>
        </div>
      </div>
    </div>

    <!-- Game Development -->
    <div class="card green">
      <div class="card-header">
        <div class="icon-circle">
          <svg class="si" viewBox="0 0 24 24"><rect x="2" y="7" width="20" height="13" rx="3"/><path d="M8 13h3m-1.5-1.5v3M17 13h.01M15 13h.01"/></svg>
        </div>
        <div>
          <div class="card-title">Game Development</div>
          <div class="title-line"></div>
        </div>
      </div>
      <div class="skills">
        <div class="skill-item">
          <div class="skill-icon">🎮</div>
          <span class="skill-label">Unity Development</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">⚔️</div>
          <span class="skill-label">Gameplay Systems</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🖼️</div>
          <span class="skill-label">Game UI</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🗺️</div>
          <span class="skill-label">Level Design</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🧊</div>
          <span class="skill-label">3D Assets</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🕹️</div>
          <span class="skill-label">Interactive Experiences</span>
        </div>
      </div>
    </div>
  </div>

  <!-- Row 3: IT & Systems (full width) -->
  <div class="grid-single">
    <div class="card gold">
      <div class="card-header">
        <div class="icon-circle">
          <svg class="si" viewBox="0 0 24 24"><path d="M12 15a3 3 0 100-6 3 3 0 000 6z"/><path d="M19.4 15a1.65 1.65 0 00.33 1.82l.06.06a2 2 0 010 2.83 2 2 0 01-2.83 0l-.06-.06a1.65 1.65 0 00-1.82-.33 1.65 1.65 0 00-1 1.51V21a2 2 0 01-4 0v-.09A1.65 1.65 0 009 19.4a1.65 1.65 0 00-1.82.33l-.06.06a2 2 0 01-2.83-2.83l.06-.06A1.65 1.65 0 004.68 15a1.65 1.65 0 00-1.51-1H3a2 2 0 010-4h.09A1.65 1.65 0 004.6 9a1.65 1.65 0 00-.33-1.82l-.06-.06a2 2 0 012.83-2.83l.06.06A1.65 1.65 0 009 4.68a1.65 1.65 0 001-1.51V3a2 2 0 014 0v.09a1.65 1.65 0 001 1.51 1.65 1.65 0 001.82-.33l.06-.06a2 2 0 012.83 2.83l-.06.06A1.65 1.65 0 0019.4 9a1.65 1.65 0 001.51 1H21a2 2 0 010 4h-.09a1.65 1.65 0 00-1.51 1z"/></svg>
        </div>
        <div>
          <div class="card-title">IT &amp; Systems</div>
          <div class="title-line"></div>
        </div>
      </div>
      <div class="skills wide">
        <div class="skill-item">
          <div class="skill-icon">🖥️</div>
          <span class="skill-label">ICT Operations</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🅶</div>
          <span class="skill-label">Google Workspace Admin</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🎧</div>
          <span class="skill-label">Technical Support</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🌐</div>
          <span class="skill-label">Networking</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🔒</div>
          <span class="skill-label">Security Systems</span>
        </div>
        <div class="skill-item">
          <div class="skill-icon">🗄️</div>
          <span class="skill-label">Database Management</span>
        </div>
      </div>
    </div>
  </div>

</div>
</body>
</html>

## 🤖 AI Tools & Platforms

<p align="center">
  <img src="https://img.shields.io/badge/ChatGPT-00A67E?style=for-the-badge&logo=openai&logoColor=white" alt="ChatGPT"/>
  <img src="https://img.shields.io/badge/Claude_AI-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude AI"/>
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/AI_Agents-8A2BE2?style=for-the-badge" alt="AI Agents"/>
  <img src="https://img.shields.io/badge/Automation-FF6B00?style=for-the-badge" alt="Automation"/>
  <img src="https://img.shields.io/badge/Prompt_Engineering-00C2CB?style=for-the-badge" alt="Prompt Engineering"/>
</p>

---

## 🎮 Game Development

<p align="center">
  <img src="https://skillicons.dev/icons?i=unity,cs,blender" alt="Game Dev Icons"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#"/>
  <img src="https://img.shields.io/badge/Game_Design-FF4C29?style=for-the-badge" alt="Game Design"/>
  <img src="https://img.shields.io/badge/Level_Design-00C2CB?style=for-the-badge" alt="Level Design"/>
  <img src="https://img.shields.io/badge/Interactive_Experiences-7952B3?style=for-the-badge" alt="Interactive Experiences"/>
</p>

**🎯 Game Dev Skills:**
- Unity game development
- Gameplay systems
- Game UI design
- Level design
- 3D visualization
- Game assets & environments
- Interactive experiences
- Rapid prototyping

---

## 🌐 Web Development & Platforms

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,php,wordpress,mysql" alt="Web Dev Icons"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress"/>
  <img src="https://img.shields.io/badge/Elementor-92003B?style=for-the-badge&logo=elementor&logoColor=white" alt="Elementor"/>
  <img src="https://img.shields.io/badge/Wix-000000?style=for-the-badge&logo=wix&logoColor=white" alt="Wix"/>
  <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white" alt="Odoo"/>
  <img src="https://img.shields.io/badge/Google_Workspace-4285F4?style=for-the-badge&logo=googleworkspace&logoColor=white" alt="Google Workspace"/>
</p>

**💻 Web Work:**
- WordPress & Wix websites
- Elementor customization
- Landing pages
- E-commerce UI/UX
- ERP interface optimization
- Responsive UI development

---

## 🎨 Creative Design & Media

<p align="center">
  <img src="https://skillicons.dev/icons?i=ps,ai,ae,pr,blender" alt="Creative Tools Icons"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white" alt="Photoshop"/>
  <img src="https://img.shields.io/badge/Illustrator-FF9A00?style=for-the-badge&logo=adobeillustrator&logoColor=white" alt="Illustrator"/>
  <img src="https://img.shields.io/badge/After_Effects-9999FF?style=for-the-badge&logo=adobeaftereffects&logoColor=white" alt="After Effects"/>
  <img src="https://img.shields.io/badge/Premiere_Pro-9999FF?style=for-the-badge&logo=adobepremierepro&logoColor=white" alt="Premiere Pro"/>
  <img src="https://img.shields.io/badge/InDesign-FF3366?style=for-the-badge&logo=adobeindesign&logoColor=white" alt="InDesign"/>
  <img src="https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white" alt="Blender"/>
  <img src="https://img.shields.io/badge/CorelDRAW-46A247?style=for-the-badge" alt="CorelDRAW"/>
</p>

**🎬 Creative Work:**
- Brand identity & logo design
- Motion graphics
- Video editing
- 2D / 3D animation
- Social media creatives
- Visual storytelling
- Marketing assets
- Posters, brochures & digital campaigns

---

## 🛠️ Development Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,python,php,cs,dotnet,mysql,java" alt="Dev Stack Icons"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/ReactJS-20232A?style=for-the-badge&logo=react" alt="React"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#"/>
  <img src="https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=.net&logoColor=white" alt="ASP.NET"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
</p>

---

## ⚙️ IT, Systems & Infrastructure

<p align="center">
  <img src="https://img.shields.io/badge/ICT_Operations-0A66C2?style=for-the-badge" alt="ICT Operations"/>
  <img src="https://img.shields.io/badge/System_Admin-333333?style=for-the-badge" alt="System Admin"/>
  <img src="https://img.shields.io/badge/ERP_Support-714B67?style=for-the-badge" alt="ERP Support"/>
  <img src="https://img.shields.io/badge/Database_Management-4479A1?style=for-the-badge" alt="Database Management"/>
  <img src="https://img.shields.io/badge/Network_Config-008080?style=for-the-badge" alt="Network Config"/>
  <img src="https://img.shields.io/badge/CCTV_Systems-222222?style=for-the-badge" alt="CCTV Systems"/>
  <img src="https://img.shields.io/badge/Device_Security-B00020?style=for-the-badge" alt="Device Security"/>
</p>

**Systems:**
- ICT Operations
- ERP Support
- Google Workspace Administration
- System Administration
- Database Management
- Technical Support
- Network Configuration
- CCTV Systems
- Device Security
- Access Management
- Workflow Automation

---

## 📱 Social Media & Digital Content

<p align="center">
  <img src="https://img.shields.io/badge/Social_Media_Management-E4405F?style=for-the-badge" alt="Social Media"/>
  <img src="https://img.shields.io/badge/Content_Strategy-FF6F00?style=for-the-badge" alt="Content Strategy"/>
  <img src="https://img.shields.io/badge/Digital_Marketing-4285F4?style=for-the-badge" alt="Digital Marketing"/>
  <img src="https://img.shields.io/badge/Brand_Storytelling-8A2BE2?style=for-the-badge" alt="Brand Storytelling"/>
  <img src="https://img.shields.io/badge/Creative_Campaigns-00C2CB?style=for-the-badge" alt="Creative Campaigns"/>
</p>

**📌 Social Media Work:**
- Content planning & campaign design
- Social media creatives
- Short-form video content
- Brand consistency
- Digital marketing assets
- AI-assisted captions and content ideas
- Engagement-focused visual storytelling

---

## 🚀 Project Areas

| 🤖 AI Projects | 🎨 Creative Projects | 🌐 Web Projects |
|---|---|---|
| AI Agents | Brand Identity Systems | WordPress Websites |
| AI Automation Workflows | Motion Graphics Campaigns | Wix Websites |
| Prompt-Based Content Systems | Social Media Design Packs | Elementor Landing Pages |
| AI-Assisted Coding | Promotional Videos | E-commerce UI/UX |
| AI Productivity Pipelines | 3D Visualizations | ERP Interface Enhancements |

| 🎮 Game Projects | ⚙️ IT Projects |
|---|---|
| Unity Game Prototypes | Google Workspace Setup |
| Game UI Concepts | ERP Workflow Improvements |
| Level Design Experiments | Website Infrastructure |
| Interactive 3D Experiences | Database Management |
| Gameplay Mechanics | Automation for Daily Operations |

---

## 🧩 My Digital Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=ps,ai,ae,pr,blender,unity,cs,html,css,js,react,python,php,mysql,wordpress" alt="Digital Toolkit"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ChatGPT-00A67E?style=flat-square&logo=openai&logoColor=white" alt="ChatGPT"/>
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude"/>
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/>
  <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white" alt="Photoshop"/>
  <img src="https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white" alt="Illustrator"/>
  <img src="https://img.shields.io/badge/After_Effects-9999FF?style=flat-square&logo=adobeaftereffects&logoColor=white" alt="After Effects"/>
  <img src="https://img.shields.io/badge/Premiere_Pro-9999FF?style=flat-square&logo=adobepremierepro&logoColor=white" alt="Premiere Pro"/>
  <img src="https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=blender&logoColor=white" alt="Blender"/>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity"/>
  <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress"/>
  <img src="https://img.shields.io/badge/Elementor-92003B?style=flat-square&logo=elementor&logoColor=white" alt="Elementor"/>
  <img src="https://img.shields.io/badge/Wix-000000?style=flat-square&logo=wix&logoColor=white" alt="Wix"/>
  <img src="https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white" alt="Odoo"/>
</p>

---

<div align="center">

⚡ **Building the future through Creativity + Systems + AI + Game Development**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=120&section=footer" alt="Footer"/>

</div>
