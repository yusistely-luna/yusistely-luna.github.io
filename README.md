# Yusistely Luna — QA Engineer Portfolio

Personal portfolio site: [yusistely-luna.github.io](https://yusistely-luna.github.io/)

## About

A single-page portfolio for a QA Engineer Jr. background — 15 years in industrial quality management, now applied to manual, web, API, and mobile software testing. Built to give recruiters a fast, scannable overview: a short hook per project, key metrics, and a link to the full write-up on GitHub.

## Structure

- `index.html` — the entire site (self-contained HTML/CSS, no build step)
- `screenshots/` — evidence images (JIRA boards, Postman collections, test case spreadsheets) referenced by the Projects section
- `CV_Yusistely_Luna_QA_Engineer_v1.pdf` — downloadable CV

## Sections

- **Hero** — name, role, short pitch, contact links (email, LinkedIn, GitHub)
- **About** — background and career pivot from Industrial Engineering to QA
- **Tech Stack** — testing techniques, tools, automation, and compliance skills, grouped and badge-styled
- **Featured Projects** — 8 QA projects, each with a one-paragraph summary, key metrics, skill badges, and a link to its GitHub repo
- **Key Achievements** — quantified results from the pre-QA career (audits, compliance, process automation)
- **Contact** — email, LinkedIn, GitHub, and CV download

## Editing

The whole page is one HTML file with an inline `<style>` block — no framework, no dependencies beyond Google Fonts and Font Awesome (both loaded via CDN). To update a project or add a new one, copy an existing `.project-card` block and edit its content in place; the card, badge, and results-row styles are shared across all projects.

## Deployment

Published via GitHub Pages from this repository's default branch. Any push to `main` updates the live site.
