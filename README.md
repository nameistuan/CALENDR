# 📅 Calendr

**Calendr** is a modern, lightweight, and **power-user friendly** calendar app.  
Created with a goal of being a better version of Google Calendar — designed to be **faster**, **simpler**, and more **focused** for everyday use.

---

## 🌟 Why Calendr?

Most calendar apps (including Google Calendar) are powerful, but they can feel **clunky**.  
Calendr is designed to be the **calendar you actually want to use daily**:

✅ **Quick & intuitive editing** – Add or change events with just a click or shortcut.  
✅ **Minimal & distraction-free design** – Focus on your schedule, not menus.  
✅ **Built for speed** – Lightweight desktop app that opens instantly.  
✅ **Local-first privacy** – Your events are stored **on your device** by default.

---

## 🎯 The Goal

Calendr isn’t just another calendar — it’s a **better way to organize your life**.  

We want to make an app that:
- **Feels effortless** to use (inline edits, drag & drop, powerful shortcuts)
- **Keeps you productive** with features like smarter reminders and focus mode
- Starts **local-first**, but is built to expand to **sync and collaboration** in the future

---

## 🚀 Planned Features (MVP)

🔹 Month, Week, and Day views  
🔹 Add, edit, delete events quickly  
🔹 Check lists within tasks/events.  
🔹 Time blocked Todo tasks.   
🔹 Scrolling with mouse wheel.  
🔹 Simple reminders (local notifications)  
🔹 Keyboard shortcuts for power users  
🔹 Clean, Tailwind-powered UI  
🔹 Authentication and account syncing.  

---

## 🌈 Future Ideas

✨ **Natural language input** (“Dinner with Alex next Friday at 7 PM”)  
✨ **Recurring event templates** (like a “Workout routine” you can drop on your week)  
✨ **Optional sync** (cloud or self-hosted, your choice)  
✨ **AI suggestions** for scheduling & reminders  
✨ **Collaboration features** (shared calendars, invites)

---

## 🛠 Tech Stack (so far)

- ⚡ **[Electron](https://electronjs.org/)** – Desktop app framework  
- ⚛️ **React** – UI library  
- 🎨 **TailwindCSS** – Modern styling  
- 🔧 **Vite** – Fast development & bundling

---

## 📁 Project Structure

```plaintext
Calendr/
├── node_modules/          # Auto-generated; all npm dependencies
├── public/                # Static files (icons, manifest) served as-is
├── src/                   # 💻 All React code lives here
│   ├── assets/            # Images, icons, and other static assets
│   ├── components/        # Reusable UI pieces (Calendar, Sidebar, Buttons)
│   ├── styles/            # Global styling
│   │   └── index.css      # Tailwind’s base + custom styles
│   └── ui/                # Core React app structure
│       ├── App.jsx        # Root React component
│       └── main.jsx       # React entry point (mounts App.jsx to index.html)
│
├── .gitignore             # Files/folders Git should ignore
├── electron-main.js       # Electron’s main process (launches app window)
├── index.html             # Base HTML for React to mount into
├── package-lock.json      # Auto-generated lockfile for npm versions
├── package.json           # Project metadata + dependencies + scripts
├── postcss.config.js      # PostCSS/Tailwind setup
├── README.md              # Project documentation (you’re reading it!)
├── tailwind.config.js     # Tailwind customization (themes, colors)
└── vite.config.mjs        # Vite config for bundling React

```

---

## 📌 Status

🚧 **Work in progress!** This is an early version of Calendr.  
The current focus is on:
- Setting up the project foundation
- Building a simple calendar UI
- Local event storage

---

## 📥 Getting Started (coming soon)

Instructions for running Calendr locally will go here once the app has a stable dev setup.

---

## 📜 License

MIT License — free to use and modify.