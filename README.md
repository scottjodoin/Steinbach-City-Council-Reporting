# Steinbach City Council Reporting

Plain-language summaries of what Steinbach City Council has said and decided, with every quote linked to its timestamp in the official meeting video.

## Reports

- [2026 council candidates' forum: every question, every answer](candidate-forum-2026/) — All 10 candidates' answers at the Chamber of Commerce forum (Oct 15, 2026), linked to the video, plus a check of the four incumbents' answers against their council record.
- [Transcript: 2026 council candidates' forum](candidate-forum-2026-transcript/) — The full forum transcript with named speakers and timestamps; downloadable as text and JSON.
- [Residents' election forum: what residents asked, and how four candidates answered](residents-forum-2026/) — The Southeast Equity Coalition and Strong Towns Steinbach forum (Oct 7, 2026): residents' questions and full answers from the four candidates who attended.
- [Transcript: residents' election forum](residents-forum-2026-transcript/) — The candidates' answers by topic with timestamps; downloadable as text and JSON.
- [Candidates in writing: growth and housing, flooding, and public safety](candidate-interviews-2026/) — All 10 candidates' written answers to SteinbachOnline, summarized with key quotes and incumbent record checks.
- [Taxes, spending and priorities: how does Steinbach pay its way?](taxes-spending/) — Priorities, five years of budgets, reserves and the five-year debt rule: council's record in its own words, and how Steinbach's tax rate compares with Brandon, Selkirk and Thompson.
- [Housing and development: keeping up with growth](housing-development/) — Affordable housing, infill apartments versus single-family neighbourhoods, and who pays for growth: council's record in its own words, and how Brandon, Niverville and others compare.
- [Sewer backups: what council said, and how Steinbach compares](sewer-backups/) — council meetings Sept 2025 to Sept 2026, plus a comparison with other Canadian municipalities.
- [Steinbach in 10 to 20 years: what has council planned?](future-planning/) — Growth to 35,000–45,000, the $215M wastewater decision, annexation and neighbours, and the plans that exist and don't: council's record in its own words, compared with Brandon and Winkler.
- [Health and wellbeing: what can council do?](health-wellbeing/) — Doctor shortages, the Mayor's recruitment task force, clinic space, recreation and wellbeing: council's record in its own words, and how councils in Niverville, Clarington and others compare.
- [Homelessness in Steinbach: what's been done, and what could be](homelessness/) — council meetings Jan 2022 to Sept 2026, plus what other councils do.
- [Traffic in Steinbach: what can council do, and what has it done?](traffic-congestion/) — Main Street and Highway 12 are provincial, but council has tools: traffic counts, cost-shared intersections and lobbying. Its record in its own words, the slow Giesbrecht lights, and what peers do.
- [A bypass around Main Street? What council says and what the traffic study shows](main-street-bypass/) — Council says traffic comes to Steinbach rather than through it. What the city's own WSP traffic studies show and can't show, the trucks no one counts, and how Yorkton, Portage la Prairie, Winkler and others handled their highways.
- [New neighbourhoods: do drainage, sidewalks and parks arrive on time?](new-neighbourhood-services/) — Lot grading, sidewalks, playgrounds and paving in new subdivisions, wells and septic in fringe areas, and who checks: council's record in its own words, compared with Brandon, Winnipeg and Calgary.
- [Public notice and having a say: do residents' objections count?](public-notice/) — How residents hear about rezonings and variances, petitions, postponement requests and the 2025 plan review: council's record in its own words, how often objections changed the result, and how Brandon, Selkirk and Lethbridge compare.
- [Crime and policing in Steinbach](crime-policing/) — The 18-officer RCMP contract, yearly policing priorities, overnight security patrols and community safety officers: council's record in its own words, and how officers per resident, cost and crime severity compare with Winkler, Morden, Brandon and Portage.
- [Business growth and investment: what has council done?](business-growth/) — The end of the economic development office, the industrial land squeeze, the Chamber's business tax and downtown rules: council's record in its own words, and how Winkler, Morden and Portage compare.
- [Quality of life: noise, belonging, parks, recreation and arts](quality-of-life/) — Noise enforcement, racism and welcoming newcomers, flags and inclusion, green space, recreation and arts space: council's record in its own words, and how other councils compare.
- [Can Steinbach have public transit?](transit/) — council meetings Jan 2022 to Sept 2026, plus how similar-size cities run transit.
- [Property standards: how does Steinbach keep rentals and yards maintained?](property-standards/) — The 2003 junk-and-weeds by-law, basement-suite safety rules, complaint-driven enforcement and residents' rental-upkeep concerns: council's record in its own words, compared with Brandon, Winkler, Winnipeg and Ontario cities that license rentals.
- [Behind closed doors? How much of council's work happens outside public meetings](behind-closed-doors/) — Do unanimous votes, including on developers' applications, mean decisions were made in advance? Four tests on 103 meetings, council's closed committee and budget study sessions, and how they measure up against Manitoba's Municipal Act and councils such as Selkirk and Brandon.
- [Recorded public deliberation on Steinbach City Council](council-deliberation/) — provisional, AI-coded Public Judgment & Deliberation Index for all 103 regular meetings, with the [methodology](council-deliberation/methodology/) and a downloadable data workbook.
- [Who moves council's public-hearing motions?](public-hearing-motions/) — The 203 motions on public-hearing matters (Jan 2022 – Sept 2026), counted by mover and seconder, each with a summary, impact rating, video moment and minutes page.

## Site layout

This is a plain static site for GitHub Pages (no Jekyll; see `.nojekyll`).

```
health-wellbeing/index.html
index.html              Home page listing all reports
assets/css/style.css    Shared styles (follows the browser light/dark setting)
sewer-backups/index.html
homelessness/index.html
transit/index.html
council-deliberation/index.html               report
council-deliberation/methodology/index.html   rubric methodology
council-deliberation/steinbach-council-deliberation-data.xlsx
public-hearing-motions/index.html
```

To add a report, create a new folder with an `index.html` that links `../assets/css/style.css`, then add it to the list in `index.html` and above.

## Report conventions

Each report starts from a plain-language question and answers it with:

- **The council record**: verbatim quotes from the meeting transcripts, each linked to its timestamp in the official YouTube video, plus the decisions and votes from the minutes.
- **How Steinbach compares**: what other municipalities do, with links to their own published programs, and a scorecard (Strong / On par / Partial / Gap).
- **About this page**: transcript accuracy, how speakers were identified, and anything that couldn't be verified.
