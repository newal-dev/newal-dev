# 👋 Hi, I'm Newal

**Full-Stack Developer · Moving into AI/ML Engineering** · Based in Ethiopia

4th-year Computer Science student (3.94 GPA). I build role-based web systems that real people use, from a logistics company's internal operations platform to an accessible, multilingual job and sign-up plug-in that placed **Top 3 at the ALX Accessibility Hackathon**.

Right now I'm deepening my backend skills and growing into **AI/ML engineering**.

---

## 💼 Experience

**Reflect Logistics and Transport PLC**
Helped design and build the company's internal operations system: a role-based platform (Boss, Operations, Secretary, Finance) for shipments, fleet, customers and finance.
* Shipment lifecycle from request to payment, with a full audit history and invalid status changes rejected
* Settlement invoices calculated server-side and checked against the company's real paper forms, with PDF export
* Document uploads (IDs, licences, vehicle papers) and payment dispute lookup by plate number

**ConDigital · AI Trainer**
Recorded step-by-step demonstrations of real marketing workflows, used as training data to teach AI systems how to carry out those tasks.

---

## 🏆 Featured Projects

### 🔹 Inclusive Access: accessible sign-up and job plug-in · Top 3, ALX Accessibility Hackathon
Built with Team Pixel. A plug-in any website can add with two lines of code, offering accessible sign-up, job search and job applications, plus a form for employers to post jobs.
* Works in **six languages**: English, አማርኛ, Afaan Oromoo, ትግርኛ, Soomaali and Sidaamu Afoo
* Voice input and read-aloud on every step; full keyboard and screen-reader support (NVDA, TalkBack)
* Web Component in Shadow DOM, so the host site's CSS can't break it
* REST API with an OpenAPI spec, LTI 1.3 launch for learning platforms, schema.org job data
* **150+ automated tests** (unit, voice, API and axe-core browser tests) run on every push
* WCAG 2.2 AA accessibility report

**Tech:** Node.js, Web Components, Docker, Playwright, axe-core, OpenAPI
- **Live:** https://inclusive-access.onrender.com/site/savanna/pages/signup.html
- **Code:** [newal-dev/new-track1](https://github.com/newal-dev/new-track1)

### 🔹 Mini Multi-Tenant Property Listing Platform
Role-based property listing platform with Admin, Owner and User roles. Built end-to-end and deployed live.
* JWT auth with role-based access control enforced at the middleware, service and database level
* Transactional property publishing (validated atomically via Prisma `$transaction`)
* Cloudinary image upload with server-side type and size validation
* Soft deletes, database-enforced unique constraints, pagination and filtering
* Server-side rendered public listings (Next.js) plus protected, role-specific dashboards
* Optimistic UI updates with automatic rollback on failure

**Tech:** Node.js, Express, Prisma, PostgreSQL, Next.js, TanStack Query, JWT, Cloudinary
- **Live:** https://mini-property-listing-platform-khnu.vercel.app/
- **API:** https://mini-property-listing-platform.onrender.com/api
- **Docs:** in-repo technical decision document and Postman collection

### 🔹 Student Management System (EduTrack)
Full-stack student record management system with authentication and CRUD.

**Tech:** PHP, MySQL, JavaScript, Bootstrap
**Demo:** https://student-management-web.kesug.com/login.php

### 🔹 Todo App
Full-stack task manager with JWT authentication, protected routes and personal to-do CRUD.

**Tech:** Node.js, Express.js, React, PostgreSQL, JWT, bcryptjs, Express Validator

---

## 🛠️ Tech Stack

**Languages:** JavaScript, SQL, PHP

**Frontend:** HTML, CSS, React (Vite), Next.js (App Router, SSR), TanStack Query, Web Components

**Backend:** Node.js, Express.js, Prisma ORM, REST APIs, OpenAPI

**Databases:** PostgreSQL, MySQL, SQL Server

**Auth & Cloud:** JWT and bcrypt, Cloudinary, Vercel, Render, Neon

**Testing & Tools:** Playwright, axe-core, Docker, GitHub Actions, Git, Postman, VS Code

---

## 🧠 Currently Learning

* Machine learning fundamentals and building applications on top of AI models
* Data structures and algorithms
* System design and production deployment

---

## 📫 Connect With Me

* LinkedIn: [linkedin.com/in/newal-mohammed1](https://www.linkedin.com/in/newal-mohammed1)
* Email: newalelias71@gmail.com

---

## 📊 GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=newal-dev&show_icons=true&theme=tokyonight)

![GitHub Streak](https://streak-stats.demolab.com/?user=newal-dev)
