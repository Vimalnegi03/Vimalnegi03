<h1 align="center">Hi 👋, I'm Vimal Negi</h1>
<h3 align="center">Software Development Engineer @ Lend A Hand India · Full-Stack & AI Systems Builder</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1000&color=38BDF8&center=true&vCenter=true&width=600&lines=SDE+%40+Lend+A+Hand+India+%F0%9F%92%BC;Building+Full-Stack+%2B+AI+Products+%F0%9F%9A%80;React+%7C+Next.js+%7C+Angular+%7C+NestJS+%7C+.NET;Shipped+a+Security-Audited+Facial+Recognition+System+%F0%9F%94%90" alt="Typing SVG" />
</p>

<img align="right" alt="Coding" width="400" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif">

- 🏢 I'm currently working as an **SDE @ Lend A Hand India (LAHI)**

- 🚀 Building **Check Karo Bawe** — an AI-powered QR menu SaaS, as a side project

- 🌱 Deep diving into **RAG pipelines, vector search (Qdrant), and on-device ML for mobile**

- 💬 Ask me about **React / Next.js / Angular, Node.js / NestJS / .NET, MySQL / MongoDB, LLM integrations**

- 📫 How to reach me **vimalnegi2003@gmail.com**

- ⚡ Fun fact **My code doesn't always work, but when it does, I have no idea why.**

<br clear="both"/>

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://github.com/Vimalnegi03" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="Vimalnegi03" height="30" width="40" /></a>
  <a href="https://www.linkedin.com/in/vimal-negi/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="vimal-negi" height="30" width="40" /></a>
  <a href="https://hashnode.com/@vimalnegi03" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hashnode.svg" alt="@vimalnegi03" height="30" width="40" /></a>
  <a href="https://leetcode.com/u/vimalnegi03/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="vimalnegi03" height="30" width="40" /></a>
</p>

<p align="left">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://trophy.ryglcloud.net/?username=Vimalnegi03&theme=light&no-frame=true&margin-w=10" />
  </a>
</p>

## 🗂️ Featured Projects

<details open>
<summary><b>🍽️ Check Karo Bawe — AI-Powered QR Menu Platform</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=react,ts,vite,tailwind,nodejs,express,mysql&theme=dark" />

A multi-tenant SaaS that turns a physical restaurant menu into a live, scannable QR menu — personal project.

- 🏢 **Multi-tenant**: a super admin onboards restaurant admins; each restaurant gets a unique slug and an auto-generated QR code
- 🤖 **AI menu import**: upload a photo of a physical menu → GPT-4o vision extracts every dish (name, ingredients, price, veg/non-veg, spice level, taste tags, nutrition estimates) into an editable review table before committing; re-scanning updates existing dishes by name instead of duplicating them
- ⭐ **Guest-facing menu**: live search + filters (category, veg/non-veg, spice level, taste tags), star ratings with optional photo reviews per dish
- 🔐 JWT-based auth, role-based access, duplicate-dish protection

<p>
  <a href="https://check-karo-bawe-7.onrender.com" target="_blank">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-38BDF8?style=for-the-badge&logoColor=white" />
  </a>
</p>
</details>

<details>
<summary><b>🧑‍💻 Face Recognition Attendance System — Lend A Hand India</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,nestjs,mongodb,tensorflow,expo&theme=dark" />

A full-stack, multi-role (student/instructor) attendance platform built around on-device facial recognition, built at LAHI.

- 📱 **Mobile app** (Expo / React Native): on-device face verification via **TensorFlow.js**, geofenced + time-boxed attendance marking, layered auth (JWT + OTP + 4-digit PIN), jailbreak/root detection for tamper resistance
- 🖥️ **Admin dashboard** (Next.js + Tailwind): institute-level and super-admin management — calendars, maps, analytics
- ⚙️ **API** (NestJS + Fastify + MongoDB): JWT/Passport auth, Swagger docs, file uploads, email notifications
- ✅ **Passed a live security (VAPT) audit** before production rollout

<p>
  <a href="https://fcr-app.lighthouse.net.in/" target="_blank">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-F43F5E?style=for-the-badge&logoColor=white" />
  </a>
</p>
</details>

<details>
<summary><b>🏛️ LAHI Lighthouse Platform — Lend A Hand India</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=cs,dotnet,angular,ts&theme=dark" />

An enterprise-grade case-management platform, built at LAHI.

- 🧱 **.NET backend** split into clean, layered projects — BAL, DAL, DAL.EF, Entities, Models, Mappers, Services, Cryptography, Logging, EmailServices — for strict separation of concerns
- 🖥️ **Angular 18 + Angular Material** admin frontend
- 🔐 Custom cryptography and logging modules built in-house for the platform

<p>
  <a href="https://himachalpradesh.lighthouse.net.in/login" target="_blank">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-A855F7?style=for-the-badge&logoColor=white" />
  </a>
</p>
</details>

<details>
<summary><b>🎓 Kaushal Saathi AI — AI Teaching Companion</b></summary>
<br/>

<img src="https://skillicons.dev/icons?i=react,ts,vite,mysql&theme=dark" />

An AI-powered teaching companion for the Kaushal Bodh vocational education curriculum (Grades 6–8).

