# ahinsvark.github.io

Personal website + paper hosting (GitHub Pages)

Live:
- https://ahinsvark.github.io/

---

## How to add a new paper (3 steps)

### 1) Upload the PDF
Add the PDF here:

`/papers/<slug>.pdf`

Example:
- `/papers/llm-survey-02.pdf`

> Use the GitHub Pages domain PDF URL (e.g. `https://ahinsvark.github.io/papers/llm-survey-02.pdf`), not the GitHub `blob/` URL.

---

### 2) Add one entry to the publications data file
Edit:

`/_data/publications.yml`

Copy/paste and modify:

```yml
- id: "llm-survey-02"
  slug: "llm-survey-02"
  title: "Paper Title Here"
  date: "2026-02-01"
  year: 2026
  venue: "Preprint"
  pdf: "/papers/llm-survey-02.pdf"

  authors_display: "First Author, Second Author, … and others"
  authors:
    - "First Author"
    - "Second Author"
    - "Third Author"

  keywords:
    - "keyword 1"
    - "keyword 2"

  blurb: "One-sentence description used on the /papers/ hub page."

  abstract: >
    Paste the abstract here. Use plain text. This is shown on the landing page.

  author_note: "Optional: e.g., complete author list appears in Appendix A of the PDF."

  notes:
    - "Optional note 1"
    - "Optional note 2"
