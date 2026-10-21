# ResolveAI Support Desk

A responsive AI-powered customer support dashboard demo built with React, Vite, Recharts, Lucide icons, and plain CSS.

## Included
- Overview dashboard with ticket KPIs, charts, priority queue, recent activity, and agent workload
- Inbox with searchable/filterable tickets, message threads, status and priority changes, assignment, internal notes, reply composer
- Demo AI reply drafting with friendly/professional/concise tones and conversation summary
- Customer directory and ticket navigation
- Searchable knowledge base with article preview, create article, and insert article into reply
- Analytics dashboard with charts and team performance
- Workspace settings and AI preference toggles
- Responsive sidebar/mobile navigation, notification popover, toast messages, and local persistence for ticket updates

## Requirements
- Node.js 18 or newer
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```

## Important demo notes
- AI suggestions are deterministic demo responses. No real AI provider/API is connected.
- Ticket changes are stored in browser `localStorage`.
- Authentication, shared database, email delivery, team synchronization, and live customer integrations are not configured.
- Charts and some analytics use sample/demo data.

## Project structure
```
ResolveAI-source/
├── index.html
├── package.json
├── README.md
└── src/
    ├── main.jsx
    └── styles.css
```
