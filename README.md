# TOGAF 10 — Certification Course

A self-contained, single-page interactive course for **TOGAF® 10** certification
study. The whole thing is one `index.html` file — no build step, no dependencies,
no external assets — so it runs anywhere you can open a browser.

## View it

**Live (GitHub Pages):** https://ctf2009.github.io/togaf-10/

**Locally:** clone the repo and open `index.html` in any modern browser, or serve it:

```bash
git clone https://github.com/ctf2009/togaf-10.git
cd togaf-10
# either just open index.html, or:
python3 -m http.server 8000   # then visit http://localhost:8000
```

## What's inside

Fourteen modules walking through the TOGAF 10 standard — the ADM phases, core
concepts, theory, worked artifacts/examples, and end-of-module quizzes to check
recall. Everything is contained in the page; your quiz progress lives in the browser.

## Enabling GitHub Pages

Already done if the live link above works. If not:

1. Repo **Settings → Pages**
2. **Source:** *Deploy from a branch*
3. **Branch:** `main`, folder `/ (root)`
4. Save — the site builds from `index.html` at the repo root.

## Notes

The course content was generated with the help of an LLM (Fable 5) and is intended
as study material. *TOGAF® is a registered trademark of The Open Group.* This is an
unofficial study aid and is not affiliated with or endorsed by The Open Group.
