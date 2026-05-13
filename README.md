# 591 Quantum Annealers Seminar

Graduate seminar presentation for CENG 591, based on:

**Compensating Connectivity Restrictions in Quantum Annealers via Splitting and Linearisation Techniques**
Seelbach Benkner, Lähner, Golyanik, Kliesch, Moeller, arXiv:2507.12536v1 (2025)

## Live slides

Once GitHub Pages is enabled for this repository, the deck is served at:

https://denizcan-yilmaz.github.io/591-quantum-annealers/

Navigation: `→` / `←` or `Space` to step through slides, `F` for fullscreen, `Cmd/Ctrl+P` to print to PDF.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The 13-slide deck (12 content slides + thanks). |
| `quantum_annealing_seminar.html` | Same content as `index.html`; kept for reference. |
| `figs/` | Figures from the paper (Fig. 1, Fig. 6, Fig. 10). |
| `speaker_notes.pdf` | Ten-minute speaking script, one section per slide. |
| `qa_prep.pdf` | Thirty likely audience questions with short answers, plus a symbol glossary. |
| `speaker_notes.tex`, `qa_prep.tex` | LaTeX sources for the two PDFs. |

## Local viewing

```bash
open index.html
```

For full fidelity (MathJax over HTTPS, click-through navigation):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

## Enabling GitHub Pages

1. Repo **Settings** -> **Pages**.
2. **Source**: Deploy from a branch.
3. **Branch**: `main`, folder `/ (root)`.
4. Save. The site is live at the URL above within ~30 seconds.

## Author

Denizcan Yılmaz, student ID 2444172.
