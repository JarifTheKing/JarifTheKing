# Hi, I'm **Jarif Mahfuz**

<!-- File: jarif-banner.svg
     900×240 creative header for Jarif Mahfuz — MERN Developer -->
<svg xmlns="http://www.w3.org/2000/svg" width="900" height="240" viewBox="0 0 900 240" role="img" aria-labelledby="titleDesc">
  <title id="titleDesc">Jarif Mahfuz — MERN Developer</title>
  <defs>
    <linearGradient id="bgGrad" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%" stop-color="#0f172a"/>
      <stop offset="50%" stop-color="#0b1220"/>
      <stop offset="100%" stop-color="#071226"/>
    </linearGradient>

    <linearGradient id="accent" x1="0" x2="1">
      <stop offset="0%" stop-color="#6EE7B7"/>
      <stop offset="45%" stop-color="#60A5FA"/>
      <stop offset="100%" stop-color="#A78BFA"/>
    </linearGradient>

    <filter id="soft" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="16" result="b"/>
      <feBlend in="SourceGraphic" in2="b" mode="screen"/>
    </filter>

    <style>
      <![CDATA[
        .name { font: 700 28px 'Segoe UI', Roboto, system-ui; fill: #E6EEF8; letter-spacing: 0.4px; }
        .role { font: 500 14px 'Segoe UI', Roboto, system-ui; fill: #AFC9E8; }
        .muted { font: 400 12px 'Segoe UI', Roboto, system-ui; fill: #98AFCB; }
        .tag { font: 600 11px 'Segoe UI', Roboto, system-ui; fill: white; }
        .chip { rx: 12; ry: 12; }
        @media (prefers-reduced-motion: reduce) {
          .rot, .float { animation: none; }
        }
      ]]>
    </style>
  </defs>

  <!-- background -->
  <rect width="100%" height="100%" fill="url(#bgGrad)"/>

  <!-- soft floating blobs (decorative) -->
  <g filter="url(#soft)" opacity="0.85">
    <ellipse cx="140" cy="60" rx="120" ry="50" fill="url(#accent)" opacity="0.10" class="float">
      <animate attributeName="cx" dur="14s" values="120;160;120" repeatCount="indefinite"/>
      <animate attributeName="cy" dur="11s" values="60;40;70;60" repeatCount="indefinite"/>
    </ellipse>

    <ellipse cx="760" cy="160" rx="140" ry="65" fill="#0ea5a5" opacity="0.06" class="float">
      <animate attributeName="cx" dur="18s" values="760;740;780;760" repeatCount="indefinite"/>
      <animate attributeName="cy" dur="13s" values="160;140;170;160" repeatCount="indefinite"/>
    </ellipse>

    <ellipse cx="480" cy="40" rx="110" ry="42" fill="#be185d" opacity="0.05" class="float">
      <animate attributeName="cx" dur="16s" values="480;460;495;480" repeatCount="indefinite"/>
      <animate attributeName="cy" dur="12s" values="40;30;55;40" repeatCount="indefinite"/>
    </ellipse>
  </g>

  <!-- left-side avatar / mark -->
  <g transform="translate(36,34)">
    <!-- circular badge -->
    <g>
      <circle cx="80" cy="64" r="60" fill="rgba(255,255,255,0.03)"/>
      <circle cx="80" cy="64" r="46" fill="url(#accent)"/>
      <!-- simple 'JM' monogram -->
      <text x="80" y="76" text-anchor="middle" font-family="Segoe UI, Roboto, system-ui" font-weight="700" font-size="28" fill="#071226">JM</text>
    </g>

    <!-- rotating 'react-like' atom -->
    <g transform="translate(220,50)" class="rot" style="transform-origin: 0px 0px;">
      <g transform="translate(-40,-20)">
        <g>
          <ellipse cx="40" cy="24" rx="26" ry="10" fill="none" stroke="white" stroke-opacity="0.14" stroke-width="2"/>
          <ellipse cx="40" cy="24" rx="26" ry="10" transform="rotate(60 40 24)" fill="none" stroke="white" stroke-opacity="0.12" stroke-width="2"/>
          <ellipse cx="40" cy="24" rx="26" ry="10" transform="rotate(120 40 24)" fill="none" stroke="white" stroke-opacity="0.10" stroke-width="2"/>
          <circle cx="40" cy="24" r="4" fill="#071226" stroke="white" stroke-opacity="0.9" stroke-width="1"/>
          <animateTransform attributeName="transform" type="rotate" from="0 40 24" to="360 40 24" dur="16s" repeatCount="indefinite"/>
        </g>
      </g>
    </g>
  </g>

  <!-- main text -->
  <g transform="translate(240,56)">
    <text class="name" x="0" y="10">Jarif Mahfuz</text>
    <text class="role" x="0" y="36">MERN Developer — React · Node · Tailwind · Firebase</text>

    <!-- chips -->
    <g transform="translate(0,56)">
      <rect class="chip" x="0" y="0" width="110" height="28" fill="#0F172A" stroke="rgba(255,255,255,0.04)"/>
      <text class="tag" x="12" y="18">Open to work</text>

      <rect class="chip" x="130" y="0" width="160" height="28" fill="rgba(255,255,255,0.03)">
        <animate attributeName="fill" values="rgba(255,255,255,0.03);rgba(255,255,255,0.06);rgba(255,255,255,0.03)" dur="6s" repeatCount="indefinite"/>
      </rect>
      <text class="muted" x="142" y="18">Building scalable web apps</text>
    </g>
  </g>

  <!-- right side small project badges -->
  <g transform="translate(240,140)">
    <g transform="translate(0,0)">
      <rect x="0" y="0" width="220" height="68" rx="12" fill="rgba(255,255,255,0.02)" stroke="rgba(255,255,255,0.03)"/>
      <text class="muted" x="14" y="20">Featured</text>

      <g transform="translate(14,34)">
        <text class="tag" x="0" y="14">• WorkOrbit</text>
        <text class="muted" x="120" y="14">Job platform</text>

        <text class="tag" x="0" y="34">• Dragon News</text>
        <text class="muted" x="120" y="34">News portal</text>

        <text class="tag" x="0" y="54">• Learnova</text>
        <text class="muted" x="120" y="54">Learning platform</text>
      </g>
    </g>
  </g>

  <!-- subtle bottom divider -->
  <g transform="translate(0,230)">
    <rect x="32" y="0" width="840" height="2" fill="rgba(255,255,255,0.02)"/>
  </g>

  <!-- tiny signature -->
  <text x="760" y="226" font-family="Segoe UI, Roboto, system-ui" font-size="10" fill="#8095B3">crafted • Jarif</text>
</svg>


### 🚀 MERN Developer

Welcome to my GitHub profile! I build scalable web apps, modern UI, and full‑stack solutions using the MERN ecosystem.

---

## 💡 About Me

* 🔭 I’m working with **MERN Stack** professionally
* ⚡ Passionate about clean UI, performance, and problem‑solving
* 🌱 Currently improving on **Backend Architecture & Firebase integrations**
* 🎯 Goal: Become a highly skilled Full‑Stack Engineer

---

## 🛠️ Tech Stack

### **Frontend:**

* React.js · Tailwind CSS · JavaScript · HTML · CSS · DaisyUI

### **Backend:**

* Node.js · Express.js · REST APIs

### **Database:**

* MongoDB · Mongoose

### **Authentication & Hosting:**

* Firebase · JWT · Netlify · Vercel

### **Tools & Others:**

* Git · GitHub · VS Code · React Router · Axios

---

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jarifmahfuz\&show_icons=true\&hide_border=true\&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jarifmahfuz\&layout=compact\&hide_border=true\&theme=tokyonight)

---

## 🚀 Featured Projects

### 🔹 **Project 1 — 🔹 WorkOrbit**

A modern job management platform featuring user authentication, job posting, and dynamic dashboards.

### 🔹 **Project 2 — 🔹 Dragon News**

A responsive news portal built with React, Firebase auth, and real-time content rendering.

### 🔹 **Project 3 — 🔹 Learnova**

An interactive learning platform built with MERN, offering courses, quizzes, and user progress tracking.


---

## 🌐 Connect With Me

* 📧 Email: jarifanuwar7@gmail.com
*  Facebook: https://www.facebook.com/zaref.zayn
---

⭐ **Thanks for visiting!** If you like my work, consider giving a star to some repos!
