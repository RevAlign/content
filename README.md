# RevAlign Content Assets

Weekly LinkedIn and Substack content - graphics and copy ready to post.

## Structure

```
YYYY-MM-DD[-topic]/          # LinkedIn weekly content
├── 01_[title].png
├── 02_[title].png
└── copy.md

substack/                     # Substack cover images
├── [slug].html              # Source HTML (auto-generated)
└── [slug].png               # Cover image (auto-screenshotted)
```

## LinkedIn Workflow

1. `/content-monday` generates HTML graphics + copy
2. Chrome headless exports to PNG
3. Auto-committed to this repo
4. Download from GitHub → post to LinkedIn

## Substack Workflow

1. Generate cover HTML:
   ```bash
   cd RevAlign.io/automation/substack
   python generate_cover.py --title "Your Title" --subtitle "Subtitle" --category HUBSPOT --commit
   ```

2. GitHub Action auto-screenshots HTML → PNG

3. Pull the PNG:
   ```bash
   git pull
   ```

4. Use PNG as Substack cover image

### Cover Dimensions
- **Width**: 1456 px
- **Height**: 600 px
- **Format**: PNG

### Available Categories
`REVOPS` | `HUBSPOT` | `CLAY` | `GTM` | `OUTBOUND` | `PIPELINE` | `DATA` | `STARTUPS`

## Raw URLs

After commit, assets are available at:
```
https://raw.githubusercontent.com/RevAlign/content/main/substack/[filename].png
```

---

Built by [RevAlign.io](https://revalign.io) - Fractional RevOps for B2B Startups
