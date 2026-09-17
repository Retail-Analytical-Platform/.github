# Business & Product Case Studies Team

> Business and product case studies that uncover actionable insights from multiple business perspectives to support strategic product decisions.

## About This Project

This team focuses on dissecting real (or hypothetical) business and product case studies from various perspectives — strategy, product, operations, finance, and users — to produce insights that can be directly applied to product decision-making.

The final output of each case study is ideally not just academic analysis, but actionable recommendations: "what should the product team do based on these findings?"

---

## Local Setup

This repo provides a retail star-schema dataset (`data/`) for query
and data-analysis practice — one fact table + four dimension tables, complete with
verified answers (see [`data/README.md`](data/README.md)).

To load this dataset into a database and practice real queries, run
PostgreSQL locally via Docker:

**[Docker.md](Docker.md)** — how to install & run PostgreSQL in Docker,
up to connecting from the VS Code PostgreSQL extension.

**[Data-Integration-Docker.md](Data-Integration-Docker.md)** — how to load
the CSVs in `data/` into that database.

**[Supabase-Migration.md](Supabase-Migration.md)** — how to migrate that data
to Supabase so it can be accessed online / without Docker.

---

## Objectives

- Train cross-functional strategic thinking (business, product, data, UX).
- Build a repository of case studies that can serve as an internal team reference.
- Produce concrete recommendations that can be tested or implemented.
- Sharpen data storytelling and insight presentation skills for stakeholders.

---

## Steps to Build This Project

### 1. Define the Team's Scope & Objectives
- Determine the focus: is the case study general industry, startup-specific, or internal to your own company?
- Establish the target audience for the case study results (e.g., product team, prospective investors, personal portfolio, learning community).
- Write a brief team mission statement (you can use the description you've already written as a starting point).

### 2. Establish Team Structure
- **Case Lead** — determines the topic, coordinates the timeline.
- **Business Analyst** — analyzes business model, revenue, market positioning.
- **Product Analyst** — analyzes features, UX, product-market fit.
- **Data/Research Support** — gathers supporting data, secondary research.
- **Writer/Editor** — compiles the final narrative so it's easy to read.

> For a small team, one person may take on multiple roles.

### 3. Build an Analysis Framework
Establish a standard framework so every case study stays consistent, for example a combination of:
- **Business Model Canvas** — to understand the business model as a whole.
- **SWOT / Porter's Five Forces** — for competitive and strategic analysis.
- **Jobs to be Done (JTBD)** — to understand user motivation.
- **RICE / ICE Scoring** — to prioritize recommendations.
- **North Star Metric & AARRR (Pirate Metrics)** — for a growth/product perspective.

Document this framework in a separate file (`/framework.md`) so all team members use the same standard.

### 4. Select & Validate the Case Study Topic
- Create a list of candidate companies/products worth dissecting.
- Prioritize based on: availability of public data, industry relevance, level of complexity.
- Validate with the team: is this topic rich enough to be analyzed from many perspectives?

### 5. Collect Data & Research
- Sources: annual reports, news articles, interviews (if possible), public data (app store reviews, social listening, etc.).
- Record all sources to maintain credibility and avoid unverified claims.
- Store raw research in the `/research/{case-name}/` folder.

### 6. Perform Multi-Perspective Analysis
Each case study should be analyzed from at least 3 perspectives, for example:
- **Business Perspective**: revenue model, unit economics, market positioning.
- **Product Perspective**: key features, user flow, differentiation.
- **User Perspective**: pain points, motivation, adoption barriers.
- **Competitive Perspective**: positioning relative to competitors.

### 7. Formulate Insights & Recommendations
- Insights must be specific and data-backed, not general opinions.
- Each insight should ideally be followed by a clear action recommendation: *"Because of X, the product team should do Y to achieve Z."*
- Use a prioritization framework (RICE/ICE) to rank which recommendations would have the most impact.

### 8. Document in a Standard Format
Create a case study template, for example:
```
1. Executive Summary
2. Company/Product Background
3. Problem/Challenge Discussed
4. Analysis (per perspective)
5. Key Insights
6. Strategic Recommendations
7. References/Data Sources
```
Store this template in `/templates/case-study-template.md`.

### 9. Team Review & Discussion
- Hold an internal review session before publishing — check the validity of the arguments, not just the writing quality.
- Invite a "devil's advocate" perspective to test how well the recommendations hold up.

### 10. Publish & Gather Feedback
- Publish the case study (internal blog, Notion, Medium, or this repo).
- Ask for feedback from outside the team to test whether the insights are truly actionable.
- Update the case study if new relevant data emerges.

### 11. Build Team Rhythm & Cadence
- Set an output target (e.g., 1 case study every 2 weeks).
- Hold regular retrospectives: what can be improved in the analysis process or team collaboration.

---
