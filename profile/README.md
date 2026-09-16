<div align="center">

# 👋 Hi, I'm A Stockmans

### Full-stack developer & infrastructure owner — C# / .NET, PHP / Laravel, JavaScript

I build applications end to end — database design, UI/UX, backend, frontend,
and polish — and then host and secure them myself. Below are curated,
sanitized excerpts of real production and school projects, grouped by stack.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/antoine-stockmans)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:a.stockmans@hotmail.com)
[![Websexpert](https://img.shields.io/badge/Websexpert-0b1230?style=for-the-badge&logo=googlechrome&logoColor=4ade80)](https://www.web-designs.eu)

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET MAUI](https://img.shields.io/badge/.NET_MAUI-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Hosting-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## 🛠️ What I actually do, end to end

Most portfolios stop at "I write code." Mine doesn't, because the work
doesn't either:

| Stage | What that covers |
|---|---|
| **Database & data modeling** | Schema design (Oracle Data Modeler, EF Core, Eloquent migrations), from a blank page to a live, evolving production database |
| **UI/UX & mockups** | From a first sketch/wireframe to a working design system, shared consistently across web and mobile (see [Colors.xaml](https://github.com/Voorbeelden/AnglerMobile/blob/main/Resources/Styles/Colors.xaml) vs. the web version's own CSS) |
| **Backend** | ASP.NET Core MVC, Laravel/PHP, REST API design, business logic, authentication & authorization |
| **Frontend** | Blade + Alpine.js + Tailwind, .NET MAUI/XAML, and plain hand-written HTML/CSS/JS with no framework at all |
| **Infrastructure & hosting** | Server provisioning and hardening, domain/DNS management, SSL certificate issuance and renewal, ongoing maintenance — I don't hand this off to a hosting provider, I *am* the hosting provider for these projects |

That last row is easy to skip on a developer portfolio, so it's worth
naming directly: through **[Websexpert](https://www.web-designs.eu)**, I
design, build, host and secure websites, webshops and small SaaS platforms
for Belgian SMEs — end-to-end, on infrastructure I manage myself. See
[Infrastructure & Hosting](#-infrastructure--hosting) below for specifics.

## 📂 Projects

### C# / .NET

| Project | What it is | Stack |
|---|---|---|
| [**AnglerHub Mobile**](https://github.com/Voorbeelden/AnglerMobile) | Offline-first .NET MAUI app for a fishing competition platform — SQLite sync queue, on-device OCR, XAML UI sharing a design system with the web version. | .NET MAUI · XAML · MVVM · SQLite |
| [**Automated Staff Scheduling App**](https://github.com/Voorbeelden/.NetCoreApp) | ASP.NET Core MVC app for lesson/staff scheduling — database-first design, EF Core migrations, a generic CRUD/search layer. | ASP.NET Core MVC · EF Core · SQL Server |

### PHP

| Project | What it is | Stack |
|---|---|---|
| [**AnglerHub API**](https://github.com/Voorbeelden/AnglerApi) | The Laravel REST API behind AnglerHub Mobile — Sanctum auth, capability-based authorization, idempotent offline-sync endpoints. | Laravel · Eloquent · Sanctum |
| [**AnglerHub Web**](https://github.com/Voorbeelden/AnglerWeb) | The traditional, session-based Laravel/Blade side of the same app — screenshots included. Account security self-service, Form Requests, a reusable Alpine.js/Tailwind component layer. | Laravel · Blade · Alpine.js · Tailwind |

### HTML / CSS / JavaScript

| Project | What it is | Stack |
|---|---|---|
| [**Web Fundamentals**](https://github.com/Voorbeelden/htmlCSS) | A small, framework-free component demo — design tokens, fluid type, an accessible nav toggle, `prefers-reduced-motion` support. No build step. | HTML5 · CSS3 · vanilla JS |

**A look at AnglerHub Web** ([full screenshot set →](https://github.com/Voorbeelden/AnglerWeb#screenshots)):

<img src="https://raw.githubusercontent.com/Voorbeelden/AnglerWeb/main/docs/screenshots/homepage.png" width="600" alt="AnglerHub marketing homepage">

## 🌐 Infrastructure & Hosting

Through **[Websexpert](https://www.web-designs.eu)**, I run a small web
design and hosting business alongside development work — websites,
webshops and SaaS platforms for Belgian SMEs, built *and* hosted by the
same person, end to end:

<img src="https://raw.githubusercontent.com/Voorbeelden/.github/main/profile/images/websexpert-homepage.png" width="600" alt="Websexpert homepage"> <img src="https://raw.githubusercontent.com/Voorbeelden/.github/main/profile/images/websexpert-services.png" width="600" alt="Websexpert services overview">

- **Server management** — provisioning, hardening and ongoing maintenance
  of the servers client projects run on, rather than outsourcing hosting
  to a third party.
- **Domains & DNS** — registration, DNS configuration and renewal
  management for client domains.
- **SSL/TLS certificates** — issuance and automatic renewal, so every
  client site runs on HTTPS without manual intervention.
- **Security-minded defaults, shipped as standard** — GDPR-compliant
  cookie/consent handling, invisible spam protection (reCAPTCHA +
  honeypot fields, no scrapeable contact details in page source), and a
  full audit log of every login attempt on the client-owner admin area.
- **Shared database, website + mobile app** — client projects that need
  both a website and a companion mobile app run on one central database,
  not two separately-synced copies — the same architecture shown in the
  AnglerHub repositories above.

---

<div align="center">

**Every project above is a curated, sanitized excerpt — not the full codebase.**
Real client/employer names, credentials and connection strings are never included.
Each repo's own README explains exactly what was left out and why.
Happy to walk through the full codebase live in an interview.

</div>
