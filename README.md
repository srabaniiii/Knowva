# 🧠 Knowva

> **Because knowledge should stay.**

AI-powered knowledge retention platform for modern HR teams. Stop knowledge from walking out the door when employees leave.

## 🚀 Deploy to Vercel (3 steps)

### Option A — Vercel CLI (fastest)
```bash
npm install
npm install -g vercel
vercel
```
Follow the prompts → your app is live in ~60 seconds.

### Option B — GitHub + Vercel Dashboard
1. Push this folder to a new GitHub repo
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo → click **Deploy**

Vercel auto-detects Vite. No config needed beyond `vercel.json`.

## 🛠 Local Development

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173)

## 📦 Build

```bash
npm run build
```

Output goes to `/dist` — ready for any static host.

## 🎯 Demo Credentials

- Click **"Login as NovaTech HR Demo"** on the login screen
- Or use any email/password — auth is simulated

## 🔄 Full Demo Flow

1. **Employees** → Mark **Ananya Sharma** as Resigned
2. Assign **Rahul Mehta** as successor → Confirm
3. Watch **Transitions** auto-populate with the exit flow
4. Check **Dashboard** — Risk Score updates live
5. Try **Ask Knowva AI** → "Show knowledge risk by department"

## 🏗 Tech Stack

- **React 18** + **Vite 5**
- Pure CSS-in-JS (no Tailwind dependency)
- Google Fonts (Outfit + Syne)
- Zero external UI library dependencies

## 📄 Pages

| Route | Page |
|-------|------|
| `/` | Auth (Login / Signup) |
| Dashboard | Overview, stats, activity |
| Employees | Team management + resign flow |
| SOP Vault | Document management |
| Projects | Project tracker |
| Transitions | Auto Exit Flow |
| Analytics | Risk & coverage charts |
| Ask Knowva AI | Intelligent org assistant |
| Billing | Plans & trial management |
