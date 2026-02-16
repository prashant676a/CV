# Prashant Bhandari — Curriculum Vitae

[![Build LaTeX Resume](https://github.com/prashant676a/CV/actions/workflows/build.yml/badge.svg)](https://github.com/prashant676a/CV/actions/workflows/build.yml)

**[Download Latest Resume (PDF)](https://github.com/prashant676a/CV/raw/main/resume.pdf)**

## About

This repository contains the LaTeX source for my resume. The PDF is automatically compiled via GitHub Actions on every push to `main`.

## How It Works

- Edit `resume.tex` (locally, in Cursor, or sync from Overleaf)
- Push to `main`
- GitHub Actions compiles the LaTeX and commits `resume.pdf` back to the repo

## Local Build

To compile the PDF locally, ensure you have a LaTeX distribution installed (e.g., TeX Live):

```bash
pdflatex resume.tex
```

## Tech Stack

- **LaTeX** for typesetting
- **GitHub Actions** with [xu-cheng/latex-action](https://github.com/xu-cheng/latex-action) for automated builds
