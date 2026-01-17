### Hi there!

#### Software Engineer | DevOps Engineer | Backend Engineer | Full stack developer
#### Former Oil Lubricant Specialist | Varia Vantaa Alumni | Hive Helsinki Alumni | 42 Alumni


Welcome to my GitHub profile! I’m a dedicated learner exploring the intersections of programming, data analysis, and software development.

My current GitHub commit rankings in Finland, according to [committers.top](https://committers.top/finland):

[![committers.top badge](https://user-badge.committers.top/finland/RychkovIurii.svg)](https://user-badge.committers.top/finland/RychkovIurii)  
[![committers.top badge](https://user-badge.committers.top/finland_public/RychkovIurii.svg)](https://user-badge.committers.top/finland_public/RychkovIurii)  
[![committers.top badge](https://user-badge.committers.top/finland_private/RychkovIurii.svg)](https://user-badge.committers.top/finland_private/RychkovIurii)  

*Latest joke:  
I scored 5.0/5.0 at Varia, yet my espresso machine still returns `HTTP 418: I'm a teapot` when I ask for coffee.*

---
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,cpp,cs,py,js,ts,bash,powershell,r,linux&perline=10" alt="Core languages and shells" />
  </a>
</p>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vim,nginx,nodejs,pnpm,react,vite,express,nextjs,html,css,php,wordpress,tailwind,postman,jest,vitest,mysql,postgres,mongodb,sequelize,sqlite,redis,prometheus,cloudflare,gcp,aws,docker,ansible,git,github,githubactions,vscode&perline=10" alt="Frameworks, databases, and tooling" />
  </a>
</p>

---

**Other:** GCC, Fastify, Pytest, RStudio, Mongoose, 2FA, JWT, Keycloak, Strapi, WebSocket, GDPR, Infrastructure, Web Scrapers, AI integration (local & cloud), VPS, VPN, Hetzner, Oracle    
## Projects  

### Software Development / Systems Programming

- [**webserv**](https://github.com/RychkovIurii/webserv_42)  
[![Build](https://github.com/to0nsa/webserv/actions/workflows/build.yml/badge.svg)](https://github.com/to0nsa/webserv/actions/workflows/build.yml)
[![Test](https://github.com/to0nsa/webserv/actions/workflows/test.yml/badge.svg)](https://github.com/to0nsa/webserv/actions/workflows/test.yml)
[![Docs](https://github.com/to0nsa/webserv/actions/workflows/docs.yml/badge.svg)](https://github.com/to0nsa/webserv/actions/workflows/docs.yml)  
  Lightweight HTTP/1.1 server in modern C++20 built for the Hive/42 specification. Ships a poll-based event loop, CGI execution sandbox, and Nginx-style configuration parser. CI tracks build/docs/license badges and enforces clang-tidy, clang-format, and editorconfig with docs deployed via GitHub Pages.  
  *Tech stack: C++, GDB, Valgrind, Python, pytest, Nginx, ApacheBench, Siege, Docker, GitHub Actions*  
  *Highlights: RFC 7230–7235 compliance, keep-alive connection reuse, automated tooling pipeline*

- [**CPP Modules**](https://github.com/RychkovIurii/CPP)  
  Complete 42 C++ module curriculum covering canonical OOP forms, templates, STL containers, polymorphism, exception safety, and concurrency primitives through progressively harder exercises.  
  *Tech stack: C++, GDB, Valgrind, Python*  
  *Highlights: Modern C++ idioms, design-by-interface practice, rigorous memory/resource management*

- [**miniRT**](https://github.com/RychkovIurii/miniRayTracer)  
  A minimalist ray tracer written in C using MLX42. Built to render 3D graphics efficiently with a strong focus on single-threaded optimization.  
  *Tech stack: C, MLX42, KCachegrind*

- [**minishell**](https://github.com/RychkovIurii/minishell)  
  A Unix-like shell that handles parsing, redirections, pipes, signals, and built-in commands.  
  *Tech stack: C, GDB, Valgrind*

- [**Philosophers**](https://github.com/RychkovIurii/Philosophers)  
  A concurrency project solving the Dining Philosophers problem using threads and semaphores. Focused on synchronization and deadlock avoidance.  
  *Tech stack: C, GDB, Valgrind*

- [**42cursusLibft**](https://github.com/RychkovIurii/42cursusLibft)  
  Custom implementation of selected libc functions, including memory management, string operations, and linked list utilities.  
  *Tech stack: C, GDB, Valgrind*

---

### DevOps & Infrastructure

- [**Inception**](https://github.com/RychkovIurii/inception)  
  Automated Docker Compose stack following the 42 Inception brief: orchestrates Nginx, WordPress, and MariaDB with custom networks, persistent volumes, TLS, and health checks behind reproducible make targets.  
  *Tech stack: Docker, Docker Compose, Makefile, MySQL, WordPress, PHP*  
  *Highlights: Infrastructure as code, container hardening, reproducible environment bootstrap*

- **DevOps footprint**  Continuous integration, container orchestration, and automated testing pipelines are also embedded in [webserv](https://github.com/RychkovIurii/webserv_42), [Arcade Transcendence](https://github.com/RychkovIurii/Arcade-Transcendence) and [Boardgamecafe](https://github.com/RychkovIurii/boardgamecafe), leveraging Docker, Docker Compose, Prometheus, GitHub Actions, Dependabot, Jest, Vitest and load-testing suites.


- **Automation & Cloud Operations**  
Experienced in using Ansible for deployment automation and configuration management across multiple environments.
Deployed and maintained VPN infrastructures using WireGuard, OpenVPN, and X-Ray (VLESS Reality).
Active user of AWS, Cloudflare, OVH, Oracle Cloud and Hetzner Cloud, focusing on secure, efficient, and reproducible setups. Familiar with GCP services.

- **Lead Intelligence Platform (private project)**  
Developed an automated lead generation and scoring system for M&A professionals targeting Nordic SMEs.
The platform discovers businesses for sale, enriches company data from public registries, scores leads, and provides valuation estimates.
Highlights: data automation, enrichment pipelines, and business intelligence integration.
---

### Web Development

- [**Arcade Transcendence**](https://github.com/RychkovIurii/Arcade-Transcendence)
 [🔗 Live Demo](https://irychkov.com)(https://irychkov.com)  
[![Backend CI](https://github.com/juusokasperi/ft_transcendence/actions/workflows/BackendCI.yml/badge.svg)](https://github.com/juusokasperi/ft_transcendence/actions/workflows/BackendCI.yml)
[![Frontend CI](https://github.com/juusokasperi/ft_transcendence/actions/workflows/FrontendCI.yml/badge.svg)](https://github.com/juusokasperi/ft_transcendence/actions/workflows/FrontendCI.yml)
[![Makefile CI](https://github.com/juusokasperi/ft_transcendence/actions/workflows/MakefileCI.yml/badge.svg)](httpsgithub.com/juusokasperi/ft_transcendence/actions/workflows/MakefileCI.yml)
[![Prod Build CI](https://github.com/juusokasperi/ft_transcendence/actions/workflows/ProdBuildCI.yml/badge.svg)](https://github.com/juusokasperi/ft_transcendence/actions/workflows/ProdBuildCI.yml)
[![Syntax Check](https://github.com/juusokasperi/ft_transcendence/actions/workflows/SyntaxCheck.yml/badge.svg)](https://github.com/juusokasperi/ft_transcendence/actions/workflows/SyntaxCheck.yml)

  A distributed, microservices-based gaming platform featuring a fully playable 3D Pong game, real-time matchmaking, tournaments, live chat, user presence tracking, and a full DevOps stack supporting scalable, production-ready infrastructure.

  *Tech stack: React, Vite, TypeScript, TailwindCSS, Babylon.js, Node.js, Fastify, SQLite, Redis, WebSockets, Docker, Docker Compose, Nginx, PNPM (monorepo), GitHub Actions, Prometheus, Grafana, ELK Stack (Elasticsearch, Logstash, Kibana), Vitest, Prettier, Oracle Cloud, Cloudflare*

- [**Boardgamecafe**](https://github.com/RychkovIurii/boardgamecafe)
 [🔗 Live Demo](https://cafeboardgame.onrender.com) (https://cafeboardgame.onrender.com)  
[![Backend CI](https://github.com/RychkovIurii/boardgamecafe/actions/workflows/BackendCI.yml/badge.svg?branch=main)](https://github.com/RychkovIurii/boardgamecafe/actions/workflows/BackendCI.yml)
[![Frontend CI](https://github.com/RychkovIurii/boardgamecafe/actions/workflows/FrontendCI.yml/badge.svg?branch=main)](https://github.com/RychkovIurii/boardgamecafe/actions/workflows/FrontendCI.yml)  
  A full-stack web platform for a real-life café offering table and board game reservations, event listings, and a Stripe-powered checkout. Includes multilingual support, working hours logic, and a full admin panel for managing tables, prices, and events.  
  *Tech stack: React, Node.js, Express, MongoDB, Mongoose, Stripe, JWT, HTML, CSS, Tailwind CSS, MUI, SweetAlert2, Day.js, libphonenumber-js, express-validator, Moment-Timezone, Nodemailer, bcryptjs, Docker, Docker Compose, GitHub Actions, Dependabot, Jest*

- [**CloudComputing.fi**](https://cloudcomputing.fi)  
 [🔗 Live Demo](https://cloudcomputing.fi) (https://cloudcomputing.fi)  
  A business website built and maintained with a focus on SEO, localization, and CRM integrations using self-written plugins.  
  *Tech stack: SiteGround, Cloudflare, WordPress, PHP, Polylang, Rank Math, Site Kit by Google, Complianz GDPR, custom CRM plugins*

- [**Visit_Central_Asia**](https://github.com/RychkovIurii/Visit_Central_Asia)  
  A hobby project originally built as an info site for Central Asia. Currently evolving into an e-commerce platform with React and MongoDB.  
  *Tech stack: JavaScript, React, MongoDB, HTML,CSS*

---

### Connect with Me  

- 💼 [LinkedIn](https://www.linkedin.com/in/iuriirychkov)  

Feel free to reach out if you’d like to collaborate or discuss interesting projects!



<!--
**RychkovIurii/RychkovIurii** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
