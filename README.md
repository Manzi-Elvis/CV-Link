# CvLink

> Your CV is no longer a document. It’s a live, shareable experience.

CvLink is a modern Micro SaaS platform that transforms traditional resumes into **dynamic, customizable, and shareable personal websites**.

Instead of sending PDFs that get lost in inboxes, users share a simple link:

 https://cvlink.app/username

---

## Why CvLink?

Hiring has changed — but resumes haven’t.

-  Static PDFs are outdated
-  Hard to track engagement
-  No personalization or branding

CvLink fixes this.

 Beautiful, live CV pages  
 Real-time updates  
 Built-in analytics  
 Personal branding with zero effort  

---

##  The Vision

We’re building the **“Linktree for professional identity”** — a single link that represents your entire career.

Our goal is to become:
- The default resume format
- A hiring intelligence platform
- A global professional identity layer

---

##  Core Features

###  Authentication
- Secure email/password login
- OAuth (Google)
- JWT/session-based auth

###  CV Builder
- Personal profile
- Education & experience
- Skills & projects
- Social links
- Live preview editor

###  Shareable CV Links
- Unique username URLs
- SEO-optimized pages
- Lightning-fast load times

###  Themes
- Modern
- Minimal
- Creative
- (More in Premium)

###  Export
- One-click PDF download
- Instant sharing

###  Analytics (Premium)
- Profile views
- Link clicks
- Engagement insights

###  Monetization
- Free tier
- Premium subscriptions (Stripe)
  - Custom domains
  - Advanced analytics
  - Premium templates

---

## 🏗 Tech Stack

**Frontend**
- Next.js (App Router)
- TypeScript
- Tailwind CSS

**Backend**
- Next.js API Routes

**Database**
- PostgreSQL + Prisma ORM

**Auth**
- NextAuth

**Payments**
- Stripe

**Hosting**
- Vercel + Railway / Supabase

---

##  Security First

- Password hashing (bcrypt)
- Input validation (Zod)
- Rate limiting on auth endpoints
- Secure API design
- Environment-based secrets

---

##  Performance

- Server-side rendering for public CVs
- Optimized assets & images
- Sub-2s page loads
- SEO-ready pages with Open Graph

---

##  Business Model

CvLink is built as a **scalable Micro SaaS**:

| Plan       | Features |
|------------|--------|
| Free       | Basic CV, limited themes |
| Premium    | Custom domain, analytics, premium themes |

 Revenue Streams:
- Monthly subscriptions
- Custom domains
- Future: recruiter tools & hiring insights

---

##  Market Opportunity

-  1B+ global professionals
-  Billions of resumes sent yearly
-  Remote work & personal branding rising

CvLink sits at the intersection of:
- Creator economy
- Professional identity
- Hiring tech

---

##  Getting Started

```bash
git clone https://github.com/yourusername/cvlink.git
cd cvlink

npm install
npx prisma migrate dev
npm run dev
```

##  Roadmap
- AI-powered CV optimization
- Recruiter dashboard
- Public CV discovery
- Template marketplace
- Mobile app

## Contributing

We welcome contributors, builders, and thinkers.

## Final Thought:

In the next decade, nobody will send a PDF resume.
They’ll send a link.

CvLink is that link.