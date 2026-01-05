# 📝 Smart Task Manager

A modern, lightweight task management web application built with vanilla JavaScript, featuring task categorization, filters, persistent storage, and an LRU-based recent tasks tracker.

---

## 🚀 Features

- ✅ Add, complete, and delete tasks
- 🗂️ Categorize tasks (Work, Study, Personal, Other)
- 🔍 Filter tasks by status (All / Active / Completed)
- ♻️ LRU (Least Recently Used) logic to track recently accessed tasks
- 💾 Persistent storage using browser `localStorage`
- 🌙 Light / Dark mode toggle
- ⌨️ Keyboard support (Enter to add, Esc to clear)
- 📊 Real-time task statistics
- 📱 Fully responsive and clean UI

---

## 🧠 LRU Logic (Highlight)

The application uses an **LRU cache strategy** to maintain a list of recently accessed tasks.
Whenever a task is added, completed, or toggled, it is marked as most recently used.
Only the latest *N* tasks are retained in the LRU list, simulating real-world cache behavior.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **Browser APIs** (`localStorage`)
- **Vanilla JS (no frameworks)**

---

## 🌐 Live Demo

👉 **Live Site:**  
https://msk-1710.github.io/smart-task-manager/


