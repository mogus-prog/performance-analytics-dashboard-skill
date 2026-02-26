---
name: performance-analytics-dashboard
description: Performance Analytics Dashboard workflow automation skill. Use when a user needs Performance Analytics Dashboard tasks planned, generated, analyzed, or reported with repeatable outputs, templates, and lightweight local scripts.
---

# Performance Analytics Dashboard

Follow this workflow:

1. Read relevant input files from       .
2. Run  with a short task prompt and output directory.
3. Verify output artifacts in the chosen output folder.
4. Iterate prompt parameters for improved quality.

## Command

```bash
bash scripts/run.sh --task "example task" --outdir ../../tmp/performance-analytics-dashboard
```

## Notes

- Keep runs deterministic and timestamped.
- Save generated artifacts to the target outdir.
- Use  as a starter template.
