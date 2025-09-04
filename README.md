# Hi, I’m Mutlu Kurt 👋

**AI-First Frontend Developer & Prompt Engineer**  
I build modern, responsive, and production-ready interfaces for web and mobile. On the web I use **React / Next.js + Tailwind CSS + TypeScript**; on mobile I use **React Native + Expo**.  
My edge is an **AI-Native engineering workflow**: I combine hands-on coding with **prompt engineering** and automation—powered primarily by **Claude Code CLI**—to deliver faster, cleaner, and more maintainable results.

---

<!-- VISUAL: Futuristic AI + Coding Intro (NEW GIF #1) -->
<p align="center">
  <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExdXFicTQzc3B6Nno0dzdqdHlrZTQ5eGZncmZvNzMwaW9yOGdjdmdjcyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/HzPtbOKyBoBFsK4hyc/giphy.gif" width="480" alt="AI + Coding Futuristic Intro" />
</p>

---

## 🔁 What “AI-First” and “AI-Native” Mean (in practice)

- **AI-First** → AI is involved from the **very first minute**: discovery, spec, wireframe, scaffolding, refactors, tests, docs, deployment.  
- **AI-Native** → AI is the **backbone** of the engineering culture: prompt templates, review loops, guardrails, reproducible scripts, and measurable outputs—**not** a side plugin.  
- **Outcomes** → Shorter delivery times, fewer regressions, consistent code style, superior docs, and predictable iteration cycles.

---

## 🧠 Why Claude Code (CLI) is my primary environment

I’ve evaluated Cursor, Bolt, Lovable, Emergent, and Rork. I use them when they shine, but for **production-grade flow** I lead with **Claude Code CLI** because it is:

- **Lightweight & distraction-free** → CLI-first ergonomics keep focus on problem-solving.
- **Structured outputs** → Cleaner component boundaries and better refactor suggestions.
- **Iterative speed** → Prompt → Diff → Test → Repeat, with minimal overhead.
- **Scriptable** → Fits neatly into npm scripts and CI, so prompts become **reproducible build steps**.

> I still use other tools tactically (e.g., quick UI spikes or idea exploration). But the **mainline code** and audits run through Claude Code CLI for consistency, speed, and quality.

---

## 🧩 My Prompt Engineering System

**Goals:** correctness, clarity, consistency, and speed—without sacrificing maintainability.

1. **Prompt templates (system + task + constraints)**  
   - Coding standards (TypeScript strictness, ESLint/Prettier rules).  
   - UI contract (atomic components, accessibility, Tailwind tokens).  
   - Performance budgets (Lighthouse targets, bundle size ceilings).  
   - Security policies (input validation patterns, no secret leakage).

2. **Spec-to-Code scaffolding**  
   - Convert user stories into a file map and component tree.  
   - Generate typed interfaces, design tokens, and shared utilities first.  
   - Create “walking skeleton”: minimal app with routing, state, layout.

3. **Critique / Review prompts**  
   - Ask AI to self-review: complexity, accessibility (ARIA), perf hotspots.  
   - Request diffs only; reject noisy or stylistic churn.

4. **Test generation & coverage growth**  
   - Unit tests for pure logic (Vitest/Jest).  
   - Component tests (React Testing Library).  
   - E2E smoke paths (Playwright/Cypress) tied to key user journeys.

5. **Refactor & hardening loops**  
   - Optimize render paths; remove prop drilling; memoize expensive work.  
   - Split code by route; lazy-load noncritical modules.  
   - Verify no regression via E2E smoke.

6. **Docs & DX**  
   - Autogenerate README sections (setup, scripts, env vars, decisions).  
   - Comments and JSDoc for exported APIs.  
   - Optional Storybook for shared components.

7. **Localization & content** (when needed)  
   - i18n scaffolding, copy generation, and glossary alignment.

---

<!-- VISUAL: Prompt Engineering in Action (NEW GIF #2) -->
<p align="center">
  <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExaWwycHRjZGQyaXVndzVsdXhvcjQ1c2NydTF4MGR0cjB0dDZ6d211YSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/m6pvmOSXuTEPaKFWBz/giphy.gif" width="480" alt="Prompt Engineering in Action" />
</p>

---

## 🧭 End-to-End Delivery Workflow (Claude CLI loop)

1. **Discovery & goals** → align on business outcomes, KPIs, must-haves.  
2. **Spec & blueprint** → user stories, acceptance criteria, component map.  
3. **Scaffold** → repo, CI, lint/test hooks, base routes, design tokens.  
4. **Build in thin vertical slices** → each slice: prompt → code → review → test → demo.  
5. **QA & hardening** → performance budgets, a11y checks, security validation.  
6. **Deployment** → Vercel (web), Expo EAS or OTA updates (mobile).  
7. **Handover** → docs, scripts, governance notes, and maintainers’ guide.

**Result:** measurable velocity, transparent checkpoints, and a codebase that your team can own confidently.

---

## 🧮 How Clients Benefit (concrete value)

- **Time-to-first-value** in hours/days, not weeks.  
- **Higher quality** via repeatable AI reviews + human code ownership.  
- **Lower maintenance cost** thanks to typed code, tests, and clear docs.  
- **Scalability from day 1** (routing, state, data access, caching patterns).  
- **Clarity & control** with demoable vertical slices and short feedback loops.  
- **Risk reduction** through security/a11y/performance guardrails embedded in prompts.

---

## 🧱 Tech & Architecture Choices

- **Web:** React, Next.js (App Router), Tailwind CSS, TypeScript.  
- **Mobile:** React Native + Expo (OTA updates, Expo Go for quick QA).  
- **State & Data:** Zustand/Redux/Context; SWR/React Query for data sync.  
- **APIs & Backends:** REST/GraphQL; can integrate Supabase/Firebase/Hasura or your stack.  
- **Testing:** Vitest/Jest, React Testing Library, Playwright/Cypress.  
- **CI/CD:** GitHub Actions; Vercel for web; EAS or Fastlane for mobile.  
- **Monitoring:** Sentry/LogRocket where appropriate.

---

## 🧪 Quality, Performance, Security

- **Performance budgets** → Lighthouse ≥ 90 on PWA/Perf/Best-Practices where feasible.  
- **Accessibility** → semantic HTML, ARIA roles, keyboard navigation.  
- **Security** → input validation, sanitized rendering, secrets management, auth flows.  
- **Reliability** → unit + E2E smoke; PR checks enforce lint/tests.

---

## 📦 Deliverables You Receive

- Clean, typed, production-ready code (web and/or mobile).  
- A maintained **README** with setup, run, test, deploy instructions.  
- Preconfigured **CI** and baseline tests.  
- Component library and design tokens for consistent UI.  
- Optional Storybook and architecture notes.  
- A clear **handover checklist** so your team can iterate confidently.

---

## 🤝 Engagement Models

- **Prototype Sprint (2–5 days)** → validate an idea with a working vertical slice.  
- **MVP (1–3 weeks)** → core product with tests, CI, and deploy.  
- **Scale & polish (ongoing)** → performance, a11y, features, analytics, QA.

---

## 📂 Featured Projects (selected)

<p align="center">
  <a href="https://mutlukurt.github.io/dashboard-app/"><img src="./docs/dashpro.png" width="45%" alt="Dashboard App" /></a>
  <a href="https://mutlukurt.github.io/cookify-recipe-app/"><img src="./docs/foodfun.png" width="45%" alt="Cookify Recipe App" /></a>
</p>

<p align="center">
  <a href="https://mutlukurt.github.io/prestige-motors/"><img src="./docs/learnhub.png" width="45%" alt="Prestige Motors" /></a>
  <img src="./docs/nexaflow.png" width="45%" alt="NexaFlow" />
</p>

<p align="center">
  <img src="./docs/nexaflow2.png" width="45%" alt="NexaFlow 2" />
</p>

---

## 🧰 Tools & Technologies

![AI-First](https://img.shields.io/badge/AI--First-4B0082?style=for-the-badge&logo=claude&logoColor=white)
![Claude CLI](https://img.shields.io/badge/Claude%20Code-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-0ACF83?style=for-the-badge&logo=figma&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

<!-- VISUAL: Build/Deploy Energy (NEW GIF #3) -->
<p align="center">
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGV2NTM5bDdsZmZnbGx6dndkZHZxMmlyaWtmYjdpcTJqY2tsOTFzdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MD0svLSDeudszrNrp0/giphy.gif" width="420" alt="Build & Deploy Energy" />
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mutlukurt&show_icons=true&theme=radical" alt="Mutlu's GitHub stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mutlukurt&layout=compact&theme=radical&langs_count=8" alt="Top Langs" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mutlukurt&theme=react-dark&hide_border=true&v=1" alt="Contribution Activity Graph" />
</p>

---

## 🌐 Connect

- [LinkedIn](https://www.linkedin.com/in/mutlukurt)
- [Twitter / X](https://twitter.com/mutlukurtio)
- [GitHub](https://github.com/mutlukurt)

---

✨ *Mission: push the boundaries of software development with **AI-Native** practices—shipping clean, efficient, future-proof products.*
