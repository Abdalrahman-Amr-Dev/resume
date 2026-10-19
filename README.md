# Abdalrahman Amr — Resume

Backend & Cloud Engineer building production systems with Node.js, NestJS, TypeScript, PostgreSQL, AWS, and Cloudflare. Experience spans backend architecture, reliable asynchronous processing, payment integrations, real-time services, and production operations.

This repository maintains my resume in LaTeX, with automated PDF builds and versioned releases.

**[Download the latest resume (PDF)](https://github.com/Abdalrahman-Amr-Dev/resume/releases/latest/download/resume.pdf)** · [View source](resume.tex) · [Release history](https://github.com/Abdalrahman-Amr-Dev/resume/releases)

## Document

The resume uses a two-page, single-column layout with selectable text, standard section headings, and clickable contact and project links. The source of truth is [`resume.tex`](resume.tex).

## Build locally

Use either a LaTeX distribution with pdfLaTeX or [Tectonic](https://tectonic-typesetting.github.io/).

With pdfLaTeX:

```bash
mkdir -p build
pdflatex -interaction=nonstopmode -halt-on-error -output-directory=build resume.tex
pdflatex -interaction=nonstopmode -halt-on-error -output-directory=build resume.tex
```

Or with Tectonic:

```bash
mkdir -p build
tectonic --outdir build resume.tex
```

Both methods produce `build/resume.pdf`. Review the generated PDF for page breaks, spacing, and link behavior before publishing.

## Automated builds and releases

The [GitHub Actions workflow](.github/workflows/build-resume.yml) runs on pushes to `main` and tags beginning with `v`.

- **Push to `main`:** Compiles the resume and uploads the PDF as the `resume-pdf` workflow artifact.
- **Push a version tag:** Also publishes a GitHub release containing `resume.pdf` and generated release notes.

The download link above points to the latest published release. Changes pushed only to `main` are available through workflow artifacts until a new version is tagged.

## Versioning

Versions use the `vMAJOR.MINOR.PATCH` format:

- **Patch:** Wording corrections, formatting adjustments, and small factual updates.
- **Minor:** New experience, projects, skills, or achievements.
- **Major:** Substantial changes to the document's structure or professional positioning.

Create an annotated tag on the intended commit and push that specific tag to publish a release. Existing release tags should remain unchanged.

## Contact

- [LinkedIn](https://www.linkedin.com/in/abdalrhman-amr-55842b334/)
- [GitHub](https://github.com/Abdalrahman-Amr-Dev)
- [Email](mailto:abdalrahman.amr.dev@gmail.com)
