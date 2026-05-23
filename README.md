# StudyFlow
# 📚 StudyFlow - Assignment Tracker

> A lightweight, single-file web application for tracking assignments, practica, and academic tasks. Runs completely offline with zero backend, stores data in your browser, and features smart backup tools to keep your data safe.

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![Works Offline](https://img.shields.io/badge/Works-Offline-orange)

---

## 📖 Overview
**StudyFlow** is designed for students who want a fast, reliable way to organize coursework without subscribing to bloated software. It runs as a single HTML file (`Progress Tracker.html`) directly in your browser. No installation, no accounts, and no servers required.

All data—including tasks, custom types, and activity logs—is stored securely in your browser's local storage, with a robust **Export/Import system** that allows you to move your data across devices or backup files effortlessly.

---

## ✨ Features
- 📊 **Interactive Dashboard** – Real-time statistics (Total, Completed, In Progress, Overdue), progress doughnut chart, and type distribution graph.
- 📝 **Full Task Management** – Create, edit, duplicate, and delete tasks with priority levels (Low/Medium/High) and due dates.
- 🔧 **Custom Task Types** – Add your own categories (e.g., "Assignment", "Practica", "Reading") with custom color codes.
- 🔢 **1-Click Section Generator** – Instantly generate numbered sections for complex tasks using the "Quick Sections" tool.
- ✅ **Section-Level Tracking** – Mark individual sections as done with visual progress bars for each task.
- 🔍 **Smart Filtering & Sorting** – Filter tasks by Type, Status (Pending/In Progress/Completed), or search by name. Sort by Date, Progress, or Due Date.
- 💾 **Auto-Save** – Data is saved automatically to your browser session as you work.
- 📦 **Portable Backup System** – 
  - **Export:** Download your entire workspace as a `.json` file.
  - **Import:** Restore from a backup file with options to **Merge** (add to existing) or **Replace** (overwrite) your data.
- 📱 **Responsive Dark UI** – Optimized for desktop and mobile with a distraction-free dark mode.

---

## 🚀 Quick Start

### Option 1: Run Locally (Recommended)
1. Download `Progress Tracker.html` to your computer.
2. Double-click the file to open it in any modern browser (Chrome, Firefox, Edge, Brave).
3. **Done!** Start tracking your tasks immediately.

### Option 2: Host on GitHub Pages
1. Create a new repository on GitHub.
2. Upload `Progress Tracker.html` (and optionally a `manifest.json` for PWA features).
3. Enable **GitHub Pages** in repository Settings.
4. Access your tracker from anywhere via `https://yourusername.github.io/repo/`.

---

## 💾 Data Management & Portability

Since this app runs locally, your data lives in your browser. To ensure you never lose it:

| Action | How To |
|--------|--------|
| **Auto-Backup** | The app saves changes instantly. Your work persists even if you close the tab. |
| **Export Data** | Click **`Export Data (.json)`** in the sidebar to download a backup file to your computer. |
| **Import Data** | Click **`Import Data (.json)`**. You can choose to **Merge** with current data or **Replace** it entirely. |
| **Move Devices** | Export the JSON file from one device/browser, then Import it on the new one. |

> ⚠️ **Note:** Clearing your browser's "Site Data" or "Local Storage" will delete unsaved tasks. Always keep a JSON backup!

---

## 🛠 Tech Stack
- **Core:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Storage:** `localStorage` API for offline persistence
- **Visuals:** CSS Variables, Flexbox/Grid, SVG Icons
- **External Libs:** Chart.js (via CDN for dashboard analytics), Inter Font

---

## 📸 Screenshots
<img width="1920" height="1080" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/bd1b04ee-4aaf-4ccd-822b-b5b4394acdf8" />
<img width="1920" height="1080" alt="Screenshot (79)" src="https://github.com/user-attachments/assets/4c5ce15b-57ff-4202-9b54-af9e155d06e8" />
<img width="1920" height="1080" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/6acf09c5-ea8c-43dc-8cb2-2a5762db6c7b" />
<img width="1920" height="1080" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/9cb281a6-8541-400d-a470-29346f291c23" />
<img width="1920" height="1080" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/a53eb1b6-9977-4e88-8095-4449edf06cac" />
<img width="1920" height="1080" alt="Screenshot (75)" src="https://github.com/user-attachments/assets/50e3da33-8eba-4a00-bbb0-96989f8a6dd0" />
<img width="1920" height="1080" alt="Screenshot (82)" src="https://github.com/user-attachments/assets/745d94b7-a518-414b-9c15-e2af09406ca5" />


---

## 🗺 Future Roadmap
- [ ] 🔗 **Google Sheets Sync:** Backend integration for cross-device sync using Google Sheets as a database.
- [ ] 📅 **Calendar View:** Visual calendar layout for upcoming deadlines.
- [ ] 🔔 **Notifications:** Browser-based alerts for overdue tasks.
- [ ] 🌐 **Multi-User Support:** Shared workspaces for group projects.

---

## 📄 License
This project is open-source and available under the MIT License.

**Built for students, by a creative minded student.** 🎓
