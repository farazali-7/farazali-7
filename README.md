# Faraz Ali

Full-stack product engineer. I build healthcare, finance, and commerce web applications, from schema design through to the deployed interface.

Most of my work is operational software: clinic management, finance tracking, admin dashboards. The kind of product where the database model, the permission boundaries, and the interface all have to agree with each other to be worth using.

### What I work on

- **Backend-integrated SaaS.** Relational data models, authentication, role isolation, billing lifecycle.
- **Operational dashboards.** Analytics, order and inventory management, internal tooling.
- **Product interfaces.** Dense, data-heavy UIs built to stay maintainable as they grow.

I tend to own the full path: data model, API, interface, deployment. I care less about the framework of the month and more about whether the system holds up once real data and real users are in it.

### Stack

**Frontend** &nbsp;Next.js (App Router) · React · TypeScript · Tailwind CSS · Shadcn UI · Redux Toolkit
**Backend** &nbsp;Node.js · Express · REST APIs · JWT auth · role-based access control
**Data** &nbsp;PostgreSQL · MongoDB · Supabase (incl. Row Level Security)
**Tooling** &nbsp;Git · Vercel · Postman

### Selected projects

**HealthLuma**, a clinic management SaaS
Separate doctor and patient portals, appointment scheduling, prescriptions, patient records, and subscription billing. It runs on PostgreSQL because prescriptions, appointments, and billing share complex relational joins. Doctor and patient flows are isolated as separate route groups with distinct permission boundaries, and patient data is protected with Supabase Row Level Security.
`Next.js` · `TypeScript` · `PostgreSQL` · `Supabase` · `Stripe`

**Spendify**, a personal finance dashboard
Multi-account tracking, liability management, and net-worth analytics. Transactions link to specific accounts rather than being globally categorized, so balances stay attributable. Sensitive financial data is isolated per user with Supabase RLS.
`Next.js` · `TypeScript` · `PostgreSQL` · `Supabase` · `Shadcn UI`

**ShareABite**, a food donation backend
REST API for a donation platform connecting restaurants with communities. Role-based access for Admin, Eatery, and Restaurant users runs through JWT middleware rather than per-route logic, with a flexible MongoDB schema for variable donation listings and consistent API response contracts.
`Node.js` · `Express` · `MongoDB` · `JWT`

### Links

Portfolio &nbsp;· &nbsp;[farazali.pro](https://farazali.pro)
LinkedIn &nbsp;· &nbsp;[linkedin.com/in/faraz-ali](https://www.linkedin.com/in/faraz-ali-63b67b39b/)
Email &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;· &nbsp;farazbhatti170@gmail.com

Based in Pakistan (GMT+5). Open to remote roles and freelance work.
