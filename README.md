<div align="center">

<!-- Banner SVG Animado con tema Catppuccin -->
<svg width="100%" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="catppuccin-gradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#89b4fa;stop-opacity:1">
        <animate attributeName="stop-color" values="#89b4fa;#cba6f7;#f38ba8;#89b4fa" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="50%" style="stop-color:#cba6f7;stop-opacity:1">
        <animate attributeName="stop-color" values="#cba6f7;#f38ba8;#fab387;#cba6f7" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" style="stop-color:#f38ba8;stop-opacity:1">
        <animate attributeName="stop-color" values="#f38ba8;#fab387;#89b4fa;#f38ba8" dur="8s" repeatCount="indefinite" />
      </stop>
    </linearGradient>
    
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Fondo -->
  <rect width="100%" height="200" fill="#1e1e2e" rx="10"/>
  
  <!-- Partículas animadas -->
  <circle cx="10%" cy="50" r="3" fill="#89b4fa" opacity="0.6">
    <animate attributeName="cy" values="50;150;50" dur="4s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" repeatCount="indefinite" />
  </circle>
  <circle cx="30%" cy="120" r="2" fill="#cba6f7" opacity="0.6">
    <animate attributeName="cy" values="120;60;120" dur="5s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.6;1;0.6" dur="5s" repeatCount="indefinite" />
  </circle>
  <circle cx="70%" cy="80" r="2.5" fill="#f38ba8" opacity="0.6">
    <animate attributeName="cy" values="80;140;80" dur="4.5s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.6;1;0.6" dur="4.5s" repeatCount="indefinite" />
  </circle>
  <circle cx="90%" cy="140" r="3" fill="#fab387" opacity="0.6">
    <animate attributeName="cy" values="140;70;140" dur="6s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.6;1;0.6" dur="6s" repeatCount="indefinite" />
  </circle>
  
  <!-- Texto principal con gradiente -->
  <text x="50%" y="100" font-family="'Courier New', monospace" font-size="48" font-weight="bold" fill="url(#catppuccin-gradient)" text-anchor="middle" filter="url(#glow)">
    &lt;Alex Larin /&gt;
    <animate attributeName="opacity" values="1;0.7;1" dur="3s" repeatCount="indefinite" />
  </text>
  
  <!-- Subtítulo -->
  <text x="50%" y="130" font-family="'Courier New', monospace" font-size="18" fill="#cdd6f4" text-anchor="middle" opacity="0.8">
    Full Stack Web Developer | Software Engineer
  </text>
  
  <!-- Línea decorativa animada -->
  <line x1="20%" y1="160" x2="80%" y2="160" stroke="url(#catppuccin-gradient)" stroke-width="2" stroke-linecap="round">
    <animate attributeName="x1" values="20%;30%;20%" dur="4s" repeatCount="indefinite" />
    <animate attributeName="x2" values="80%;70%;80%" dur="4s" repeatCount="indefinite" />
  </line>
</svg>

<!-- Typing SVG -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=89B4FA&center=true&vCenter=true&multiline=false&repeat=true&width=600&lines=Construyendo+soluciones+escalables+%F0%9F%9A%80;Becado+Universidad+del+Atl%C3%A1ntico+%F0%9F%8E%93;Miembro+de+Presencia+Web+Santander+%F0%9F%92%BB;Estudiante+de+Ingenier%C3%ADa+Inform%C3%A1tica+%F0%9F%8C%9F" alt="Typing SVG" />
</p>

</div>

---

## <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"> Sobre Mí

<img align="right" alt="Coding" width="400" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif">

