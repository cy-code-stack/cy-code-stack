<h2 align="center">Cymon John Buladaco</h2>

<p align="center">
  Software Developer &middot; Full-stack web applications
</p>

<p align="center">
  <a href="mailto:buladacocymonjohn02@gmail.com"><img src="https://img.shields.io/badge/Email-1E293B?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/cymon-john-buladaco-1875b2254/"><img src="https://img.shields.io/badge/LinkedIn-1E293B?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.facebook.com/saymon2002"><img src="https://img.shields.io/badge/Facebook-1E293B?style=flat-square&logo=facebook&logoColor=white" alt="Facebook"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-1E293B?style=flat-square&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/PHP-1E293B?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/TypeScript-1E293B?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-1E293B?style=flat-square&logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/Vue-1E293B?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue">
  <img src="https://img.shields.io/badge/Inertia.js-1E293B?style=flat-square&logo=inertia&logoColor=white" alt="Inertia.js">
  <img src="https://img.shields.io/badge/Tailwind_CSS-1E293B?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/MySQL-1E293B?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
</p>

---

### About

I build production web applications end to end &mdash; data modelling and backend services through
to the interfaces people actually use. Most of my work is delivered for local government units,
schools, and small businesses: permitting and records systems, e-learning platforms, booking and
dispatch tools, and internal dashboards.

My default stack is **Laravel + Inertia.js** with either **React** or **Vue** on the front end,
typed with TypeScript and styled with Tailwind CSS. For admin-heavy systems I build on
**Filament**. I care about role-based access control, auditable records, and reporting that holds
up in day-to-day operations.

---

### Tech Stack

<details open>
<summary><b>Backend</b></summary>

| Area | Tools |
| --- | --- |
| Framework | Laravel 12 / 13, Filament 3 |
| Auth &amp; access | Fortify, Sanctum, Spatie Permission |
| Data | Eloquent, MySQL, Spatie Data, Query Builder |
| Auditing | Spatie Activitylog |
| Reporting | DomPDF, Maatwebsite Excel, ApexCharts |

</details>

<details>
<summary><b>Frontend</b></summary>

| Area | Tools |
| --- | --- |
| Frameworks | React 19, Vue 3 |
| Bridge | Inertia.js, Wayfinder, Ziggy |
| State | Pinia, TanStack-style hooks |
| UI | Tailwind CSS 4, Radix UI, Reka UI, Lucide |
| Build | Vite, TypeScript, ESLint, Prettier |

</details>

<details>
<summary><b>Mobile, ML &amp; Other</b></summary>

| Area | Tools |
| --- | --- |
| Mobile | Android (Java / Kotlin), Firebase |
| Machine learning | TensorFlow, VGG16 transfer learning |
| Graphics | Three.js, cannon-es physics |
| Mapping | Leaflet, routing &amp; geocoding |
| Testing | Playwright |

</details>

---

### AI Development Tools

[![Claude Code](https://img.shields.io/badge/Claude_Code-4F46E5?style=flat-square&logo=anthropic&logoColor=white)](https://claude.com/claude-code)
[![Gemini CLI](https://img.shields.io/badge/Gemini_CLI-4F46E5?style=flat-square&logo=googlegemini&logoColor=white)](https://github.com/google-gemini/gemini-cli)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-4F46E5?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Laravel Boost](https://img.shields.io/badge/Laravel_Boost-4F46E5?style=flat-square&logo=laravel&logoColor=white)

<details>
<summary><b>How I use them</b></summary>

| Tool | Use |
| --- | --- |
| Claude Code | Primary coding agent for scaffolding, refactors, and review passes. Configured per repository with a checked-in `CLAUDE.md` so conventions carry across sessions. |
| Gemini CLI | Secondary agent for exploration and cross-checking approaches on larger changes. |
| Model Context Protocol | MCP servers wired into the editor so agents can inspect the running application instead of guessing at it. |
| Laravel Boost | MCP server exposing routes, Eloquent models, and schema to the agent during development. |
| Herd MCP | Local Laravel Herd site control from the same MCP setup. |

Agent configuration is committed alongside the code, so the setup is reproducible for anyone
picking up the project.

</details>

---

### Selected Work

<details open>
<summary><b>Government &amp; Public Sector</b></summary>

| Project | Stack | Description |
| --- | --- | --- |
| Barangay E-Services Management | Laravel &middot; Filament | Resident and household registry, blotter and hearing records, document requests, and payment collections. |
| Business Permit &amp; Licensing | Laravel &middot; Vue | Permit workflow with requirement checklists, fee schedules, payments, renewals, and QR-verified certificates. |
| Decision Support System | Laravel &middot; React | Income-generating project tracking with milestones, document management, activity logs, and Excel / PDF reporting. |

</details>

<details>
<summary><b>Education</b></summary>

| Project | Stack | Description |
| --- | --- | --- |
| Science Literacy Platform | Laravel &middot; Vue | Modules, lessons, and assessments with per-student progress tracking, badges, and certificates. |
| Storm Surge Simulation | Three.js &middot; cannon-es | Interactive 3D model of coastal housing under storm surge conditions for disaster-awareness teaching. |

</details>

<details>
<summary><b>Business &amp; Operations</b></summary>

| Project | Stack | Description |
| --- | --- | --- |
| Water Delivery Operations | Laravel &middot; Filament &middot; Leaflet | Order intake, delivery scheduling and routing, zone pricing, payments and refunds, fuel reporting. |
| Vehicle Rental &amp; Fleet | Laravel &middot; React | Booking engine with driver assignment, document verification, OTP accounts, maintenance logs, payments. |
| Parish Management | Laravel &middot; React | Appointment scheduling, certificate issuance, priest rosters, donations, and budget allocation with audit trail. |

</details>

<details>
<summary><b>Public Repositories</b></summary>

| Project | Stack | Description |
| --- | --- | --- |
| [agent-web](https://github.com/cy-code-stack/agent-web) | Laravel &middot; React | Real estate agent workspace for clients, listings, projects, sales, and incentive tracking, with generated API docs. |
| [bestfit](https://github.com/cy-code-stack/bestfit) | Laravel &middot; Vue | AI styling assistant with body-shape and colour analysis and conversational recommendations. |
| [Coryza-Disease-Prediction](https://github.com/cy-code-stack/Coryza-Disease-Prediction) | Android &middot; VGG16 | Mobile app classifying infectious coryza in poultry from images using a convolutional neural network. |
| [Dentist-Appointment-System](https://github.com/cy-code-stack/Dentist-Appointment-System) | Laravel &middot; Vue | Patient-facing booking, rescheduling, and cancellation for dental clinics. |
| [valentine-invitation](https://github.com/cy-code-stack/valentine-invitation) | React &middot; Framer Motion | Animated interactive invitation page. |

</details>

<sub>Client-owned systems are kept in private repositories and summarised above without identifying details.</sub>

---

### Currently

- Building Laravel 13 applications with Inertia.js, React 19, and Tailwind CSS 4
- Working with Filament 3 for operations and back-office systems
- Improving type safety and test coverage across ongoing projects
