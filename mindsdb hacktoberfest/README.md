# 🎃 MindsDB Hacktoberfest 2025 

## Supercharging AI analytical Apps with Knowledge Bases ⚡

This Hacktoberfest, MindsDB challenges you to build RAG apps using Knowledge Bases.


### 🌟 Why Join?
MindsDB's Hacktoberfest is your chance to turn code into impact:
- Build tools that answer real business questions.
- Help teams move beyond rigid dashboards and siloed data.
- Level up your open-source contributions with AI-native analytics apps.
- Compete for prizes: GitHub sponsorships, swag, and a Prize Draw for a [MacBook Pro 16" M4 Chip](https://www.apple.com/shop/buy-mac/macbook-pro/16-inch-space-black-standard-display-apple-m4-pro-with-14-core-cpu-and-20-core-gpu-48gb-memory-512gb).
- Get your project featured on the MindsDB blog + community.

**Your mission:** Create AI apps powered by MindsDB's Knowledge Bases that query enterprise-like data in place—delivering accurate, explainable answers.


------

## 🛠️ Core Task

- Pick a use case where there is unstructured data and can benefit from making it searchable via natural language: (For example analyzing CRM Unstructured data: Notes, Emails, Calls, Meetings, Tasks, Conversations → transcripts, attachments, Tickets → Descriptions, associated notes/emails)
- Pick the datasources that you will need for these use cases
- Write a blog post (Medium, Hashnode, dev.to, LinkedIn) explaining your use case.
- Write a pull request with your use-case implementation in the use-cases folder (create a folder for your use case with a descriptive name)
- Your use case implementation can be either a notebook or an app, that uses MindsDB + Knowledge bases
- Promote your use case on Linkedin, and X/Twitter with a post mentioning @mindsdb.

-----

## 🏆 Prize Categories

Stand a chance to win a [MacBook Pro 16" M4 Chip](https://www.apple.com/shop/buy-mac/macbook-pro/16-inch-space-black-standard-display-apple-m4-pro-with-14-core-cpu-and-20-core-gpu-48gb-memory-512gb) in our Prize Draw!

### 🔥 Most Popular Pull Requests
- Top 3 Pull Requests with the most thumbs up (👍) or heart (❤️) reaction wins win GitHub sponsorship prizes.
- Every 10 positive reaction = 1 entry into the Apple MacBook Pro prize draw.
  
**Prizes:**
- 🥇 $1500 + MindsDB T-shirt
- 🥈 $1000 + MindsDB T-shirt
- 🥉 $500 + MindsDB T-shirt


(Note: GitHub sponsorship must be available in your country in order to receive the prize, participants to check before they contribute. Automated voting is not allowed—violations will be disqualified.)

### 📣 Social Media Awareness
Top 3 posts (LinkedIn/X) with the most engagement win:
- MindsDB T-shirt
- 1 entry into the Apple MacBook Pro prize draw
- $100 Github Sponsorship

(Github Sponsorship may change depending on the amount of engagement a social media post received).

### ✍️ Best Blog Content
Top 3 blog posts (as judged by the MindsDB team) win:
- MindsDB T-shirt
- Blog feature on the official MindsDB website
- 1 entry into the Apple MacBook Pro prize draw
- $100 Github Sponsorship.

----

## 🎯 Goals
- Showcase zero-ETL, data-in-place AI analytics with MindsDB KBs.
- Demonstrate hybrid semantic + SQL logic and use Evaluate KB for quality.
- Encourage integrations (Salesforce, BigQuery, Confluence, Gong, Postgres, etc.).
- Create repeatable app templates for use cases in accordance to our industries listed on our webpage, i.e [Finance Services](https://mindsdb.com/solutions/industry/ai-data-solution-financial-services), [Energy & Utilities](https://mindsdb.com/solutions/industry/ai-data-solution-energy-utilities), [Retail & E-commerce](https://mindsdb.com/solutions/industry/ai-data-solution-retail-ecommerce), [Enterprise Software Vendors](https://mindsdb.com/solutions/industry/ai-data-solution-b2b-tech), or for another Enterprise industry.

## 👩‍💻 Who Should Join?
- AI/ML Enthusiasts (especially RAG & semantic search fans)
- SQL-savvy developers (data engineers, full-stack devs, data scientists)
- Existing MindsDB users & open-source contributors

## 🔑 Example Use Cases
- Decision BI Re-imagined → NLQ → KPIs/charts (with auditability).
- Operations Copilot → Root cause & SOP search across tickets/wikis.
- Customer Intelligence → 360° CRM + docs with explainable recs.
- Compliance & Controls → Policy/filing QA with citations + risk flags.
- Wildcard → Any creative KB-powered analytics app.

## 🛤️ Tracks

### Track 1: Build an application with MindsDB Knowledge Bases

Create a functional application (CLI, Web App, API, Bot Interface etc.) where the primary interaction or feature relies on the semantic query results from the KB. This includes:
  - A functional, empty Knowledge Base exists within their MindsDB instance (Cloud or local)
  - Participant connects a data source (Salesforce, Gong, Hubspot, Postgres or files) and successfully ingests text data into the KB using INSERT INTO. The KB is populated with text data suitable for semantic querying.
  - Demonstrate retrieving meaningful results based on semantic similarity and metadata filtering using [Hybrid Search](https://docs.mindsdb.com/mindsdb_sql/knowledge_bases/hybrid_search). Successfully retrieve relevant data chunks/rows based on semantic queries. 
  - Provide a public GitHub repo with clear setup instructions and documentation, along with a working application that demonstrates a practical use case for Knowledge Bases, supported by a short, shareable demo video showcasing the app in action.

### Track 2: Advanced Capabilities
- Jobs Integration: Auto-update KBs with [CREATE JOB](https://docs.mindsdb.com/mindsdb_sql/sql/create/jobs).
- [Agent Integration](https://docs.mindsdb.com/mindsdb_sql/agents/agent)
- Metadata Filtering: Hybrid search with semantic + structured filters for eg. LIKE and BETWEEN operators.
- [Evaluate Knowledge Bases](https://docs.mindsdb.com/mindsdb_sql/knowledge_bases/evaluate): Produce an evaluation report (MRR, Hit@k, relevancy, etc.).
- [Hybrid Search](https://docs.mindsdb.com/mindsdb_sql/knowledge_bases/hybrid_search): Perform semantic and metadata filtering queries on your data.

-----

## 📦 Deliverables/ Minimum Requirements
- Public GitHub repo with code + infra (Docker optional).
- README: problem statement(what use case this solves), architecture, Knowledge Base schema, SQL examples, metrics.
- Demo UI (CLI or Web) + 5-min demo video
- Sample queries (Natural language + SQL).
- Evaluation report: metrics (MRR, Hit@k, avg relevancy, etc.).
- Blog post explaining how you built the application and what use case it solves.
- Social media posts on LinkedIn and Twitter about your use case, mention @mindsdb.

----

## 🚀 Get Started

- [MindsDB Documentation](https://docs.mindsdb.com/mindsdb)
- [MindsDB Knowledge Bases Documentation](https://docs.mindsdb.com/mindsdb_sql/knowledge_bases/overview)
- [SDK's and API documentation](https://docs.mindsdb.com/overview_sdks_apis)

As the main category is based on the amount of likes/upvotes your Pull Request receives, you can request to have it merged so that you can claim the merged PR by the official [Hacktoberfest organizers](https://hacktoberfest.com/participation/). Pull Requests will be merged 2 hours before the deadline.

----
## Ideas

| **Team / Function**         | **Finance & Insurance**                                                                                                                                                                                                        | **Healthcare & Life Sciences**                                                                                                                                                      | **Energy & Manufacturing**                                                                                                                                       | **Government & Legal**                                                                                                                      | **Research & Education**                                                                                                                           | **Tech, SaaS & AI Infra**                                                                                                                           | **Enterprise / Cross-Industry Ops**                                                                                                                              |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **🧾 Compliance / Risk**    | Regulatory filings, audit reports, policy docs<br>💬 *QA:* “Find all reports citing liquidity risk in 2024”<br>🧩 **Integrations:** PostgreSQL, Snowflake, ElasticSearch, SharePoint, Dropbox, Google Drive, QuickBooks, Slack | FDA/EMA docs, SOPs, adverse event reports<br>💬 *QA:* “Trials that mention IRB deviation?”<br>🧩 **Integrations:** PostgreSQL, MongoDB, Notion, Google Cloud Storage, MS SQL Server | NRC inspections, maintenance logs<br>💬 *QA:* “Reports mentioning turbine cracks”<br>🧩 **Integrations:** PostgreSQL, TimescaleDB, Oracle, S3, Azure Blob        | Procurement policies, memos<br>💬 *QA:* “Memos mentioning budget overruns”<br>🧩 **Integrations:** SharePoint, Microsoft Access, Box, Gmail | Grant compliance docs<br>💬 *QA:* “Projects acknowledging NIH funding”<br>🧩 **Integrations:** Zotero, Mendeley, Google Drive                      | SOC2, GDPR evidence docs<br>💬 *QA:* “Which systems lack risk assessments?”<br>🧩 **Integrations:** Confluence, Notion, GitHub, Jira, Slack         | ESG & vendor compliance forms<br>💬 *QA:* “Who hasn’t signed NDA rev3?”<br>🧩 **Integrations:** Salesforce, Google Sheets, Email, DocuSign (via API), SharePoint |
| **⚙️ Operations / Field**   | Branch ops reports, loan notes<br>💬 *QA:* “Underwriting exceptions by branch”<br>🧩 **Integrations:** MySQL, Snowflake, Salesforce, Email, Google Sheets                                                                      | Lab reports, clinical notes<br>💬 *QA:* “Recurring post-implant issues?”<br>🧩 **Integrations:** MongoDB, PostgreSQL, Notion, S3                                                    | Shift logs, SCADA text alerts<br>💬 *QA:* “Outages mentioning pump cavitation?”<br>🧩 **Integrations:** InfluxDB, TimescaleDB, Prometheus (via REST), PostgreSQL | Field inspection reports<br>💬 *QA:* “Bridge safety issues noted?”<br>🧩 **Integrations:** Google Cloud Storage, Dropbox, S3, MS SharePoint | Lab notebooks, experiments<br>💬 *QA:* “Failed tests due to reagent purity?”<br>🧩 **Integrations:** Notion, Google Drive, Zotero, ChromaDB        | Runbooks, support tickets<br>💬 *QA:* “Root causes of downtime tickets?”<br>🧩 **Integrations:** Jira, GitHub, Confluence, Slack                    | Facility reports, customer support logs<br>💬 *QA:* “Delivery issues by region?”<br>🧩 **Integrations:** Zendesk, Gmail, Salesforce, Google Sheets               |
| **🔬 R&D / Engineering**    | Quant models, research memos<br>💬 *QA:* “Which models use Monte Carlo VaR?”<br>🧩 **Integrations:** Databricks, PostgreSQL, GitHub, Confluence                                                                                | Trial protocols, biomedical research<br>💬 *QA:* “Genes linked to treatment response?”<br>🧩 **Integrations:** MongoDB, Milvus, Qdrant, Zotero, Mendeley                            | Design reviews, test reports<br>💬 *QA:* “Materials failed in stress tests?”<br>🧩 **Integrations:** PostgreSQL, Oracle, SharePoint, S3                          | Policy studies, pilot reports<br>💬 *QA:* “Programs evaluating IoT sensors?”<br>🧩 **Integrations:** Notion, Google Drive, SharePoint       | Academic papers, datasets<br>💬 *QA:* “Who published on federated learning?”<br>🧩 **Integrations:** Google Books, Zotero, ArXiv (via web), DuckDB | Architecture reviews, Git issues<br>💬 *QA:* “Modules changed before latency spike?”<br>🧩 **Integrations:** GitHub, GitLab, Jira, Notion, ChromaDB | Product PRDs, process docs<br>💬 *QA:* “Automation proposals this year?”<br>🧩 **Integrations:** Notion, Confluence, Google Docs, GitHub                         |
| **⚖️ Legal / Contracts**    | Loan agreements, risk clauses<br>💬 *QA:* “Contracts with force majeure?”<br>🧩 **Integrations:** SharePoint, Dropbox, Google Drive, Snowflake                                                                                 | Site agreements, NDAs<br>💬 *QA:* “Trials with data-sharing clauses?”<br>🧩 **Integrations:** MS SharePoint, Notion, Email                                                          | Vendor SLAs<br>💬 *QA:* “Maintenance contracts mentioning vibration warranty?”<br>🧩 **Integrations:** PostgreSQL, Dropbox, SharePoint                           | Case files, legislation<br>💬 *QA:* “Cases citing statute 14-C?”<br>🧩 **Integrations:** ElasticSearch, Solr, PostgreSQL, Google Drive      | IP licensing docs<br>💬 *QA:* “Collaborations with MIT?”<br>🧩 **Integrations:** Notion, Zotero, Google Drive                                      | Partner contracts, OSS licenses<br>💬 *QA:* “Repos using AGPL?”<br>🧩 **Integrations:** GitHub, GitLab, Notion                                      | Customer contracts<br>💬 *QA:* “Contracts expiring Q1 2026?”<br>🧩 **Integrations:** Salesforce, SharePoint, Dropbox, Email                                      |
| **💰 Finance / Strategy**   | Analyst reports, call transcripts<br>💬 *QA:* “CFO sentiment by quarter?”<br>🧩 **Integrations:** Financial_Modeling_Prep, QuickBooks, Snowflake, PostgreSQL, Email                                                            | R&D budgets<br>💬 *QA:* “Therapeutic areas over budget?”<br>🧩 **Integrations:** PostgreSQL, Snowflake, Google Sheets                                                               | CapEx memos, project costs<br>💬 *QA:* “Cost variance per plant?”<br>🧩 **Integrations:** PostgreSQL, Oracle, Excel (via Sheets), QuickBooks                     | Budgets & grants<br>💬 *QA:* “Projects over $5M funding?”<br>🧩 **Integrations:** Google Sheets, PostgreSQL, SharePoint                     | Grant summaries<br>💬 *QA:* “Labs exceeding budgets?”<br>🧩 **Integrations:** Google Sheets, Zotero, Notion                                        | Investor updates<br>💬 *QA:* “Delayed GTM features?”<br>🧩 **Integrations:** Notion, Google Drive, Slack                                            | P&L reports<br>💬 *QA:* “Which ops sites exceed cost benchmarks?”<br>🧩 **Integrations:** QuickBooks, Google Sheets, Snowflake                                   |
| **🧩 Customer / Support**   | Claims, support chat logs<br>💬 *QA:* “Common causes of claim denials?”<br>🧩 **Integrations:** Zendesk, Email, Slack, Salesforce                                                                                              | Patient feedback<br>💬 *QA:* “Post-visit complaints?”<br>🧩 **Integrations:** Email, Zendesk, Notion                                                                                | Vendor support tickets<br>💬 *QA:* “Frequent field service failures?”<br>🧩 **Integrations:** Jira, Slack, PostgreSQL                                            | Citizen helpdesk<br>💬 *QA:* “Permit delays causes?”<br>🧩 **Integrations:** Zendesk, MS Teams, SharePoint                                  | Student feedback<br>💬 *QA:* “Top paper rejection reasons?”<br>🧩 **Integrations:** Gmail, Notion, Zotero                                          | Support tickets, Slack threads<br>💬 *QA:* “Feature requests tied to churn?”<br>🧩 **Integrations:** Slack, Intercom, HubSpot, Salesforce           | IT helpdesk, HR chat logs<br>💬 *QA:* “Recurring release issues?”<br>🧩 **Integrations:** Jira, Slack, Gmail, Confluence                                         |
| **📘 Knowledge / Training** | Onboarding manuals, AML docs<br>💬 *QA:* “Changes to AML since 2023?”<br>🧩 **Integrations:** Confluence, Notion, SharePoint                                                                                                   | Clinical guidelines, manuals<br>💬 *QA:* “Latest insulin dosage protocol?”<br>🧩 **Integrations:** SharePoint, Notion, Google Drive                                                 | SOPs, maintenance guides<br>💬 *QA:* “Valve calibration steps?”<br>🧩 **Integrations:** PostgreSQL, Dropbox, Google Drive                                        | Agency handbooks<br>💬 *QA:* “Emergency declaration steps?”<br>🧩 **Integrations:** SharePoint, Notion                                      | Curricula, lecture notes<br>💬 *QA:* “Course covering neural nets?”<br>🧩 **Integrations:** Notion, Google Drive, Zotero                           | API docs, runbooks<br>💬 *QA:* “How to configure S3 triggers?”<br>🧩 **Integrations:** GitHub, Confluence, Notion, S3                               | HR & IT playbooks<br>💬 *QA:* “Vacation policy updates 2025?”<br>🧩 **Integrations:** Confluence, Notion, SharePoint                                             |


**Deadline:**
The competion ends on 31st October 2025 00:00 PST. It is advised to make Pull Requests well in advanced. We wish everyone goodluck!

**Hack smarter. Query faster. Build the Next Generation of AI Analytics Apps with MindsDB.**




