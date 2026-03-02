# Nexish AI — Complete Source Code

A full-featured AI chatbot with 30 AI-powered features, built with React + Tailwind + Base44.

## 30 Features
Generate Images, Videos, Websites · Code Assistant · Writing Helper · Data Analysis
Translation · Summarization · Brainstorming · Q&A Expert · Music Lyrics
Podcast Script · Story Writer · Business Plan · Health Advisor · Math Solver
Travel Planner · Recipe Creator · Fitness Coach · Photo Editing · Science Explainer
News Digest · AI Tutor · Legal Assistant · Art Prompt Gen · Startup Advisor
Shopping Guide · Social Media · Resume Builder · Debate Coach

## Tech Stack
- React 18 + Vite
- Tailwind CSS
- Base44 SDK (AI, image generation, database)
- @tanstack/react-query
- react-markdown, lucide-react, framer-motion, jszip

## File Structure
```
nexish-ai/
├── src/
│   ├── pages/
│   │   └── Chat.jsx                  ← main chat page
│   └── components/chat/
│       ├── WelcomeScreen.jsx          ← 30-feature landing grid
│       ├── FeatureCard.jsx            ← individual feature tile
│       ├── MessageBubble.jsx          ← chat message renderer
│       ├── ChatInput.jsx              ← message input form
│       └── Sidebar.jsx                ← conversation history
├── entities/
│   └── Conversation.json             ← Base44 data schema
├── index.css                         ← Tailwind + CSS variables
├── tailwind.config.js
├── package.json
└── README.md
```

## Getting Started
1. Clone / unzip this project
2. Run: npm install
3. Run: npm run dev
4. Connect your Base44 SDK credentials in src/api/base44Client.js
