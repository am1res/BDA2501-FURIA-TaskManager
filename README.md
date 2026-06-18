# 📋 Task Manager — FURIA Team

**Educational Practice 2025–2026 | BDA-2501 | Web Project Track**

A browser-based Task Manager web application built with HTML5, CSS3, and vanilla JavaScript. Manage your tasks visually with a Kanban board, list view, and dashboard — no login or installation required.

🔗 **Live Demo:** https://am1res.github.io/BDA2501-FURIA-TaskManager

---

## ✨ Features

| Feature | Description |
|---|---|
| ➕ Add Task | Create tasks with title, description, due date, priority, and status |
| 👁️ View Tasks | Kanban board (drag & drop) + flat list view |
| 📊 Dashboard | KPI cards — total, completed, in-progress, and to-do task counts |
| ✏️ Edit Task | Edit any field on an existing task via a pre-filled modal |
| 🗑️ Delete Task | Two-step confirmation delete to prevent accidents |
| 🔍 Search & Filter | Live search + filter by status and priority |
| 🌙 Dark Mode | Full light/dark theme toggle |
| 📱 Responsive | Works on desktop, tablet, and mobile |

---

## 🚀 Getting Started

No installation needed. Just open the live site:

**https://am1res.github.io/BDA2501-FURIA-TaskManager**

Or clone the repo and open `index.html` directly in your browser:

```bash
git clone https://github.com/am1res/BDA2501-FURIA-TaskManager.git
cd BDA2501-FURIA-TaskManager
# Open index.html in your browser
```

---

## 🗂️ Project Structure

```
BDA2501-FURIA-TaskManager/
├── index.html          # Main UI shell, layout, modals, navigation
├── tasks.js            # Central data store + Add Task logic
├── view.js             # Task rendering, dashboard, search & filter
├── edit.js             # Edit modal and update logic
├── delete.js           # Delete confirmation and removal
├── drag.js             # Drag-and-drop Kanban reordering
├── README.md           # Project documentation
├── .nojekyll           # Disables Jekyll processing on GitHub Pages
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions auto-deployment pipeline
```

---

## 👥 Team — FURIA

| Name | Role | Files |
|---|---|---|
| Amir | Team Leader · Frontend Shell · Add Task | `index.html`, `tasks.js` |
| Arsen | View & Dashboard · Search/Filter | `view.js` |
| Dias | Edit Task Feature | `edit.js` |
| Abylay | Delete · Drag & Drop · Deployment | `delete.js`, `drag.js`, `.github/` |

---

## 🛠️ Technologies Used

- **HTML5** — Semantic page structure
- **CSS3** — Custom properties, Grid, Flexbox, dark/light theming
- **Vanilla JavaScript (ES6+)** — All logic, no frameworks
- **GitHub Pages** — Static site hosting
- **GitHub Actions** — Automated deployment on push to `main`

---

## 📄 License

This project was created for educational purposes as part of the Educational Practice 2025–2026 course.
