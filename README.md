# ADM-11013 Final Exam Preparation

Study material for the ADM-11013 final exam, built as a [Quartz](https://quartz.jzhao.xyz) site with Obsidian-style wikilinks, math rendering, and Mermaid diagrams.

## Live site

Once GitHub Pages is enabled, the site will publish to:

`https://<your-username>.github.io/ADM-11013-final-exam-preparation/`

Update `baseUrl` in [`quartz.config.ts`](./quartz.config.ts) to match your username.

## What's in this repo

```
content/                          ← all study material (markdown)
├── index.md                      Homepage — exam logistics, entry points
├── study-plan.md                 Time-based study plans (15h / 8h / 3h)
├── cheat-sheet.md                Must-include phrases + day-before quick reference
├── formulas.md                   All formulas on one page
├── concept-map.md                Mermaid graph of all topic clusters
├── topics/                       Concept-first reference (7 clusters)
│   ├── consolidation/            21 pts on the exam — biggest single item
│   ├── fx-theories/              PPP, IFE, currency swap
│   ├── fx-exposure/              3 exposures + hedging
│   ├── tax-mechanisms/           4 ways to reduce MNC tax
│   ├── mnc-finance/              Lessard-Lorange, depositories, netting
│   ├── monetary-system/          Gold standard, fixed/floating, currency board
│   └── legal-systems/            Common vs Civil, torts, IP
└── questions/                    20 practice questions + 8 teacher-flagged
    ├── index.md                  Master list sorted by exam probability
    └── q*-*.md                   One file per question
```

The `_legacy/` folder holds the earlier 1st-pass refinement (by lecture/chapter/exercise) for diff/cross-check. It is excluded from the published site.

## Local preview

Requires Node 22+ (see [`.node-version`](./.node-version)).

```bash
npm install
npx quartz build --serve
# → http://localhost:8080
```

## Deploying to GitHub Pages

A workflow is already wired up at [`.github/workflows/deploy.yml`](./.github/workflows/deploy.yml). To enable it:

1. **Push this repo to GitHub** (any repo name — but if you change the name, update `baseUrl` in `quartz.config.ts`).
2. In the repo's **Settings → Pages**, set:
   - **Source:** GitHub Actions
3. Push to `main`. The workflow builds and deploys automatically.

The first deploy may take a few minutes (npm install + build); subsequent deploys with the cached npm modules take ~1 minute.

## Editing content

- All study material lives in [`content/`](./content/).
- Cross-references use **Obsidian-style wikilinks**: `[[topics/consolidation/temporal-method|Temporal method]]`.
- Math via `$$...$$` (block) or `$...$` (inline). Currency dollar signs must be escaped: `\$1.49`.
- Mermaid diagrams: ```` ```mermaid ```` fenced code blocks.
- Callouts: `> [!note]`, `> [!warning]`, `> [!danger]`, `> [!important]`, `> [!tip]`, `> [!info]`.

## Credits

Built with [Quartz v4](https://quartz.jzhao.xyz) by jackyzha0.
