# Football analysis archive

One page (`index.html`) shows the newest analysis and keeps every earlier one in a history list.
It has an EN / FR switch: each analysis exists in English and in French.

## Publishing a new analysis
1. Save the English board as `analyses/YYYY-MM-DD-<slug>.html` and its French twin as `analyses/fr/YYYY-MM-DD-<slug>.html` (self-contained HTML, own `<title>`).
2. Add one entry at the top of `analyses.json`: `file`, `date` (YYYY-MM-DD), `title`, `kind`, `scope`, plus `title_fr`, `kind_fr`, `scope_fr`.
3. Commit and push to `main`. GitHub Pages republishes the site.

Never edit or delete an older analysis: each one is a snapshot of its date.
Estimates are analysis, not betting advice.
