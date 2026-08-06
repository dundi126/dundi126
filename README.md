<h1 align="center">Hey! I'm Dundi 👋</h1>
<h3 align="center">Building stuff that matters | CS Grad Student @ UMich</h3>

<p align="center">
  <a href="mailto:dundi@umich.edu"> Email</a> •
  <a href="https://linkedin.com/in/dundi"> LinkedIn</a> •
  <a href="https://dundi-gutti.vercel.app"> Portfolio</a> 
  
</p>

---

## 🚀 What I'm Building Right Now

### Meet.ai – AI Meeting Companion That Actually Works
Ever wished you could have a focused conversation with AI without the ChatGPT UI clutter? Building **meet.ai** - a dedicated meeting interface where you can have deep, recorded conversations with AI that feel more like actual meetings than chat sessions.

**The Vision:** Instead of scrolling through endless ChatGPT threads, you schedule "meetings" with AI, have structured conversations, and get full transcripts + recordings for reference later. Perfect for brainstorming, debugging complex problems, or working through ideas.

**Current progress:**
- ✅ Real-time chat interface with OpenAI API integration
- ✅ User authentication with Better Auth (no more sketchy JWT implementations)
- ✅ Conversation recording and storage in PostgreSQL
- ✅ Auto-generated transcripts using Inngest for background processing
- 🚧 Meeting scheduling and session management
- 🚧 Voice-to-text integration for hands-free conversations
- 📅 Next: Analytics dashboard showing conversation patterns and AI usage metrics

**Stack:** Next.js 14, PostgreSQL, Drizzle ORM, shadcn/ui, Better Auth, OpenAI API, Inngest

**Why this stack?**
- **Next.js 14** – Server actions make API handling clean
- **Drizzle ORM** – Type-safe queries without the bloat of Prisma
- **shadcn/ui** – Beautiful components I can actually customize
- **Better Auth** – Because rolling your own auth in 2025 is asking for trouble
- **Inngest** – Background jobs for transcript processing without blocking the UI

---

### Student ID Wallet – Your entire wallet, digitally
Sick of carrying 5 different cards just to get into the gym, library, dining hall, and pay for stuff? Building a single app to store all student IDs, passes, and payment cards with NFC support.

**The challenge:** Most schools use different card systems (RFID, magnetic stripe, barcodes). Reverse-engineering these without violating security protocols is... interesting.


---

### Screen Mirroring System – Because AirDrop isn't enough
Working on seamless device-to-device screen sharing and file transfer. The goal: share your screen to any device on the same network **without installing anything** on the receiving device.

**Tech exploration:** WebRTC, peer-to-peer protocols, low-latency streaming

---

## 💭 What I'm Learning

- **Swift & iOS Development** – Finally diving into native iOS after years of React/Flutter
- **Microservices Architecture** – Breaking down monoliths (currently reading "Building Microservices")
- **System Design** – Prepping for interviews but genuinely fascinated by how Netflix/Uber scale
- **Prompt Engineering** – LLMs are cool, but making them actually useful is the real challenge
- **Drizzle ORM** – Loving the type-safety without Prisma's overhead

---

## 🛠️ My Go-To Stack

**When I need to ship fast:** Next.js + Tailwind + Vercel  
**When I need it scalable:** FastAPI + PostgreSQL + Docker + AWS  
**When I'm prototyping:** Flutter (cross-platform MVP in days)  
**When I'm learning:** Whatever the project needs (recently: Swift, Better Auth, Drizzle)

<details>
<summary><b>Full tech list (click to expand)</b></summary>

**Languages I actually use:**  
Python • JavaScript/TypeScript • Dart • Java • Swift (learning) • SQL

**Frontend:**  
React • Next.js • Flutter • Tailwind CSS • shadcn/ui • Material-UI

**Backend:**  
FastAPI • Node.js • Express • Laravel • Drizzle ORM • PHP

**Databases:**  
PostgreSQL • MySQL • MongoDB • Redis

**DevOps & Tools:**  
Docker • AWS (EC2, S3, RDS) • Vercel • Firebase • Inngest • Better Auth

**Testing:**  
pytest • Jest • Selenium

</details>

---

## 🔥 Stuff I've Built

**🤖 Multi-Agent AI Consensus Engine**  
Ever wonder if an AI's answer is actually correct? I built a system where 5 different LLaMA agents debate and vote on responses. Reduced hallucinations significantly.

*The interesting part:* Optimized from 8s to 2.5s by running agents in parallel instead of sequentially. Turns out async workflows are magic.

**🍱 Oishii – Full Restaurant Platform**  
Built an entire restaurant management system with online ordering, Stripe payments, and admin dashboard. The hard part wasn't the code—it was understanding PCI compliance and 3D Secure authentication.

*What I learned:* Financial APIs are terrifying but fascinating. Also, optimizing MySQL queries can 10x your app's speed.

**📦 SafeUI – API Wrapper Library**  
Created a TypeScript package that handles API errors gracefully. Your UI won't crash when the backend decides to take a nap.



---

## 🎯 My Engineering Philosophy

**1. Ship first, perfect later** – Perfect is the enemy of done  
**2. Test everything** – 80% code coverage isn't optional  
**3. Security isn't a feature, it's a requirement** – OAuth, encryption, proper auth flows  
**4. Performance matters** – Users won't wait 8 seconds for a response  
**5. Learn by building** – Reading docs is fine, building is better

---

## 🎓 Background

**Currently:** MS in Computer Science @ University of Michigan (2024-2026)  
**Previously:** Worked at a couple startups, built MVPs, shipped production code

I tried to start a company with a friend—we had 45 days to build an MVP for investors. Built a full Flutter app with FastAPI backend while learning OAuth, JWT, and Swift simultaneously. Didn't get the funding, but learned more in those 45 days than in any semester of school.

**Now:** Interning at PM Accelerator, building AI-powered products, and constantly learning new tech.

---

## 💬 Let's Talk

I love chatting about:
- 🚀 Building MVPs and shipping fast
- 🤖 AI/ML applications (especially practical ones, not hype)
- 📱 Web development 
- 🏗️ System design and scalability challenges
- 💡 Side project ideas and startup stuff

**Reach me:** dundi@umich.edu | [LinkedIn](https://linkedin.com/in/dundi)


---

<p align="center">
  <i>"The best code is code that ships."</i>
</p>
