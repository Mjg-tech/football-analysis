# Football analysis archive

One page (`index.html`) shows the newest analysis and keeps every earlier one in a history list.

## Publishing a new analysis
1. Save the finished board as `analyses/YYYY-MM-DD-<slug>.html` (self-contained HTML, own `<title>`).
2. Add one entry at the top of `analyses.json`: `file`, `date` (YYYY-MM-DD), `title`, `kind` (Predictions / Bettable events), `scope`.
3. Commit and push to `main`. GitHub Pages republishes the site.

Never edit or delete an older analysis: each one is a snapshot of its date.
Estimates are analysis, not betting advice.