\`\`\`javascript
const alexLarin = {
    name: "Alex Larin",
    role: "Full Stack Web Developer",
    education: {
        university: "Universidad del Atlántico",
        degree: "Ingeniería Informática",
        scholarship: "Becado FUNIBER"
    },
    currentWork: {
        organization: "Presencia Web Santander",
        department: "Desarrollo Web",
        role: "Developer Team Member"
    },
    code: [
        "JavaScript", "TypeScript", "Python", "AppScript"
    ],
    technologies: {
        frontEnd: {
            js: ["React", "Next.js", "Vue"],
            cms: ["WordPress"]
        },
        backEnd: {
            js: ["Node.js", "Express", "NestJS"],
            python: ["FastAPI", "Django"]
        },
        databases: [
            "MongoDB", "PostgreSQL", "MySQL", "Redis"
        ],
        devOps: [
            "Docker", "Kubernetes", "Jenkins",
            "GitLab CI/CD", "GitHub Actions"
        ],
        cloud: [
            "Google Cloud Platform", "AWS", "Vercel"
        ],
        ai: ["Ollama", "LangChain", "OpenAI"],
        testing: ["Jest", "Pytest", "Cypress"],
        tools: ["Git", "Linux", "VS Code", "Postman"]
    },
    architecture: [
        "Microservices", "RESTful APIs", 
        "GraphQL", "Serverless"
    ],
    currentFocus: "Construyendo aplicaciones web escalables y modernas",
    funFact: "El mejor código es el que no necesita comentarios... pero siempre los escribo 😄"
};
\`\`\`

<br clear="right"/>

---

## 🛠️ Tech Stack

<div align="center">

### Frontend Development
<p>
  <img src="https://img.shields.io/badge/TypeScript-1e1e2e?style=for-the-badge&logo=typescript&logoColor=89b4fa" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-1e1e2e?style=for-the-badge&logo=javascript&logoColor=f9e2af" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/React-1e1e2e?style=for-the-badge&logo=react&logoColor=89b4fa" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-1e1e2e?style=for-the-badge&logo=next.js&logoColor=cdd6f4" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Vue.js-1e1e2e?style=for-the-badge&logo=vue.js&logoColor=a6e3a1" alt="Vue"/>
  <img src="https://img.shields.io/badge/Tailwind-1e1e2e?style=for-the-badge&logo=tailwind-css&logoColor=89dceb" alt="Tailwind"/>
</p>

### Backend Development
<p>
  <img src="https://img.shields.io/badge/Node.js-1e1e2e?style=for-the-badge&logo=node.js&logoColor=a6e3a1" alt="Node.js"/>
  <img src="https://img.shields.io/badge/NestJS-1e1e2e?style=for-the-badge&logo=nestjs&logoColor=f38ba8" alt="NestJS"/>
  <img src="https://img.shields.io/badge/Express-1e1e2e?style=for-the-badge&logo=express&logoColor=cdd6f4" alt="Express"/>
  <img src="https://img.shields.io/badge/Python-1e1e2e?style=for-the-badge&logo=python&logoColor=f9e2af" alt="Python"/>
  <img src="https://img.shields.io/badge/FastAPI-1e1e2e?style=for-the-badge&logo=fastapi&logoColor=89dceb" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/AppScript-1e1e2e?style=for-the-badge&logo=google&logoColor=89b4fa" alt="AppScript"/>
</p>

### Database & Cache
<p>
  <img src="https://img.shields.io/badge/MongoDB-1e1e2e?style=for-the-badge&logo=mongodb&logoColor=a6e3a1" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/PostgreSQL-1e1e2e?style=for-the-badge&logo=postgresql&logoColor=89b4fa" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MySQL-1e1e2e?style=for-the-badge&logo=mysql&logoColor=89dceb" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Redis-1e1e2e?style=for-the-badge&logo=redis&logoColor=f38ba8" alt="Redis"/>
</p>

### DevOps & Cloud
<p>
  <img src="https://img.shields.io/badge/Docker-1e1e2e?style=for-the-badge&logo=docker&logoColor=89b4fa" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-1e1e2e?style=for-the-badge&logo=kubernetes&logoColor=89b4fa" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Jenkins-1e1e2e?style=for-the-badge&logo=jenkins&logoColor=f38ba8" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/GitLab_CI-1e1e2e?style=for-the-badge&logo=gitlab&logoColor=fab387" alt="GitLab CI"/>
  <img src="https://img.shields.io/badge/Google_Cloud-1e1e2e?style=for-the-badge&logo=google-cloud&logoColor=89b4fa" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/Linux-1e1e2e?style=for-the-badge&logo=linux&logoColor=f9e2af" alt="Linux"/>
</p>

### Testing & Tools
<p>
  <img src="https://img.shields.io/badge/Jest-1e1e2e?style=for-the-badge&logo=jest&logoColor=f38ba8" alt="Jest"/>
  <img src="https://img.shields.io/badge/Git-1e1e2e?style=for-the-badge&logo=git&logoColor=f38ba8" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-1e1e2e?style=for-the-badge&logo=github&logoColor=cdd6f4" alt="GitHub"/>
  <img src="https://img.shields.io/badge/GitLab-1e1e2e?style=for-the-badge&logo=gitlab&logoColor=fab387" alt="GitLab"/>
  <img src="https://img.shields.io/badge/VS_Code-1e1e2e?style=for-the-badge&logo=visual-studio-code&logoColor=89b4fa" alt="VS Code"/>
  <img src="https://img.shields.io/badge/Postman-1e1e2e?style=for-the-badge&logo=postman&logoColor=fab387" alt="Postman"/>
</p>

### CMS & AI
<p>
  <img src="https://img.shields.io/badge/WordPress-1e1e2e?style=for-the-badge&logo=wordpress&logoColor=89b4fa" alt="WordPress"/>
  <img src="https://img.shields.io/badge/Ollama-1e1e2e?style=for-the-badge&logo=ollama&logoColor=cba6f7" alt="Ollama"/>
  <img src="https://img.shields.io/badge/OpenAI-1e1e2e?style=for-the-badge&logo=openai&logoColor=a6e3a1" alt="OpenAI"/>
</p>

</div>

---

## 📊 GitHub Stats

<div align="center">
  
<img width="49%" src="https://github-readme-stats.vercel.app/api?username=TU_USUARIO&show_icons=true&theme=catppuccin_mocha&hide_border=true&bg_color=1e1e2e&title_color=89b4fa&icon_color=cba6f7&text_color=cdd6f4" alt="GitHub Stats" />

<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=TU_USUARIO&theme=catppuccin-mocha&hide_border=true&background=1e1e2e&ring=89b4fa&fire=f38ba8&currStreakLabel=cdd6f4" alt="GitHub Streak" />

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TU_USUARIO&layout=compact&theme=catppuccin_mocha&hide_border=true&bg_color=1e1e2e&title_color=89b4fa&text_color=cdd6f4&langs_count=8" alt="Top Languages" />

<img width="49%" src="https://github-readme-activity-graph.vercel.app/graph?username=TU_USUARIO&theme=catppuccin-mocha&hide_border=true&bg_color=1e1e2e&color=89b4fa&line=cba6f7&point=f38ba8" alt="Contribution Graph" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">
  
<img src="https://github-profile-trophy.vercel.app/?username=TU_USUARIO&theme=catppuccin_mocha&no-frame=true&no-bg=true&row=1&column=7" alt="Trophies" />

</div>

---

## 💼 Experiencia Profesional

<div align="center">

\`\`\`mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#1e1e2e', 'primaryTextColor':'#cdd6f4', 'primaryBorderColor':'#89b4fa', 'lineColor':'#cba6f7', 'secondaryColor':'#313244', 'tertiaryColor':'#1e1e2e'}}}%%
timeline
    title Mi Trayectoria Profesional & Académica
    2021 : Inicio en Desarrollo Web
         : HTML, CSS, JavaScript
         : Primeros proyectos personales
    2022 : Ingreso a Universidad del Atlántico
         : Beca FUNIBER
         : Fundamentos de Programación
    2023 : Developer en Presencia Web Santander
         : Desarrollo con TypeScript y NestJS
         : Implementación de CI/CD
         : Trabajo con WordPress empresarial
    2024 : Full Stack Developer
         : Arquitectura de Microservicios
         : Docker & Kubernetes
         : Google Cloud Platform
         : Integración de IA con Ollama
\`\`\`

</div>

---

## 🎓 Educación & Certificaciones

<table align="center">
  <tr>
    <td align="center" width="300">
      <img src="https://img.shields.io/badge/Universidad-1e1e2e?style=for-the-badge&logo=google-scholar&logoColor=89b4fa" alt="Universidad"/>
      <h3>Universidad del Atlántico</h3>
      <p><strong>Ingeniería Informática</strong></p>
      <p>Becado FUNIBER</p>
    </td>
    <td align="center" width="300">
      <img src="https://img.shields.io/badge/Organización-1e1e2e?style=for-the-badge&logo=building&logoColor=cba6f7" alt="Organización"/>
      <h3>Presencia Web Santander</h3>
      <p><strong>Developer Team Member</strong></p>
      <p>Desarrollo Web Full Stack</p>
    </td>
  </tr>
</table>

---

## 🚀 Proyectos Destacados

<div align="center">

<table>
  <tr>
    <td width="50%">
      <h3 align="center">Sistema de Gestión Empresarial</h3>
      <div align="center">
        <a href="https://github.com/TU_USUARIO/proyecto1" target="_blank">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=TU_USUARIO&repo=proyecto1&theme=catppuccin_mocha&hide_border=true&bg_color=1e1e2e&title_color=89b4fa&icon_color=cba6f7&text_color=cdd6f4" alt="Proyecto 1" />
        </a>
        <p>
          <a href="https://github.com/TU_USUARIO/proyecto1" target="_blank">
            <img src="https://img.shields.io/badge/CÓDIGO-1e1e2e?style=for-the-badge&logo=github&logoColor=cdd6f4" alt="Código"/>
          </a>
          <a href="https://proyecto1-demo.com" target="_blank">
            <img src="https://img.shields.io/badge/DEMO-1e1e2e?style=for-the-badge&logo=vercel&logoColor=89b4fa" alt="Demo"/>
          </a>
        </p>
        <p><strong>NestJS, TypeScript, PostgreSQL, Docker</strong></p>
        <p>Sistema completo de gestión con arquitectura de microservicios, autenticación JWT y panel de administración.</p>
      </div>
    </td>
    <td width="50%">
      <h3 align="center">API RESTful con CI/CD</h3>
      <div align="center">
        <a href="https://github.com/TU_USUARIO/proyecto2" target="_blank">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=TU_USUARIO&repo=proyecto2&theme=catppuccin_mocha&hide_border=true&bg_color=1e1e2e&title_color=89b4fa&icon_color=cba6f7&text_color=cdd6f4" alt="Proyecto 2" />
        </a>
        <p>
          <a href="https://github.com/TU_USUARIO/proyecto2" target="_blank">
            <img src="https://img.shields.io/badge/CÓDIGO-1e1e2e?style=for-the-badge&logo=github&logoColor=cdd6f4" alt="Código"/>
          </a>
          <a href="https://proyecto2-demo.com" target="_blank">
            <img src="https://img.shields.io/badge/DEMO-1e1e2e?style=for-the-badge&logo=vercel&logoColor=89b4fa" alt="Demo"/>
          </a>
        </p>
        <p><strong>Express, MongoDB, Jenkins, GitLab CI</strong></p>
        <p>API escalable con pipeline de CI/CD automatizado, tests con Jest y despliegue en Google Cloud.</p>
      </div>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">Dashboard Analytics</h3>
      <div align="center">
        <a href="https://github.com/TU_USUARIO/proyecto3" target="_blank">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=TU_USUARIO&repo=proyecto3&theme=catppuccin_mocha&hide_border=true&bg_color=1e1e2e&title_color=89b4fa&icon_color=cba6f7&text_color=cdd6f4" alt="Proyecto 3" />
        </a>
        <p>
          <a href="https://github.com/TU_USUARIO/proyecto3" target="_blank">
            <img src="https://img.shields.io/badge/CÓDIGO-1e1e2e?style=for-the-badge&logo=github&logoColor=cdd6f4" alt="Código"/>
          </a>
          <a href="https://proyecto3-demo.com" target="_blank">
            <img src="https://img.shields.io/badge/DEMO-1e1e2e?style=for-the-badge&logo=vercel&logoColor=89b4fa" alt="Demo"/>
          </a>
        </p>
        <p><strong>React, TypeScript, Tailwind, Chart.js</strong></p>
        <p>Dashboard interactivo con visualización de datos en tiempo real y diseño responsive moderno.</p>
      </div>
    </td>
    <td width="50%">
      <h3 align="center">Automatización con AppScript</h3>
      <div align="center">
        <a href="https://github.com/TU_USUARIO/proyecto4" target="_blank">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=TU_USUARIO&repo=proyecto4&theme=catppuccin_mocha&hide_border=true&bg_color=1e1e2e&title_color=89b4fa&icon_color=cba6f7&text_color=cdd6f4" alt="Proyecto 4" />
        </a>
        <p>
          <a href="https://github.com/TU_USUARIO/proyecto4" target="_blank">
            <img src="https://img.shields.io/badge/CÓDIGO-1e1e2e?style=for-the-badge&logo=github&logoColor=cdd6f4" alt="Código"/>
          </a>
        </p>
        <p><strong>Google AppScript, Sheets API, Gmail API</strong></p>
        <p>Herramientas de automatización para Google Workspace, procesamiento de datos y reportes automáticos.</p>
      </div>
    </td>
  </tr>
</table>

</div>

---

## 📈 Contribuciones & Actividad

<div align="center">

### Lenguajes más utilizados (Detallado)

<img src="https://github-readme-stats.vercel.app/api/wakatime?username=TU_USUARIO&theme=catppuccin_mocha&hide_border=true&bg_color=1e1e2e&title_color=89b4fa&text_color=cdd6f4&layout=compact" alt="Wakatime Stats" />

</div>

---

## 🐍 Contribution Graph

<div align="center">
  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TU_USUARIO/TU_USUARIO/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TU_USUARIO/TU_USUARIO/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/TU_USUARIO/TU_USUARIO/output/github-contribution-grid-snake.svg">
</picture>

</div>

---

## 🎯 Objetivos 2025

<div align="center">

\`\`\`typescript
interface Goals2025 {
  learning: string[];
  projects: string[];
  community: string[];
  career: string[];
}

const myGoals: Goals2025 = {
  learning: [
    "Profundizar en arquitectura de microservicios",
    "Dominar patrones avanzados de React",
    "Certificación en Google Cloud Platform",
    "Aprender Go para backend de alto rendimiento"
  ],
  projects: [
    "Contribuir a proyectos open source",
    "Desarrollar una SaaS completa",
    "Crear contenido técnico en español",
    "Implementar proyectos con IA generativa"
  ],
  community: [
    "Mentoría a estudiantes de desarrollo",
    "Participar en eventos tech locales",
    "Escribir artículos técnicos",
    "Compartir conocimiento en redes"
  ],
  career: [
    "Completar Ingeniería Informática",
    "Fortalecer habilidades de arquitectura",
    "Liderar proyectos en Presencia Web",
    "Expandir red profesional internacional"
  ]
};
\`\`\`

</div>

---

## 📝 Blog & Artículos

<div align="center">

| Título | Tecnología | Fecha | Link |
|--------|-----------|-------|------|
| Implementando CI/CD con GitLab y Docker | DevOps | 2024 | [Leer →](https://tu-blog.com) |
| NestJS: Arquitectura escalable para APIs | Backend | 2024 | [Leer →](https://tu-blog.com) |
| TypeScript: Tips y mejores prácticas | Frontend | 2024 | [Leer →](https://tu-blog.com) |
| Kubernetes en producción: Guía práctica | Cloud | 2024 | [Leer →](https://tu-blog.com) |

</div>

---

## 💬 Habilidades Blandas

<div align="center">

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Trabajo_en_Equipo-1e1e2e?style=for-the-badge&logo=microsoft-teams&logoColor=89b4fa" alt="Trabajo en Equipo"/>
      <p>Colaboración efectiva en equipos multidisciplinarios</p>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Resolución_de_Problemas-1e1e2e?style=for-the-badge&logo=lighthouse&logoColor=cba6f7" alt="Resolución de Problemas"/>
      <p>Análisis crítico y soluciones creativas</p>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Comunicación-1e1e2e?style=for-the-badge&logo=telegram&logoColor=a6e3a1" alt="Comunicación"/>
      <p>Documentación clara y comunicación efectiva</p>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Aprendizaje_Continuo-1e1e2e?style=for-the-badge&logo=bookstack&logoColor=f9e2af" alt="Aprendizaje"/>
      <p>Adaptación constante a nuevas tecnologías</p>
    </td>
  </tr>
</table>

</div>

---

## 📫 Conecta Conmigo

<div align="center">

<a href="https://linkedin.com/in/tu-perfil">
  <img src="https://img.shields.io/badge/LinkedIn-1e1e2e?style=for-the-badge&logo=linkedin&logoColor=89b4fa" alt="LinkedIn"/>
</a>
<a href="https://twitter.com/tu-usuario">
  <img src="https://img.shields.io/badge/Twitter-1e1e2e?style=for-the-badge&logo=twitter&logoColor=89b4fa" alt="Twitter"/>
</a>
<a href="mailto:alex.larin@example.com">
  <img src="https://img.shields.io/badge/Email-1e1e2e?style=for-the-badge&logo=gmail&logoColor=f38ba8" alt="Email"/>
</a>
<a href="https://tu-portfolio.com">
  <img src="https://img.shields.io/badge/Portfolio-1e1e2e?style=for-the-badge&logo=firefox&logoColor=fab387" alt="Portfolio"/>
</a>
<a href="https://dev.to/tu-usuario">
  <img src="https://img.shields.io/badge/Dev.to-1e1e2e?style=for-the-badge&logo=dev.to&logoColor=cdd6f4" alt="Dev.to"/>
</a>
<a href="https://gitlab.com/tu-usuario">
  <img src="https://img.shields.io/badge/GitLab-1e1e2e?style=for-the-badge&logo=gitlab&logoColor=fab387" alt="GitLab"/>
</a>

</div>

---

## 📈 Profile Views & Stats

<div align="center">
  
<img src="https://komarev.com/ghpvc/?username=TU_USUARIO&label=Visitas%20al%20Perfil&color=89b4fa&style=for-the-badge&base=1000" alt="Profile Views" />

<br/><br/>

<img src="https://img.shields.io/github/followers/TU_USUARIO?label=Seguidores&style=for-the-badge&color=89b4fa&labelColor=1e1e2e" alt="Followers" />
<img src="https://img.shields.io/github/stars/TU_USUARIO?label=Stars&style=for-the-badge&color=cba6f7&labelColor=1e1e2e" alt="Stars" />

</div>

---

## 🌟 Testimonios

<div align="center">

> "Alex es un desarrollador excepcional con gran capacidad de aprendizaje y compromiso con la calidad del código."  
> **— Equipo Presencia Web Santander**

> "Su dominio de TypeScript y NestJS ha sido fundamental para el éxito de nuestros proyectos."  
> **— Líder Técnico**

</div>

---

<!-- SVG Footer animado -->
<div align="center">

<svg width="100%" height="120" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="120" fill="#1e1e2e"/>
  
  <!-- Onda animada superior -->
  <path d="M0,40 Q250,20 500,40 T1000,40 T1500,40 T2000,40 T2500,40 T3000,40" stroke="#89b4fa" stroke-width="2" fill="none" opacity="0.3">
    <animate attributeName="d" 
             values="M0,40 Q250,20 500,40 T1000,40 T1500,40 T2000,40 T2500,40 T3000,40;
                     M0,40 Q250,60 500,40 T1000,40 T1500,40 T2000,40 T2500,40 T3000,40;
                     M0,40 Q250,20 500,40 T1000,40 T1500,40 T2000,40 T2500,40 T3000,40"
             dur="5s" 
             repeatCount="indefinite"/>
  </path>
  
  <path d="M0,40 Q250,60 500,40 T1000,40 T1500,40 T2000,40 T2500,40 T3000,40" stroke="#cba6f7" stroke-width="2" fill="none" opacity="0.3">
    <animate attributeName="d" 
             values="M0,40 Q250,60 500,40 T1000,40 T1500,40 T2000,40 T2500,40 T3000,40;
                     M0,40 Q250,20 500,40 T1000,40 T1500,40 T2000,40 T2500,40 T3000,40;
                     M0,40 Q250,60 500,40 T1000,40 T1500,40 T2000,40 T2500,40 T3000,40"
             dur="5s" 
             repeatCount="indefinite"/>
  </path>
  
  <!-- Texto principal -->
  <text x="50%" y="75" font-family="'Courier New', monospace" font-size="16" fill="#cdd6f4" text-anchor="middle" font-weight="bold">
    "Code is poetry, but debugging is horror" 💻
  </text>
  
  <text x="50%" y="95" font-family="'Courier New', monospace" font-size="12" fill="#89b4fa" text-anchor="middle" opacity="0.7">
    Made with ❤️ by Alex Larin | Universidad del Atlántico
  </text>
  
  <!-- Partículas decorativas -->
  <circle cx="15%" cy="60" r="2" fill="#f38ba8" opacity="0.5">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite" />
  </circle>
  <circle cx="85%" cy="65" r="2" fill="#a6e3a1" opacity="0.5">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite" />
  </circle>
</svg>

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&text=¡Construyamos%20algo%20increíble%20juntos!&fontSize=24&fontColor=cdd6f4&animation=twinkling" width="100%"/>
</div>
