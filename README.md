# Steinbach City Council Reporting

Plain-language summaries of what Steinbach City Council has said and decided, with every quote linked to its timestamp in the official meeting video.

## Reports

- [Sewer backups: what council said, and how Steinbach compares](sewer-backups/) — council meetings Sept 2025 to Sept 2026, plus a comparison with other Canadian municipalities.
- [Homelessness in Steinbach: what's been done, and what could be](homelessness/) — council meetings Jan 2022 to Sept 2026, plus what other councils do.
- [Can Steinbach have public transit?](transit/) — council meetings Jan 2022 to Sept 2026, plus how similar-size cities run transit.
- [Recorded public deliberation on Steinbach City Council](council-deliberation/) — provisional, AI-coded Public Judgment & Deliberation Index for all 103 regular meetings, with the [methodology](council-deliberation/methodology/) and a downloadable data workbook.

## Site layout

This is a plain static site for GitHub Pages (no Jekyll; see `.nojekyll`).

```
index.html              Home page listing all reports
assets/css/style.css    Shared styles (follows the browser light/dark setting)
sewer-backups/index.html
homelessness/index.html
transit/index.html
council-deliberation/index.html               report
council-deliberation/methodology/index.html   rubric methodology
council-deliberation/steinbach-council-deliberation-data.xlsx
```

To add a report, create a new folder with an `index.html` that links `../assets/css/style.css`, then add it to the list in `index.html` and above.

## Report conventions

Each report starts from a plain-language question and answers it with:

- **The council record**: verbatim quotes from the meeting transcripts, each linked to its timestamp in the official YouTube video, plus the decisions and votes from the minutes.
- **How Steinbach compares**: what other municipalities do, with links to their own published programs, and a scorecard (Strong / On par / Partial / Gap).
- **About this page**: transcript accuracy, how speakers were identified, and anything that couldn't be verified.
