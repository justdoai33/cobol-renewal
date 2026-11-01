# Demo Site

A static HTML site for showcasing the COBOL Renewal Framework to potential clients.

## How to Use

Open `index.html` in any browser — no server, no build step, no dependencies.

```bash
# macOS
open docs/index.html

# Or serve locally if you prefer
python3 -m http.server 8000 --directory docs
# Then visit http://localhost:8000
```

## Hosting Options

This is a static site (HTML + CSS only, no JavaScript). It can be hosted anywhere:

- **GitHub Pages** — already configured to serve from the `docs/` folder on `main`
- **Netlify** — drag and drop the `docs/` folder
- **Any web server** — just serve the directory
- **Local** — open `index.html` directly in a browser

## Pages

| Page | File | Content |
|------|------|---------|
| Landing | `index.html` | Problem statement, value prop, navigation |
| The Modernisation Imperative | `imperative.html` | The knowledge crisis, discovery lag, and transparency gap |
| Before & After | `before-after.html` | Raw COBOL vs. structured specification |
| The Breakthrough | `breakthrough.html` | AI speed & efficiency vs. traditional analyst effort |
| Methodology | `methodology.html` | EARS, phased delivery, gap-first honesty |
| Why This Works | `why-this-works.html` | Why AI-assisted speed doesn't come at the cost of rigor |
| The Deliverables | `deliverables.html` | The permanent knowledge base (wiki) produced by the framework |
| The Re-Written Code | `rewritten-code.html` | Implementation-ready code in Python, Go, or Java |
| The Playbook | `playbook.html` | Step-by-step guide with skills, tools, and timeline |
| The Path Forward | `path-forward.html` | Select → Generate → Validate → Scale |
| BRS Example | `example-brs.html` | Real business rules from billing deduplication |
| FRS Example | `example-frs.html` | Functional requirements with data mappings |
| TDD Example | `example-tdd.html` | Implementation-ready Go design |
| GAPS Example | `example-gaps.html` | Open questions with resolution paths |

## Notes

- Content is based on the IDMI700W proof-of-concept example
- Client names have been removed
- No pricing or commercial content included
- No JavaScript — works without a network connection
