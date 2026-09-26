# Hi, I'm Haris 👋

**Senior Frontend Engineer and Tech Lead (Web + Mobile)** · React, Next.js, React Native · Islamabad, Pakistan

I've spent ~7 years shipping production React, the last 4+ full-time. Today I lead a 12-engineer web and mobile team at Code Huddle, building Next.js and React Native (Expo) products for clients in Denmark, Germany, the UK and the US.

I care about three things: fast interfaces, architecture that survives the second year, and teams that ship without heroics.

---

## 🧭 What I do

- **Lead**: own architecture, sprint planning, PR review and technical hiring for a 12-engineer team. I've run 25+ interviews and mentored 2 engineers to promotion.
- **Build**: Next.js App Router and React Native (Expo) products, multi-tenant Supabase backends with Row Level Security, and realtime features over WebSockets and WebRTC.
- **Make it fast**: Core Web Vitals, payload and query optimization, ISR at scale.
- **Ship AI inside products**: streaming LLM chat interfaces and AI assessment flows. The team runs an agent-native workflow on Claude Code and Cursor that cut our Jira ticket cycle time ~30%.

---

## 🚀 Selected work

> Most of my code lives in private client repositories under NDA, so it doesn't show up in the graph below. I'm happy to walk through the architecture of any of these on a call.

| Product | What I did | Result |
|---|---|---|
| **QOM** · news publishing platform | Moved slot resolution from client-side JS filtering to a database lookup | Homepage DB egress **-85.6%** (1.56 MB to 230 KB), story page HTML **-44%**, parity verified across 136 slugs |
| **[Honest Dog](https://honestdog.de)** · German dog marketplace | Led delivery on Next.js with ISR across 500+ breed pages | **25,000+ registered users**, 90+ Lighthouse, FCP **-40%** |
| **LeadKPI** · multi-tenant SaaS for car dealerships | Architected tenant isolation on Supabase Postgres RLS with super-admin impersonation | 3 dealerships live, thousands of records per tenant |
| **DriverHub** · driver hire, Denmark | Built one Expo app for driver and passenger flows: PostGIS matching, MitID and Veriff identity verification | Shipped to App Store and Google Play |
| **GYMYG** · fitness SaaS | Live training over Daily.co WebRTC with realtime workout sync across web and mobile | Monitored in Sentry |
| **Inform** · AI physiotherapy app | Built the AI assessment flow | Stabilized across 162 tracked defects (admin + mobile) |

---

## 🛠️ Open source and tools

- **Next.js boilerplate generator** (co-architect): scaffolds Next.js 16, React 19, TypeScript and Tailwind 4 projects with 12 auth and ORM combinations. <!-- TODO: add repo / npm link -->
- **Pumble MCP server**: TypeScript on Vercel serverless, 9 tools, so engineers can act on team chat threads and tasks from inside the editor. <!-- TODO: link if the repo is public -->

---

## 🧰 Tech stack

**Frontend and mobile**
![React](https://img.shields.io/badge/React_19-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-1C1E24?style=flat-square&logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)

**State, data and realtime**
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Postgres_%2B_PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)

**Quality, security and delivery**
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

Also: WCAG accessibility, i18n with Arabic RTL, OAuth, CSP, Storybook design systems, CI/CD.

**AI engineering**
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_servers-111111?style=flat-square)

---

## 🤝 How I run a team

- TypeScript strict and ESLint as the baseline, and a written code review standard, so reviews argue about design, not style.
- Features ship with component and end-to-end tests, accessibility and RTL support as standard.
- Agent-facing repo docs (CLAUDE.md, skill libraries), so AI output follows team conventions instead of each person prompting ad hoc.
- Hiring with structured technical interviews for frontend, fullstack and AI roles.

---

## 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haris-ahmed-software-engineer)
[![Email](https://img.shields.io/badge/malikharis629%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:malikharis629@gmail.com)
