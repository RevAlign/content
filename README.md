# RevAlign Content Assets

Weekly LinkedIn content - graphics and copy ready to post.

## Structure

```
YYYY-MM-DD[-topic]/
├── 01_[title].png      # First post graphic
├── 02_[title].png      # Second post graphic
├── ...
└── copy.md             # All LinkedIn copy for the week
```

## Workflow

1. `/content-monday` generates HTML graphics + copy
2. Chrome headless exports to PNG
3. Auto-committed to this repo
4. Download from GitHub → post to LinkedIn

## Usage

Each folder contains:
- **PNG files** - Right-click → Save Image As (or clone repo)
- **copy.md** - Copy/paste directly to LinkedIn

---

Built by [RevAlign.io](https://revalign.io) - Fractional RevOps for B2B Startups
