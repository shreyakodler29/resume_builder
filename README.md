# resume_builder
# Paperwork — Free Resume Builder

A free, no-signup resume builder. Fill in your details once and switch between **three real resume designs** — Classic, Modern, and Bold — built from the same data. Export any of them as a clean PDF with one click.

**Built by:** Shreya S Kodler
**Contact:** shreyakodler29@gmail.com

## Why I built this

Most free resume builders give you one template and lock everything else — better fonts, second pages, even the PDF export — behind a paid plan. I wanted one place where I could try a few different looks for the same resume without re-typing anything, and export it for free. This is that tool.

## What it includes

- **Three themes**, switchable live: a serif single-column Classic, a sidebar-based Modern (sans-serif, dark sidebar), and a Bold theme with a dark header band and accent color
- Sections: heading & contact, summary, experience, projects, education, certifications, skills, languages, achievements
- Live preview that updates as you type — no "generate" step
- One-click PDF export via the browser's print dialog (correctly scoped so only the resume sheet prints, not the form)
- No login, no backend, no data leaves your browser

## Tech

Plain HTML, CSS, and JavaScript. No build step, no dependencies, no framework — deploys to Vercel as a static site.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Static site — deploy directly to [Vercel](https://vercel.com) with zero configuration (Framework Preset: "Other").
---
Built for the Digital Heroes developer trial task.
