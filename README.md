# 3D AI Chatbot

A portfolio-ready AI chatbot UI with an animated Three.js assistant, responsive conversation interface, demo AI mode, and an API-ready architecture.

## Features
- Interactive 3D AI orb with floating particles and thinking animation
- Responsive desktop/mobile chat layout
- Quick prompts, typing state, copy, regenerate, clear/new chat
- Dark/light theme and animation toggle
- Demo responses work without an API key
- API-ready frontend; keep real AI secrets on a backend/serverless function

## Run locally
```bash
npm install
npm run dev
```

## Connect a real AI provider
Create a server endpoint such as `/api/chat` and keep your provider key in a server-side environment variable such as `AI_API_KEY`. Never put secret keys in `VITE_*` variables or frontend source.

## Deploy
This is a standard Vite React app and can be deployed to Vercel, Netlify, Cloudflare Pages, or another static host. Add your serverless API separately if you want real AI responses.

## Stack
React + TypeScript + Vite + Three.js + React Three Fiber + Drei + Lucide.
