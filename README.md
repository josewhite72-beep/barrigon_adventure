# 🦦 Barrigón Adventure Platform

A gamified ESL learning Progressive Web App (PWA) for primary school students in Barrigón, Panama.

## 🎯 About

Barrigón Adventure transforms the official MEDUCA English curriculum into an interactive game-based learning experience. Students explore a cartoon-style map of their own community while completing English language activities.

## 🗺️ How It Works

Students navigate an interactive map of Barrigón and unlock locations by completing missions:

| Location | Emoji |
|---|---|
| The School | 🏫 |
| The Shops | 🛒 |
| The Church | ⛪ |
| The River | 🌊 |
| Las Yayas Waterfall | 💧 |
| Omar Torrijos Park | 🌳 |

## 📚 Curriculum Alignment

Aligned with MEDUCA Panama English curriculum for:

- Kinder
- Grade 1
- Grade 2
- Grade 3
- Grade 4
- Grade 5
- Grade 6

Each grade includes **2 scenarios × 2 missions × 5 activities** for Trimestre 1.

## 🎮 Activity Types

Each mission includes 5 activity types:

- 🎧 **Listening** — Text-to-speech with soundwave animation
- 📖 **Reading** — Story-based comprehension
- ✏️ **Writing** — Sentence completion
- 🗣️ **Speaking** — Model sentence + oral production
- 🌐 **Mediation** — Spanish/English bridging

## 🔊 Audio Features

- Web Speech API (Text-to-Speech) — no external APIs needed
- Sound effects for correct/incorrect answers
- Coin reward jingle 🪙
- Background music toggle 🎵
- Works offline after first visit

## 🏗️ Architecture
```
barrigon-adventure/
├── index.html          ← Game engine
├── manifest.json       ← PWA manifest
├── service-worker.js   ← Offline support
└── data/
    ├── gradek.json     ← Kinder content
    ├── grade1.json     ← Grade 1 content
    ├── grade2.json     ← Grade 2 content
    ├── grade3.json     ← Grade 3 content
    ├── grade4.json     ← Grade 4 content
    ├── grade5.json     ← Grade 5 content
    └── grade6.json     ← Grade 6 content
```

## 🚀 Deployment

Hosted on Vercel. Each grade's content is loaded dynamically from its JSON file — the game engine never changes, only the content files grow.

## 🎖️ Game Mechanics

- 🔒 Unlockable map locations
- 🪙 Capibara Coins reward system
- ✅ Mission progress tracking
- 🏆 Completion celebrations
- 📱 Mobile-first design

## 🏫 School

Escuela Primaria de Barrigón, Colón, Panama

## 📄 License

Educational use only. Content aligned with MEDUCA Panama official curriculum.
