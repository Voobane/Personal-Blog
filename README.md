# 📝 Personal Blog

A two-page personal blog application built with vanilla JavaScript and the Web Storage API. Users can write and submit blog posts on the landing page, then view all saved posts on the blog page — with a light/dark mode toggle and full localStorage persistence.

---

## 📖 Overview

This project demonstrates how to build an interactive multi-page app using only HTML, CSS, and JavaScript — no frameworks. It uses `localStorage` to persist data across pages and sessions, and separates concerns cleanly into distinct JS files for each page.

---

## ✨ Features

- 📬 Submit blog posts with username, title, and content
- 💾 Posts saved to `localStorage` as a JSON array — persist after refresh
- 🚫 Form validation — alerts the user if any field is left blank
- 📄 Blog page renders all saved posts dynamically from storage
- 🌗 Light / dark mode toggle on the blog page
- 🔙 Back button returns to the submission form

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (three separate stylesheets) |
| Logic | Vanilla JavaScript (Web Storage API) |
| Deployment | GitHub Pages |

---

## 🚀 Getting Started

No install required — open directly in a browser.

```bash
git clone https://github.com/Voobane/Personal-Blog.git
cd Personal-Blog
open index.html
```

---

## 📁 Project Structure

```
Personal-Blog/
├── index.html          # Blog submission form (landing page)
├── blog.html           # Posts display page
├── assets/
│   ├── css/
│   │   ├── styles.css  # Shared base styles
│   │   ├── form.css    # Landing page styles
│   │   └── blog.css    # Blog page styles
│   └── js/
│       ├── logic.js    # Shared utilities / localStorage helpers
│       ├── form.js     # Form submission and redirect logic
│       └── blog.js     # Post rendering and dark mode toggle
└── README.md
```

---

## 💡 What I Learned

- Reading and writing structured data to **localStorage** as JSON
- Passing state between pages using the **Web Storage API** (no backend needed)
- Separating JavaScript logic per page to keep files focused and readable
- Implementing a **light/dark mode toggle** with CSS and a JS click handler
- Client-side **form validation** without a library

---

## 📸 Screenshots

> _Add screenshots to the repo and update this section._

---

## 👤 Author

**Matt (Voobane)**
- GitHub: [@Voobane](https://github.com/Voobane)
