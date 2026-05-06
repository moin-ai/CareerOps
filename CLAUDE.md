# CareerOps — Remote Agent Instructions

This repo is the personal job search automation system for Arifuzzaman Moin.
The career-ops tool lives in the `career-ops/` subdirectory.

## For scheduled agents running this repo

### Setup (run once per session)
```bash
cd career-ops
npm install --prefer-offline 2>/dev/null || true
```

### Daily scan + pipeline
1. Use the `/career-ops scan` skill to scan all configured portals
2. Use the `/career-ops pipeline` skill to evaluate all pending jobs in `career-ops/data/pipeline.md`
3. Commit and push results back

### Committing results
```bash
cd career-ops
git add data/pipeline.md data/applications.md data/scan-history.tsv reports/ modes/_profile.md
git commit -m "chore: daily scan + pipeline results $(date +%Y-%m-%d)"
git push origin main
```

## Candidate
- Name: Arifuzzaman Moin
- Target: Data Analyst, Business Analyst, Data Engineer, Power Platform Developer
- Markets: Germany (EU Blue Card), Australia, Malaysia, Remote
