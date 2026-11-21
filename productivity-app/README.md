# StudyFlow — Smart Productivity for Students

![Version](https://img.shields.io/badge/version-2.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20PWA-purple)

<p align="center">
  <strong>⚡ A premium, offline-first productivity suite built for B.Tech & CS students</strong>
</p>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📋 **Smart Tasks** | Priorities, categories (Study/Project/Exam/DSA/Assignment), due dates, notes, filters |
| ⏱️ **Focus Timer** | Pomodoro (25/5/15/45 min modes) with circular progress, task linking |
| 🎵 **Ambient Sounds** | 8 built-in sounds (Rain, Fire, Café, Wind, Waves, Birds, White/Brown noise) |
| 🔔 **Reminders** | Date/time reminders with snooze, daily/weekly repeat, browser notifications |
| 📅 **Schedule** | Weekly class timetable planner with time blocks |
| 🎯 **Habit Tracker** | Daily habits with 7-day dot grid and streak counter |
| 📊 **Analytics** | Canvas bar charts, 28-day heatmap, focus history, weekly summaries |
| 🔍 **Global Search** | Search across tasks, reminders, habits, and schedule (Ctrl+K) |
| ⌨️ **Keyboard Shortcuts** | Full shortcut system for power users |
| 🌗 **Dark/Light Theme** | Smooth theme switching with iOS-style glassmorphism |
| 💾 **Data Backup** | JSON export/import for data portability |
| 📱 **PWA Support** | Installable as a native-like app with offline caching |

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/studyflow.git

# Open in browser
cd studyflow
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

No build tools, no dependencies, no server required. Just open `index.html`.

## 🏗️ Project Structure

```
studyflow/
├── index.html          # Complete app (HTML + CSS + JS)
├── manifest.json       # PWA manifest
├── sw.js               # Service worker for offline support
├── LICENSE             # MIT License
└── README.md           # This file
```

## 🎨 Design System

- **iOS Glassmorphism** — Frosted glass cards with backdrop blur
- **8px spacing grid** — Consistent spacing with CSS custom properties
- **Spring animations** — Smooth micro-interactions on every element
- **Responsive** — Adapts from desktop to tablet
- **Accessibility** — Semantic HTML, keyboard navigation, proper contrast

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1` - `8` | Navigate between pages |
| `N` | New task |
| `Space` | Start/pause timer |
| `Ctrl+K` | Global search |
| `?` | Show shortcuts overlay |
| `Esc` | Close modals |

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, backdrop-filter, animations, grid/flexbox
- **Vanilla JavaScript** — Zero dependencies
- **Web Audio API** — Ambient sound generation
- **Canvas API** — Analytics charts
- **Service Worker** — Offline caching (PWA)
- **LocalStorage** — Persistent data storage

## 📦 Deploy as SaaS

The app is ready for static hosting:

```bash
# Deploy to Netlify
npx netlify-cli deploy --prod --dir .

# Deploy to Vercel
npx vercel --prod

# Deploy to GitHub Pages
# Just push to main and enable Pages in repo settings
```

## 🗺️ Roadmap

- [ ] Cloud sync with Firebase/Supabase
- [ ] User authentication
- [ ] Collaborative study groups
- [ ] Spaced repetition flashcards
- [ ] Calendar integration
- [ ] Mobile app (React Native / Capacitor)

## 📄 License

MIT License — free for personal and commercial use.

---

<p align="center">
  Built with ❤️ for students, by students<br>
  <strong>⚡ StudyFlow</strong> — Focus Smarter, Achieve More
</p>