- 🧠 **RAG pipeline** over curriculum content using **Qdrant** vector search, with Gemini/OpenAI auto-detected for generation
- 📝 Generates lesson plans, tracks student progress, and manages assessments for teachers
- 🛡️ Admin panel for school-level admins and platform super admins — teacher accounts, content access, question banks, reports, and audit logs

<p>
  <a href="https://kaushalsaathi.ai/login" target="_blank">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-22C55E?style=for-the-badge&logoColor=white" />
  </a>
</p>
</details>

## 🏆 Achievements

<p align="left">
  <img src="https://img.shields.io/badge/Security_Audited-Facial_Recognition_System-22C55E?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/4x-Production_Systems_Shipped-A855F7?style=for-the-badge&labelColor=0d1117" />
</p>

- 🔐 **Security-Audited in Production** — contributed to a facial recognition attendance system that passed a live **VAPT (Vulnerability Assessment & Penetration Testing)** security audit before going live
- 🏗️ **Shipped 4 full-stack production systems** — spanning React, Next.js, and Angular on the frontend; Node.js, NestJS, and .NET on the backend; React Native + on-device ML (TensorFlow.js) on mobile
- 💼 **SDE @ Lend A Hand India** — building and maintaining enterprise-grade platforms powering real-world social impact programs
- ✍️ **Technical writer** — sharing deep-dives and learnings on [Hashnode](https://hashnode.com/@vimalnegi03)
- 🧩 **Consistent problem solver** — sharpening DSA fundamentals on [LeetCode](https://leetcode.com/u/vimalnegi03/)

<h3>My favorite tools and technologies ⚙️</h3>

<div align="center">
<table>
  <tr>
    <td align="center" width="96">
        <img src="https://techstack-generator.vercel.app/react-icon.svg" width="48" height="48" alt="react" />
      <br>React
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=nextjs" width="48" height="48" alt="nextjs" />
      <br>Next.js
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=angular" width="48" height="48" alt="angular" />
      <br>Angular
    </td>
    <td align="center" width="96">
        <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="65" height="65" />
      <br>Javascript
    </td>
    <td align="center" width="96">
        <img src="https://techstack-generator.vercel.app/ts-icon.svg" width="48" height="48" alt="TS" />
      <br>Typescript
    </td>
    <td align="center" width="96">
        <img src="https://techstack-generator.vercel.app/cpp-icon.svg" alt="icon" width="65" height="65" />
      <br>C/C++
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=windows" width="48" height="48" alt="Windows" />
      <br>Windows
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
        <img src="https://nodejs.org/static/logos/jsIconGreen.svg" width="65" height="65" alt="NodeJS" />
      <br>NodeJS
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=express" width="48" height="48" alt="express" />
      <br>Express
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=nestjs" width="48" height="48" alt="nestjs" />
      <br>NestJS
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=dotnet" width="48" height="48" alt="dotnet" />
      <br>.NET
    </td>
    <td align="center" width="96">
        <img src="https://techstack-generator.vercel.app/restapi-icon.svg" width="65" height="65" alt="Rest API" />
      <br>Rest API
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=socketio" width="48" height="48" alt="socket.io" />
      <br>Socket.io
    </td>
    <td align="center" width="96">
        <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="icon" width="65" height="65" />
      <br>Python
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=mysql" width="48" height="48" alt="mysql" />
      <br>MySQL
    </td>
    <td align="center" width="96">
        <img src="https://d2lgmzy8vjj79z.cloudfront.net/mongodb.svg" width="65" height="65" alt="MongoDB" />
      <br>MongoDB
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="postgresql" />
      <br>PostgreSQL
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=prisma" width="48" height="48" alt="prisma" />
      <br>Prisma
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=tensorflow" width="48" height="48" alt="tensorflow" />
      <br>TensorFlow
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=expo" width="48" height="48" alt="expo" />
      <br>Expo / RN
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=zustand" width="48" height="48" alt="Zustand" />
      <br>Zustand
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
      <br>Git
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=html" width="48" height="48" alt="HTML" />
      <br>HTML
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=css" width="48" height="48" alt="css" />
      <br>CSS
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=tailwind" width="48" height="48" alt="tailwind" />
      <br>Tailwind
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=lua" width="48" height="48" alt="lua" />
      <br>Lua
    </td>
    <td align="center" width="96">
        <img src="https://skillicons.dev/icons?i=postman" width="48" height="48" alt="Postman" />
      <br>Postman
    </td>
    <td align="center" width="96">
        <!-- spacer -->
    </td>
  </tr>
</table>
</div>

<p>
  <img align="left" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs?username=vimalnegi03&layout=compact&theme=tokyonight" />
</p>

<p>
  <img align="center" src="https://github-readme-stats-eight-theta.vercel.app/api?username=vimalnegi03&show_icons=true&theme=tokyonight" />
</p>

<br clear="both"/>

<p>
  <img align="center" src="https://streak-stats.demolab.com/?user=vimalnegi03&theme=tokyonight" alt="vimalnegi03" />
</p>

<details>
  <summary>Profile Views 👁️</summary>
  <br/>
  <img src="https://komarev.com/ghpvc/?username=Vimalnegi03&label=PROFILE+VIEWS&style=for-the-badge&color=brightgreen" />
</details>
