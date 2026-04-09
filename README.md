# GitHub Issues Tracker

A clean, responsive web app to track and manage GitHub-style issues — with login, real-time search, status filtering, priority badges, and a detailed modal view.

---

## Live Demo

> Add your live link here: `https://your-live-link.com`

---

## Screenshot

> Add a screenshot here after deploying:
> `![App Screenshot](./assets/screenshot.png)`

---

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI_v5-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)

---

## Features

- **Login Page** — credential-based authentication with error handling
- **Issue Cards** — displays all issues fetched live from a REST API
- **Status Filter** — filter issues by All / Open / Closed
- **Real-time Search** — search issues via API query
- **Priority Badges** — color-coded High / Medium / Low priority indicators
- **Label Badges** — bug, enhancement, documentation, help wanted, good first issue
- **Issue Modal** — click any card to view full details (assignee, priority, labels, description)
- **Live Issue Count** — updates dynamically on filter/search
- **Loading Spinner** — shown while fetching data
- **Fully Responsive** — works on mobile, tablet, and desktop

---

## Dependencies

All dependencies are loaded via CDN — no installation required.

| Dependency | Version | Purpose |
|---|---|---|
| Tailwind CSS Browser | v4 | Utility-first CSS framework |
| DaisyUI | v5 | Component library for Tailwind |
| Font Awesome | v7 | Icons |
| Google Fonts (Geist) | — | Typography |

---

## Run Locally

Since this is a pure HTML/CSS/JS project with no build step, running it locally is simple.

**1. Clone the repository**
```bash
git clone https://github.com/Muhatarima/YOUR-REPO-NAME.git
```

**2. Open in browser**

Just open `index.html` directly in your browser — or use the Live Server extension in VS Code for the best experience.

```
Right click index.html → Open with Live Server
```

**3. Login credentials**
```
Username: admin
Password: admin123
```

---

## API Reference

This project fetches data from:

```
GET https://phi-lab-server.vercel.app/api/v1/lab/issues
GET https://phi-lab-server.vercel.app/api/v1/lab/issues/search?q={query}
```

---

## Project Structure

```
├── index.html          # Login page
├── issueTracker.html   # Main issues tracker page
├── style.css           # Custom styles
└── assets/             # Images and icons
```

---

## Author

**Muhatarima** — [GitHub](https://github.com/Muhatarima) · [LinkedIn](https://www.linkedin.com/in/muhatarima-medha/) · [muhatarima@gmail.com](mailto:muhatarima@gmail.com)
