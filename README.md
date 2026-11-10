# Marketing Budget Tracker

A single-file web app (`index.html`) for tracking marketing budget vs actuals. No build step, no dependencies.

- **Plan:** budget lines with planned spend per quarter (Q1–Q4)
- **POs & Invoices:** entered by hand or imported from CSV (type, number, vendor, code, amount, quarter)
- **GL Upload (Finance):** CSV with code, quarter, type (Actual or Accrual), amount, reference
- **Dashboard:** % of plan invoiced, PO remaining, POs over plan flagged for review, and invoice vs GL reconciliation (timing, accrual, overspend)

Rules built in: a PO should be larger than the invoices against it, and below plan (exceptions are flagged for review). % of plan is based on invoices.

Sample data is preloaded. Data is saved in your browser's localStorage only. Use "Reset to sample data" or "Clear all data" at the top of the page.

## Publish with GitHub Pages
1. Create a repository and add `index.html` (and this README) to the root.
2. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`.
3. Your app will be live at `https://<your-username>.github.io/<repo-name>/`.

All data in the sample is fictional.
