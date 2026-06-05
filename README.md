# Exercise 8 — Nonlinear Equations (Multi-Dimensional Newton and DK Method)

Numerical Analysis 2026 / Lecture 8 assignment bundle.

This repository contains **Ex 8.0–8.2** (all **Individual Work**).
Study the shared handout in the `materials` repository; you do not copy it
into this repo.

---

## Files

| File | Topic |
|---|---|
| `ex8-0.qmd` | **Ex 8.0** — environment check + handout study with AI Tutor (Sections 4–5) |
| `ex8-1.qmd` | Multi-dimensional Newton's method for systems of nonlinear equations |
| `ex8-2.qmd` | Simultaneous polynomial root-finding by the DK (Durand–Kerner) method |
| `requirements.txt` | Python packages used in the exercises |

---

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Then select the `.venv` interpreter in VS Code / Cursor.

---

## Render

```bash
quarto render ex8-0.qmd
quarto render ex8-1.qmd
quarto render ex8-2.qmd
```

**IMPORTANT:** This creates `ex8-0.html`, `ex8-1.html`, `ex8-2.html`, and
the corresponding `ex8-*_files/` directories.

---

## Submission

```bash
git add ex8-0.qmd ex8-1.qmd ex8-2.qmd
git add ex8-0.html ex8-1.html ex8-2.html ex8-0_files ex8-1_files ex8-2_files
git commit -m "Submit Ex 8"
git push
```

You may push as many times as you like before the deadline; the **last
commit before the deadline** will be graded.

**IMPORTANT:** After pushing, open your repository on GitHub and check that
the rendered HTML files are visible in the browser.

**Deadlines (JST):**
- Ex 8.0 — June 11 (Thu), 23:59 JST
- Ex 8.1 — June 11 (Thu), 23:59 JST
- Ex 8.2 — June 14 (Sun), 23:59 JST

---

## Need help?

- Mattermost: <https://class.s-top.dev/numerical-analysis-2026/channels/question>
- Materials repo: <https://github.com/waseda-num-analysis-2026/materials>
- Lecture 8 slides: <https://waseda-num-analysis-2026.github.io/materials/080/8th.html>
- Shared handout: <https://waseda-num-analysis-2026.github.io/materials/070/nonlinear-equations-handout.html>
