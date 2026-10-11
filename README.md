# Shanahan Suresh

**Full-stack & AI product engineer** · Python + TypeScript · I design and ship production web apps, MCP servers and LLM tooling on GCP.

```text
Django / DRF · Next.js · SvelteKit · MCP · LLM agents · PostgreSQL · GCP Cloud Run · Terraform
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=flat&logo=svelte&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

These days I work on enterprise service-management (ITSM) platforms at a multinational technology company. Before that, I built internal web platforms for a large Malaysian property & construction group: Django and REST APIs, SvelteKit and Next.js frontends, and GCP Cloud Run underneath it all.

I'm more product engineer than code-writer. What matters is the outcome users actually get, so I treat UI/UX, reliability and load as part of the craft, not afterthoughts.

### Shipped at work

<sub>Private / enterprise, so no public code. Happy to walk through any of them.</sub>

<table>
<tr>
<td width="50%" valign="top">

**AI assistant for an OHSE platform**<br>
<sub>MCP · FastAPI · OpenAI + Gemini · Next.js</sub>

An MCP server that generates its tools from the platform's Django OpenAPI schema, so staff can query records and take actions in plain language. The agent falls back from OpenAI to Gemini on quota limits, recovers from API validation errors on its own, and runs behind a Next.js chat UI.

</td>
<td width="50%" valign="top">

**HR performance platform**<br>
<sub>Django REST · SvelteKit · Azure AD · Cloud Tasks</sub>

Django REST backend with 150+ endpoints and a SvelteKit frontend with 70+ routes and role-based UIs. Azure AD SSO and JWT auth, with GCP Cloud Tasks driving scheduled sync and notification jobs.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Event RSVP platform**<br>
<sub>Next.js · PostgreSQL / Prisma · Cloud Run · Pub/Sub</sub>

Load-tested to ~12k RSVPs an hour on auto-scaling Cloud Run and Cloud SQL, with a Pub/Sub fan-out pipeline sending email and WhatsApp confirmations. Glassmorphism UI.

</td>
<td width="50%" valign="top">

**Incident-management system**<br>
<sub>Next.js · Django · Celery / Redis · Azure AD</sub>

Decoupled Next.js frontend and Django API with Azure AD SSO, Celery/Redis background jobs and server-side PDF report generation.
</td>
</tr>
</table>

### Built on my own time

- **SiteMedic**: an agent that audits small-business websites from the outside (DNS, TLS, headers, forms, PageSpeed with a Gemini visual review), explains each finding with evidence, and, with the owner's approval, keeps watch with scheduled rechecks that alert on regression. Google ADK 2, Gemini on Vertex AI, Cloud Run, Firestore, Cloud Scheduler.
- **Tech Scout**: an LLM news-intelligence pipeline. It pulls RSS, Hacker News and research papers, scores and de-duplicates them with an LLM, and emails a ranked digest scoped to a team's stack. Runs as a scale-to-zero Cloud Run Job; every topic is plain YAML.
- **[django-openapi-mcp](https://github.com/Shanahan-Suresh/django-openapi-mcp)**: an open reference implementation that turns any DRF project's OpenAPI schema into MCP tools. Read-only by default, auth carried through, stdio and Streamable HTTP.

Research-wise, I co-authored [HeatGen](https://github.com/Shanahan-Suresh/segp-group4a-deep-learning-network), a neural-network tool for predicting heat-absorbing pavement materials, published in the *Journal of Engineering Science and Technology* ([paper](https://jestec.taylors.edu.my/Vol%2018%20Issue%202%20April%202023/18_2_16.pdf)).

### Reach me

Always happy to talk full-stack, product, MCP and agentic workflows, or to contribute to interesting projects.

🌐 [shanahansuresh.com](https://shanahansuresh.com) · 📬 [shanahan.suresh1@gmail.com](mailto:shanahan.suresh1@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/shanahan-suresh/)
