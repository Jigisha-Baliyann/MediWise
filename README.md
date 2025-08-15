# 🩺 MediWise

MediWise is a modern healthcare insights platform that combines **real-time dashboards**, **secure authentication**, and **public health APIs** to deliver actionable medical information to users.  

Built with **Next.js 14**, **TypeScript**, **Tailwind CSS**, **Prisma**, and **NextAuth**, MediWise is designed for scalability, clean developer workflows, and easy deployment.

## ✨ Features

- **User Authentication & Onboarding**  
  Secure login with OAuth providers (GitHub, Google, etc.) using NextAuth.

- **Healthcare Data Integration**  
  Pulls drug and trial information from:
  - [OpenFDA Drug Label API](https://open.fda.gov/apis/drug/label/)
  - [ClinicalTrials.gov API](https://clinicaltrials.gov/api/)

- **Real-time Data Visualization**  
  Live health metric charts powered by Pusher (or demo simulated data).

- **Responsive UI**  
  Built with Tailwind + shadcn/ui for mobile-first experience.

- **API-First Design**  
  Clean API routes for future mobile app or third-party integration.

## 🚀 Tech Stack

| Category          | Technology |
|-------------------|------------|
| Framework         | Next.js 14 (App Router) |
| Language          | TypeScript |
| Styling           | Tailwind CSS, shadcn/ui |
| Auth              | NextAuth (Auth.js) |
| Database & ORM    | PostgreSQL + Prisma |
| Charts            | Recharts |
| Realtime          | Pusher |
| Validation        | Zod + react-hook-form |

## 📄 License

MIT License — see LICENSE for details.

## 🤝 Contributing

We welcome contributions!
See CONTRIBUTING.md for setup and coding standards.






