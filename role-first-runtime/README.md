# role-first-runtime (starter)

This folder is a **non-technical scaffold** for your project. It gives your engineers a clear place to put things.
You can upload this to GitHub as a new repository.

## What lives where (plain English)
- **sdk/** – the small plugin ("interposer") your engineers build. It plugs into GPU software.
- **kernels/** – ready-made GPU kernels (templates) your engineers tune for speed.
- **policies/** – a simple settings file that tells the runtime what to optimize.
- **bench/** – simple tests that compare BEFORE vs AFTER.
- **reports/** – results: charts, CSVs, a one-page PoV report for customers.

## Quick start (non-technical)
1. Create a GitHub repo named `role-first-runtime`.
2. Upload these folders/files.
3. Share the repo link with your engineer; tell them to start with `policies/policy.yaml` and `sdk/README.md`.
4. When they’re done, use `reports/PoV-report-template.md` to send a one-page result to customers.
