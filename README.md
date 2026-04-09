# GitHub Issues Tracker

A clean, responsive web app to track and manage GitHub-style issues — with login, real-time search, status filtering, priority badges, and a detailed modal view.

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-6366f1?style=for-the-badge&logo=github)](https://muhatarima.github.io/github-issues-tracker/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/Muhatarima/github-issues-tracker)

</div>

---

## Screenshot

<div align="center">
  <img src="https://raw.githubusercontent.com/Muhatarima/github-issues-tracker/main/assets/preview.png" alt="GitHub Issues Tracker Preview" width="600"/>
</div>

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
- **Issue Cards** — all issues fetched live from a REST API
- **Status Filter** — filter issues by All / Open / Closed
- **Real-time Search** — search issues via API query
- **Priority Badges** — color-coded High / Medium / Low indicators
- **Label Badges** — bug, enhancement, documentation, help wanted, good first issue
- **Issue Modal** — click any card to view full details including assignee, priority, labels and description
- **Live Issue Count** — updates dynamically based on filter or search
- **Loading Spinner** — shown while fetching data from API
- **Fully Responsive** — works on mobile, tablet, and desktop

---

## Dependencies

All dependencies are loaded via CDN — no installation required.

| Dependency | Version | Purpose |
|---|---|---|
| Tailwind CSS Browser | v4 | Utility-first CSS framework |
| DaisyUI | v5 | Component library for Tailwind |
| Font Awesome | v7 | Icons |
| Google Fonts (Geist) | latest | Typography |

---

## Run Locally

**1. Clone the repository**

```bash
# HTTPS
git clone https://github.com/Muhatarima/github-issues-tracker.git

# GitHub CLI
gh repo clone Muhatarima/github-issues-tracker
```

**2. Open the project**

```bash
cd github-issues-tracker
```

**3. Launch in browser**

Open `index.html` directly in your browser, or use the **Live Server** extension in VS Code for best experience.

```
Right click index.html → Open with Live Server
```

**4. Login credentials**

```
Username : admin
Password : admin123
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
github-issues-tracker/
├── index.html            # Login page
├── issueTracker.html     # Main issues tracker page
├── style.css             # Custom styles
└── assets/               # Images and icons
```

---

## Author

**Muhatarima** — [GitHub](https://github.com/Muhatarima) · [LinkedIn](https://www.linkedin.com/in/muhatarima-medha/) · [muhatarima@gmail.com](mailto:muhatarima@gmail.com)
