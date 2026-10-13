# Splitlab: Experiment Hub (prototype)

A clickable prototype of a self-serve A/B experimentation tool for product managers. It is a single HTML file with sample data and nothing to install.

## Run it

Open `index.html` in any browser. To host it, turn on GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder).

## What's inside

- **All experiments**: every experiment in the org with its status (running, completed, terminated, scheduled, draft) and result, shown as a list or a timeline.
- **Experiment page**: an automatic Success / Failure / Flat verdict with a written summary and recommendation. It includes a metrics scorecard with 95% confidence intervals, a lift-over-time chart, a segment breakdown, a sample ratio mismatch check, annotated before/after screens, comments, an activity log and exports.
- **New experiment wizard**: feature name and ID, platforms, geography, number of users and traffic share, variants and split, metrics (multi-select, quick-pick bundles, custom formulas, Adobe Analytics import), before/after screens with pinned notes, dates, a sample size calculator, CUPED, sequential testing and approval.
- **Metrics library**: business, customer, engagement and performance metrics with their formulas.
- **Feature guide**: features borrowed from common experimentation platforms, with links to where each one appears in the prototype.

## Limitations

- All experiment data is sample data. The Adobe Analytics connection is simulated.
- Changes you make are saved in your own browser only (localStorage).
- "Today" is fixed at 8 Oct 2026 so the sample experiments line up.
