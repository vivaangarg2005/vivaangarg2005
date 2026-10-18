<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,100:38BDF8&text=Vivaan%20Garg&fontAlignY=38&fontSize=46&fontColor=ffffff&animation=fadeIn" alt="Vivaan Garg" />

# Vivaan Garg

### Full-Stack Developer · AI Enthusiast · Problem Solver

I build useful web products, dependable backends, and AI-powered experiences.

[![Portfolio](https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white)](https://vivaangarg.netlify.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vivaangarg2005)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vivaangarg2005)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/vivaan2005/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vivaangarg2005@gmail.com)

<img src="https://komarev.com/ghpvc/?username=vivaangarg2005&style=flat-square&color=38BDF8&label=PROFILE+VIEWS" alt="Profile views" />

</div>

---

## 👨‍💻 About Me

I'm **Vivaan Garg**, an Information Technology undergraduate at **Guru Tegh Bahadur Institute of Technology (GGSIPU)**. I enjoy building full-stack products, designing dependable backend systems, and exploring practical applications of AI.

| | |
|---|---|
| 🎓 **Education** | B.Tech in Information Technology · GTBIT (GGSIPU) |
| 📍 **Location** | Delhi, India |
| 📊 **CGPA** | 9.05/10 |
| 🧠 **LeetCode contest rating** | 1716 |
| 🎯 **Current focus** | Full-stack engineering, backend development, system design |

## 🧰 Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend, Databases & Tools**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)

**Core concepts:** Data Structures & Algorithms, OOP, Operating Systems, DBMS, Computer Networks, REST APIs, JWT authentication, and HttpOnly cookies.

---

## 🚀 Featured Projects

### TraceFlow — Behavioral Analytics & Spatial Intelligence

<div align="center">
  <img src="./TraceFlow.png" alt="TraceFlow project preview" width="92%" />
</div>

**React 19 · Vite · Node.js · Express · MongoDB Atlas · Vanilla JavaScript SDK**

An open-source analytics platform inspired by tools like Hotjar and Microsoft Clarity. TraceFlow captures visitor interactions, reconstructs user journeys, and visualizes click activity as heatmaps over webpage previews.

- **Lightweight tracking SDK:** A zero-dependency `tracker.js` script under 4 KB minified, designed to capture page views and clicks with minimal integration.
- **Responsive spatial analytics:** Stores pixel coordinates and viewport-relative percentages so interaction hotspots can be interpreted across screen sizes.
- **Privacy-aware collection:** Sanitizes sensitive text and likely PII on the client before events are sent to the API.
- **Reliable event delivery:** Batches events and uses `navigator.sendBeacon()` with a `fetch` keepalive fallback for navigation-sensitive interactions.
- **Session journeys:** Reconstructs chronological visitor timelines with page transitions, click targets, and relative event times.
- **Three heatmap views:** Thermal glow, a 10×10 density grid, and interactive pins, with desktop, tablet, and mobile viewport presets.
- **Two dashboard modes:** Store Owner summaries for business insights and Technical views for event telemetry and debugging.
- **Testing & deployment:** Reports 13/13 passing API integration tests; frontend and storefront on Vercel, ingestion API on Render, and data stored in MongoDB Atlas.

**Links:** Add TraceFlow's direct GitHub repository and live dashboard URLs here.

---

### The Anvor — Full-Stack E-Commerce Platform

<div align="center">
  <img src="./The-Anvor.png" alt="The Anvor project preview" width="92%" />
</div>

**Next.js · TypeScript · Node.js · Express.js · MongoDB**

A full-stack shopping platform with product discovery, secure authentication, and a persistent cart experience.

- Product browsing with filtering, pagination, and dedicated product detail pages.
- Password- and OTP-based authentication using HttpOnly JWT cookies.
- Guest cart support with automatic merging into persistent MongoDB carts after sign-in.
- Atomic cart updates designed to maintain consistency during concurrent operations.

**Links:** Add The Anvor's direct GitHub repository and live deployment URLs here.

---

### AI Resume Analyzer

<div align="center">
  <img src="./RA.png" alt="AI Resume Analyzer project preview" width="92%" />
</div>

**React · Tailwind CSS · Node.js · Express.js · Google Gemini API**

An AI-powered tool that analyzes PDF resumes and generates structured, role-aware feedback.

- Identifies strengths, improvement areas, and personalized skill recommendations.
- Uses Google Gemini for contextual resume analysis and actionable suggestions.
- Processes PDFs in memory with Multer Memory Storage.
- Uses IP-based rate limiting to help protect the API from abuse.

[![Live Demo](https://img.shields.io/badge/Live_Demo-16A34A?style=for-the-badge&logo=vercel&logoColor=white)](https://resume-analyzer-vg.vercel.app/)

---

## 🏆 Achievements

- 🥇 **1st Prize** — Debug Run competition
- 🏅 **QubitX** — Top 10 finalist
- 🏅 **MatheThon** — Hackathon finalist
- 🏅 **Nexathon** — Top 15 among 150 teams
- 🧠 **LeetCode** — 1716 contest rating

## 📈 GitHub Analytics

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=vivaangarg2005&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub statistics" />
  <img height="165" src="https://streak-stats.demolab.com?user=vivaangarg2005&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
</div>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=vivaangarg2005&theme=tokyo-night&hide_border=true" alt="GitHub activity graph" width="100%" />

---

## 🤝 Let's Connect

I'm always happy to connect about full-stack development, backend engineering, AI projects, and hackathons.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white)](https://vivaangarg.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vivaangarg2005)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vivaangarg2005@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:38BDF8,100:0F172A" alt="" />

*Thanks for visiting — let's build something useful.*

</div>
