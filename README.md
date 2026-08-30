# Abdalrahman Amr — Resume

My professional resume, written in **LaTeX** and automatically compiled to PDF using **GitHub Actions**.

## 📄 Resume

**Latest version:** [Download Resume (PDF)](../../releases/latest)

The PDF is automatically generated whenever changes are pushed to the `main` branch.

## 🛠️ Tech Stack

* **LaTeX** — Resume source and document formatting
* **Git** — Version control
* **GitHub Actions** — Automated PDF generation
* **GitHub Releases** — Versioned resume PDFs

## 📁 Project Structure

```text
.
├── resume.tex
├── README.md
├── .gitignore
└── .github/
    └── workflows/
        └── build-resume.yml
```

## 🔄 Workflow

The resume follows a simple automated workflow:

```text
Edit resume.tex
      ↓
Commit & Push
      ↓
GitHub Actions
      ↓
Compile LaTeX
      ↓
Generate resume.pdf
      ↓
Publish as Release
```

## 📌 Versioning

Resume versions follow [Semantic Versioning](https://semver.org/):

* **Patch** (`v1.0.1`) — Typo fixes, formatting changes, minor corrections
* **Minor** (`v1.1.0`) — New projects, skills, experience, or achievements
* **Major** (`v2.0.0`) — Major redesigns or significant career changes

Example:

```bash
git add resume.tex
git commit -m "feat: add new project"

git tag v1.1.0
git push origin main --tags
```

## 👤 About Me

**Abdalrahman Amr**

Computer Science & AI Engineering student at **Damietta University**, focused on backend engineering, cloud infrastructure, distributed systems, and AI integration.

* 💼 Software Engineer
* ⚙️ Node.js / NestJS / TypeScript
* ☁️ AWS / Cloudflare / Hetzner
* 🐳 Docker & CI/CD
* 🤖 AI & LLM Integration

## 🔗 Links

* [GitHub](https://github.com/Abdalrahman-Amr-Dev)
* [LinkedIn](https://www.linkedin.com/in/abdalrahman-amr-55842b334/)

---

> This repository contains the source code of my resume. The PDF is generated automatically from the LaTeX source.
