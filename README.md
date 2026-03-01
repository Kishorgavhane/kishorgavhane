# 🚀 Kishor Gavhane — Cloud & DevOps Engineer Portfolio

[![Deploy Portfolio](https://github.com/Kishorgavhane/kishorgavhane/actions/workflows/deploy.yml/badge.svg)](https://github.com/Kishorgavhane/kishorgavhane/actions/workflows/deploy.yml)
![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?logo=github)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-orange?logo=githubactions)
![Azure](https://img.shields.io/badge/Certified-AZ--104-blue?logo=microsoftazure)

> A production-ready DevOps portfolio with fully automated CI/CD deployment via GitHub Actions.

## 🌐 Live Site
**[kishorgavhane.github.io/kishorgavhane](https://kishorgavhane.github.io/kishorgavhane)**

---

## ✨ Features

- **Animated DevOps-themed background** — particle network + CI/CD pipeline visualization
- **Custom cursor** with smooth trailing ring
- **Scroll-reveal animations** for all sections
- **Resume upload & preview** — drag & drop PDF viewer
- **Fully responsive** — mobile + tablet + desktop
- **Contact form** — mailto integration
- **Smooth navigation** with active state tracking
- **CI/CD automated deployment** on every `git push`

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3 (custom properties), Vanilla JS |
| Fonts | Syne (display), DM Sans (body), Space Mono (code) |
| Icons | Font Awesome 6 |
| Canvas | HTML5 Canvas API (animated background) |
| CI/CD | GitHub Actions |
| Hosting | GitHub Pages |
| Domain | portfolio.kishorgavhane |

---

## 🚀 CI/CD Pipeline

Every `git push` to `main` triggers:

```
Push to main
    │
    ▼
[Build Job]
    ├── Checkout code
    ├── Validate HTML
    ├── List deployment files
    └── Upload artifact
    │
    ▼
[Deploy Job]
    └── Deploy to GitHub Pages → Live URL
```

---

## 📁 Repository Structure

```
kishorgavhane/
├── index.html              # Main portfolio (single-file)
├── Resume.pdf              # Resume document
├── README.md               # This file
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Actions CI/CD pipeline
```

---

## 🛠️ Local Development

```bash
# Clone the repo
git clone https://github.com/Kishorgavhane/kishorgavhane.git
cd kishorgavhane

# Serve locally (Python)
python3 -m http.server 8000

# Open in browser
open http://localhost:8000
```

---

## ⚙️ Deploy Your Own

1. **Fork** this repository
2. Go to **Settings → Pages**
3. Set Source to **GitHub Actions**
4. Push any change to `main` — the workflow handles the rest!

---

## 📬 Contact

| Channel | Link |
|---------|------|
| Email | [kishorgavhane.dev@gmail.com](mailto:kishorgavhane.dev@gmail.com) |
| LinkedIn | [linkedin.com/in/kishor-g-dev](https://www.linkedin.com/in/kishor-g-dev) |
| GitHub | [github.com/Kishorgavhane](https://github.com/Kishorgavhane) |
| Phone | +91-9270701808 |

---

*Built & deployed with ❤️ using GitHub Actions CI/CD*
