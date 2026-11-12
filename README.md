<p align="center">
  <img src="./assets/header.svg" alt="Murilo Silva Braga de Castro — Software Engineering, AI and Computer Networks" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/murilocastro31/"><img src="https://img.shields.io/badge/LinkedIn-Murilo%20Castro-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:murilosbcastro@gmail.com"><img src="https://img.shields.io/badge/Email-murilosbcastro%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open%20to-Internships-1F8F72?style=for-the-badge" alt="Open to internships" />
  <a href="#portfolio"><img src="https://img.shields.io/badge/Portfolio-5%20projects-24292F?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio" /></a>
</p>

## About me

I’m a technology student based in **Brasília, Brazil**, currently pursuing two higher-education programs:

- **Communication Networks Engineering** at **Universidade de Brasília (UnB)** — expected graduation: **2031**
- **Systems Analysis and Development** at **Universidade Católica de Brasília (UCB)** — expected graduation: **2028**

My main interests are **Software Engineering, Artificial Intelligence and Computer Networks**. I enjoy learning through practice: testing ideas, understanding why things fail, correcting mistakes and improving solutions until they work well.

Right now, I’m strengthening my programming fundamentals, learning modern development workflows and building a [portfolio](#portfolio) of real-world projects while pursuing my **first internship in technology**.

## Current focus

```text
Software Engineering    → programming fundamentals, full stack development, clean code
Artificial Intelligence → generative AI, LLM workflows, AI-assisted development
Computer Networks       → networking fundamentals, infrastructure and automation
Career                   → first internship in technology
```

## Portfolio

### Featured projects

> 🔒 The source code of these three projects is kept in private repositories. I’m happy to walk through the code, architecture and tests in an interview.

<table>
<tr>
<td width="50%" valign="top">

#### 🎲 Grimório da Mesa

**Online platform for tabletop RPG campaigns** — a fan-made, non-profit platform for *Black Clover* campaigns using the *Feiticeiros & Maldições* system.

- Character sheets with a fully tested **rules engine** that calculates attributes, skills, defense, damage and level progression automatically
- Game masters can **customize the rules** of each campaign and preview the impact before applying
- **Server-side dice rolls**, real-time combat, chat with roll commands and a **2D virtual tabletop** (scenes, grid, tokens, fog of war)
- Security by design: **Row Level Security on every table**, private file storage served through short-lived signed URLs
- **178 unit and database tests** (Vitest + PGlite) and Playwright end-to-end tests

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod" />
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />

**Status:** in development · 🔒 private repository

</td>
<td width="50%" valign="top">

#### 🏋️ Carga

**Mobile-first strength training log** — replaces spreadsheets, notes, a separate timer and manual progression math with a single app, built to be used at the gym.

- **Local-first active workout** stored in IndexedDB with a sync queue, so logging keeps working with a bad connection
- Load **progression suggestions** with explanations, estimated 1RM, personal-record detection and a plate calculator
- Routines, history with calendar, progress charts, body measurements, goals and **private progress photos**
- Supabase backend with **Row Level Security** and an **email allowlist** (no public sign-up)
- Versioned **JSON backup** with import preview; catalog of 73 exercises

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
<img src="https://img.shields.io/badge/IndexedDB-555555?style=flat-square" alt="IndexedDB" />
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />

**Status:** functional end to end · 🔒 private

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### ⚖️ Medeiros & Antinoro — Institutional website

**Website for a law firm** (client project), focused on accessibility, a consistent visual identity and maintainable code.

- Custom **design system** with semantic tokens and WCAG-checked color contrast, documented alongside UX and security contracts
- Responsive pages for the firm, practice areas and contact, including partner profiles and FAQ
- **Instagram feed** fetched server-side (no keys exposed to the browser), with caching tuned to stay within the free plan’s limits
- **Accessibility tested automatically** with Playwright + axe-core: keyboard navigation, reflow and reduced motion
- **CI on GitHub Actions** (format, typecheck, lint, tests and build) and architecture decisions recorded as ADRs

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
<img src="https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white" alt="Testing Library" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />

**Status:** in development, content under client review · 🔒 private repository

</td>
</tr>
</table>

### Challenges and practice

| Project | What it is | Stack | Code |
|---|---|---|---|
| **Algorithms in JavaScript** | Trainee challenge: the 5 final projects of freeCodeCamp’s *JavaScript Algorithms and Data Structures* (palindrome checker and more) | JavaScript | [Repository](https://github.com/MuriloCastro-UnB/Desafio-1-2024.1-Backend) |
| **Web résumé** | Trainee challenge: a personal résumé built as a web page using only HTML and CSS, without CSS frameworks | HTML, CSS | [Repository](https://github.com/MuriloCastro-UnB/Desafio-1-2024.1-Frontend) |

## Tech stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=js,ts,python,cpp,c,cs" alt="Programming languages" />
</p>

### Web Development

<p>
  <img src="https://skillicons.dev/icons?i=html,css,react,nodejs,nextjs" alt="Web development technologies" />
</p>

### Tools & Platforms

<p>
  <img src="https://skillicons.dev/icons?i=github,linux,vscode" alt="Tools and platforms" />
</p>

> Technologies listed here are technologies I have already studied or used. I’m actively developing deeper proficiency through coursework and hands-on practice.

## Education

### Universidade de Brasília — UnB
**Communication Networks Engineering**  
2026 — 2031 (expected)

Current coursework includes **Computer Programming for Engineering, Calculus I, Physics I, Experimental Physics I and Environmental Sciences**.

### Universidade Católica de Brasília — UCB
**Technology Degree in Systems Analysis and Development**  
2026 — 2028 (expected)

## Additional training

### FullStack PRO — Sujeito Programador
**In progress — started Jan 2026**

Training focused on modern full stack development, covering front-end, back-end and AI-assisted software development.

## Certifications

All issued by **Anthropic** through **Claude Academy** in **August 2026**.

| Certification | Credential ID |
|---|---|
| **Claude 101** | `12b2742b14a00a7349a6a74340bcd968` |
| **AI Fluency: Framework & Foundations** | `f3960a3c6bd558c37861c2c8fc0286c6` |
| **AI Capabilities and Limitations** | `0e6cdffbb706554c332bc309f591ca79` |
| **Claude Code 101** | `66fb73940865a129a99dc0d83319a410` |
| **Introduction to Claude Cowork** | `299a05412770578f5e040c2a86c59212` |

## Technical roadmap

Next projects and technical areas I plan to develop as my portfolio grows:

| Project / Track | Goal | Planned stack |
|---|---|---|
| **NetDiag** | Network diagnostics and automation | Python, networking, CLI |
| **Full Stack Application** | End-to-end web application | React / Next.js, Node.js, database |
| **NetOps AI** | AI-assisted network and infrastructure analysis | Python / TypeScript, LLM API, full stack |
| **Algorithms & Data Structures** | Problem solving and interview fundamentals | Python / C++ |

> This section is a roadmap, not a list of completed projects. Finished work is listed in the [Portfolio](#portfolio) section.

## What I’m learning next

- Git and collaborative development workflows
- SQL and relational databases
- REST APIs and HTTP fundamentals
- Data structures and algorithms
- Linux and command-line tooling
- TCP/IP, DNS, routing, switching and network fundamentals
- Building and documenting production-style projects

## Languages

- **Portuguese:** Native
- **English:** Intermediate
- **Spanish:** Intermediate

## Let’s connect

I’m looking for my **first technology internship**, preferably remote, while remaining open to on-site opportunities.

If you work with **software engineering, AI, networking, infrastructure or technology recruiting**, feel free to reach out.

<p align="center">
  <a href="https://www.linkedin.com/in/murilocastro31/"><strong>LinkedIn</strong></a>
  ·
  <a href="mailto:murilosbcastro@gmail.com"><strong>Email</strong></a>
</p>
