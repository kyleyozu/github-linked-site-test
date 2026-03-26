# github-linked-site-test

A static HTML site built and deployed through a GitHub-connected workflow driven by Claude Code.

## Structure

```
/
├── index.html   # Single-page site
└── style.css    # All styles
```

## Phases

| # | Phase | Branch | Issue |
|---|-------|--------|-------|
| 1 | Project setup & repo initialisation | `phase/1-setup` | #1 |
| 2 | Header component | `phase/2-header` | #2 |
| 3 | Hero section | `phase/3-hero` | #3 |
| 4 | Copy / content section | `phase/4-copy` | #4 |
| 5 | Footer | `phase/5-footer` | #5 |
| 6 | Styling & polish | `phase/6-styling` | #6 |

## Workflow

Each phase has a dedicated branch and GitHub issue. Work is committed to the phase branch, a detailed PR is opened, reviewed, and merged into `main`.
