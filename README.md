# CIOP Pure Thesis (v1.1 public-ready)

**Purpose**: Fix and timestamp the current state of thought as a verifiable intellectual record (PIAO/UIR/CIAO).  
**Language**: Japanese (with English metadata via `CITATION.cff`).

## Quick Start (You do these steps)
```bash
git init
git add .
git commit -m "Add CIOP pure thesis v1.1"
git tag v1.1
# (Optional) create GitHub repo and push, then create a Release for tag v1.1
```

## Hash → Paste into front matter
```bash
openssl sha256 ciop_pure_thesis_v1_1.md
openssl sha256 assets/prompts_index.jsonl
openssl sha256 assets/*
```
Copy the resulting SHA-256 into `identifiers.content_hash_sha256` in the front matter of the main file.

## After Publishing
- Put your GitHub Release URL into `identifiers.canonical_uri`.
- (Optional) Connect to Zenodo to mint a DOI.
- Cross-post to Note/Medium with the Release URL as the canonical link.

- ## Releases
- v1.1 — Main thesis (canonical)  
  https://github.com/hand-shinya/ciop-pure-thesis/releases/tag/v1.1
- v1.1.1 — Appendices (Originality, Math, Miura, Protocols, Meta)  
  https://github.com/hand-shinya/ciop-pure-thesis/releases/tag/v1.1.1

