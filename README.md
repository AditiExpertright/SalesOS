# SalesOS Pro — AI Sales CRM

A fully self-contained, single-file AI-powered Sales CRM with outreach tools for Email, LinkedIn, Twitter, and Instagram.

## ✨ Features

- **Sales CRM** — Leads table with stages, deal values, priority, lead scoring, and temperature (hot/warm/cold)
- **Team & Assignments** — Assign leads to team members, track Wikipedia/Contractual/Full-time work per member
- **Pipeline View** — 7-stage Kanban (New → Won/Lost)
- **AI Compose** — Write outreach messages for Email, LinkedIn, Twitter, Instagram using Claude AI
- **Outreach Sequences** — AI-generated multi-step cadences
- **Follow-up Scheduler** — Track overdue, today, and upcoming follow-ups
- **Message Templates** — Save and reuse message templates
- **AI Tools Hub** — 15 AI-powered sales tools (lead scoring, objection handling, pitch builder, etc.)
- **Analytics** — Charts for pipeline, work type, team performance, and channel distribution
- **Import/Export CSV** — Bulk import and export leads

## 🚀 Deploy on Vercel (1 minute)

### Option A — Vercel Dashboard (easiest)
1. Fork or upload this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo
4. Leave all settings as default — click **Deploy**
5. Done ✅

### Option B — Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

### Option C — Drag & Drop
1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag the entire project folder into the browser
3. Deploy instantly

## 🔑 Setting Up Your API Key

After deploying, open the app → go to **Settings** → paste your **Anthropic API key**.

Get a free API key at [console.anthropic.com](https://console.anthropic.com)

> **Note:** Your API key is stored only in your browser's localStorage — it never leaves your device.

## 💻 Run Locally

Just open `index.html` in any browser. No server needed.

## 📁 Project Structure

```
salesos-pro/
├── index.html      ← The entire app (self-contained)
├── vercel.json     ← Vercel deployment config
└── README.md       ← This file
```

## 🛠 Tech Stack

- Vanilla HTML/CSS/JavaScript — zero dependencies, zero build step
- Claude AI (Anthropic) for message generation
- localStorage for data persistence
- Deployed as a static site on Vercel

## 📤 Sharing With Your Team

Once deployed on Vercel, share the URL with anyone on your team. Each person will have their own data stored in their browser.

## 📋 CSV Import Format

Your CSV should have these column headers (all optional except name/email):

```
name, company, role, email, phone, linkedin, twitter, instagram, tags, notes
```
