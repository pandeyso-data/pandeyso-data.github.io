# SPEC — Personal Portfolio for Sonal Pandey

## 1. Professional story (summary)

Sonal Pandey is a **Senior Member Technical at Broadridge Financial Solutions** with
**~7 years** in enterprise fintech technology. Her work runs across the data flow behind
fintech operations: requirement → YAML/configuration → batch execution → database
processing → validation → Datamart/staging → downstream processing → reporting. She is
strongest in the middle of that chain — configuration, execution, validation, and
troubleshooting — where correctness is won or lost.

She is now deliberately building on that foundation toward **data analytics and data
engineering** (SQL, Python, ETL/pipelines, Apache Spark, data engineering concepts) and
developing **practical AI literacy**. Her learning is structured through the
**IISc Agentic AI program**, where she is practising **spec-driven development**.

Positioning: an experienced enterprise/fintech professional growing deeper into data
engineering, analytics, and AI-enabled workflows — **not a fresher, and not an AI/ML
engineer**. Growth areas are shown as in-progress, supported by structured learning and
early public repositories.

Audience: recruiters, hiring managers, and technical leads evaluating her for
data-focused roles.

## 2. Site structure

Single-page site, anchor navigation, sticky slim top nav.

| Section | Purpose |
| --- | --- |
| Hero | Name, title, one-paragraph positioning, primary links |
| About | Fuller story + "at a glance" facts |
| Experience | Broadridge — Senior Member Technical, ~7 years, factual responsibilities |
| How the work flows | 8-stage pipeline as a numbered timeline, plain-English |
| Technical skills | Core/production · Actively developing · Practices & tools |
| AI Literacy | Six concrete, practical use cases |
| Projects | Three real public repos, framed as hands-on learning |
| Continuous Learning | Ongoing, structured focus areas incl. IISc Agentic AI |
| Career Interests | What she is looking for next |
| Contact | GitHub, LinkedIn, email |

## 3. Content rules

- No invented achievements, metrics, employers, clients, dates, or technologies.
- Growth skills labelled "actively developing"; projects labelled practice, not production.
- Calm, professional, concrete tone.

## 4. Architecture

- Static site, no build step. Single `index.html` with inline CSS/JS.
- Google Fonts (IBM Plex superfamily) via `<link>`.
- Light + dark themes via tokens; optional manual toggle.
- Deploy on **GitHub Pages** from repo root.

## 5. Deployment

Repo: `pandeyso-data.github.io` (serves at `https://pandeyso-data.github.io`).
`.nojekyll` present. Push `index.html` to the default branch, enable Pages → root.

## 6. Known placeholders (confirm, then update)

- Employment start/end dates — omitted; shown as "~7 years".
- Public email — `sonalpandey937@gmail.com` (swap if a dedicated address is preferred).
- IISc program name — shown as "Agentic AI program"; add exact certificate title / other
  courses when available.
