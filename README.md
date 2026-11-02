# Jatin Kumar — Data Analyst & Analytics Engineer Portfolio

A responsive portfolio website presenting my data-analysis, business-intelligence, data-modelling, and analytics-engineering projects.

The portfolio focuses on the business problem, modelling decisions, implementation approach, and measurable project scope rather than displaying screenshots without context.

[![Live Portfolio](https://img.shields.io/badge/Live_Portfolio-jatinanalytics.co.in-111827?style=for-the-badge&logo=vercel&logoColor=white)](https://jatinanalytics.co.in/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jatin_Kumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jatin-kumar-5a46a720a)
[![GitHub](https://img.shields.io/badge/GitHub-jatinkumar--analytics-181717?style=for-the-badge&logo=github)](https://github.com/jatinkumar-analytics)

## Portfolio highlights

- Responsive single-page portfolio
- Searchable project gallery with technology filters
- Dedicated project-detail dialogs
- Standalone engineering case-study pages
- Power BI report embeds where a published report is available
- GitHub source and project-file links
- Deep links for sharing an individual project directly
- Kaggle dataset case studies
- Resume, education, certification, and contact sections
- Lightweight portfolio assistant for project discovery
- Dark and light themes

## Featured case studies

### Airbnb Analytics Engineering Pipeline

An end-to-end analytics-engineering project using AWS S3, Snowflake, and dbt Core.

- 5,700 source records
- 11 layered dbt models
- Booking-grain Fact with three Dimensions
- Two SCD Type 2 snapshots
- 40 data-quality tests

[Read the case study](https://jatinanalytics.co.in/airbnb-analytics-engineering.html) · [View the repository](https://github.com/jatinkumar-analytics/airbnb-dbt-snowflake)

### BharatMart Enterprise Retail Model

A Microsoft Fabric dimensional-modelling project covering retail, supply-chain, and workforce processes.

- 13 conformed Dimensions
- Nine Facts with declared grains
- One Product–Supplier Bridge
- Retail Direct Lake model: 20 tables and 32 measures
- Workforce Direct Lake model: six tables and six measures

[Read the case study](https://jatinanalytics.co.in/bharatmart-fabric-model.html) · [View the repository](https://github.com/jatinkumar-analytics/Datamart_project)

## Project collection

The portfolio currently presents 11 projects across:

| Area | Examples |
|---|---|
| Analytics engineering | Airbnb pipeline, Fabric Sales Analytics |
| Dimensional modelling | BharatMart enterprise retail model |
| Operations analytics | Supply Chain and Logistics Control Tower |
| Financial analytics | Indian Financial Fraud Analytics, Bank Analytics |
| Sales analytics | E-Commerce Sales Analytics, Zomato Analytics |
| Workforce analytics | HR Analytics |
| Sports analytics | Virat Kohli Career Analytics |
| Educational synthetic analytics | Smoking and Health Risk Analytics |

Healthcare-related content uses synthetic educational data and does not represent clinical work or medical guidance.

## Technology coverage

```text
Microsoft Fabric · OneLake · Lakehouse · Fabric Warehouse · Direct Lake
Power BI · DAX · Data Modelling · TMDL
SQL · Snowflake · dbt Core · AWS S3
Python · Pandas · NumPy
Git · GitHub · Vercel
```

## Repository structure

```text
jatinanalytics-vercel/
├── index.html
├── style.css
├── v3.css
├── script.js
├── airbnb-analytics-engineering.html
├── bharatmart-fabric-model.html
├── images/
│   ├── airbnb/
│   └── bharatmart/
├── projects/
├── assets/
├── resume.pdf
├── certificate.pdf
├── vercel.json
└── README.md
```

## How project content is organised

### Standard portfolio projects

Most projects use an object inside `script.js` and a matching folder under:

```text
projects/<Project Folder>/
```

The project object stores the title, summary, metric, technology tags, source link, and detail-dialog content.

### Standalone case studies

Larger engineering and data-modelling projects use a dedicated HTML page and image folder:

```text
<project-case-study>.html
images/<project-name>/
```

Current standalone case studies:

```text
airbnb-analytics-engineering.html
bharatmart-fabric-model.html
```

## Add or update a project

1. Add or edit the project object in `script.js`.
2. Store supporting files under the correct `projects/` or `images/` folder.
3. Use landscape WebP images where possible.
4. Confirm that titles, metrics, links, and technology tags match the actual implementation.
5. Test the project card, detail view, source link, and mobile layout locally.
6. Commit the reviewed files to GitHub.

## Run locally

From the repository root:

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

Open:

```text
http://localhost:4173
```

A local server should be used instead of opening `index.html` directly because project content and assets are loaded through browser requests.

## Deployment

The website is deployed through Vercel with the custom domain:

https://jatinanalytics.co.in/

Pushing reviewed changes to the connected production branch triggers a new deployment.

## Design principles

- Keep project claims factual and verifiable.
- Explain the business problem before listing tools.
- Show grain, modelling, validation, and delivery decisions.
- Use readable screenshots instead of crowded galleries.
- Avoid claiming production deployment where only development-scale work was completed.
- Clearly label synthetic and educational datasets.

## Contact

**Jatin Kumar**  
Data Analyst · Analytics Engineer · BI Projects  
Delhi · Gurugram · Delhi NCR

- Portfolio: https://jatinanalytics.co.in/
- LinkedIn: https://www.linkedin.com/in/jatin-kumar-5a46a720a
- GitHub: https://github.com/jatinkumar-analytics
- Email: jating1416@gmail.com
