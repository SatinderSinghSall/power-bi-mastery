# 📊 Power BI — From Zero to Advanced

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Learning%20Roadmap-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Level-Beginner%20%E2%86%92%20Advanced-0078D4?style=for-the-badge" alt="Level"/>
  <img src="https://img.shields.io/badge/Focus-Data%20Analytics-6C63FF?style=for-the-badge" alt="Data Analytics"/>
  <img src="https://img.shields.io/badge/DAX-Advanced-512BD4?style=for-the-badge" alt="DAX"/>
  <img src="https://img.shields.io/badge/Power%20Query-M%20Language-00A4EF?style=for-the-badge" alt="Power Query"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Progress-orange?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/Projects-5+-green?style=flat-square" alt="Projects"/>
  <img src="https://img.shields.io/badge/Portfolio-Ready-success?style=flat-square" alt="Portfolio"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License"/>
</p>

<p align="center">
  <strong>A structured, project-based journey from Power BI fundamentals to advanced Business Intelligence.</strong>
</p>

---

## 📖 About This Repository

This repository documents my structured journey to learn **Microsoft Power BI from the ground up to an advanced, professional level**.

The objective is not simply to learn how to create attractive dashboards, but to develop a strong understanding of the complete Business Intelligence workflow:

> **Data → Transformation → Modeling → DAX → Visualization → Analytics → Security → Deployment → Optimization**

Power BI combines data connectivity, data preparation, semantic modeling, calculations, reporting, and distribution into an integrated analytics platform.

This repository therefore focuses on both **technical implementation** and **business-oriented analytical thinking**.

---

## 🎯 Learning Objectives

By completing this roadmap, I aim to become capable of:

- Understanding Business Intelligence fundamentals
- Connecting Power BI to multiple data sources
- Cleaning and transforming data using Power Query
- Writing Power Query M expressions
- Designing professional semantic models
- Applying star-schema principles
- Building relationships between tables
- Writing beginner-to-advanced DAX
- Understanding row context and filter context
- Performing time-intelligence analysis
- Building interactive dashboards
- Designing executive-level reports
- Implementing Row-Level Security (RLS)
- Publishing and managing reports in Power BI Service
- Optimizing data models and DAX
- Working with enterprise BI concepts
- Building portfolio-quality Power BI projects

---

# 🧭 Complete Learning Roadmap

```text
                         POWER BI MASTERY
                               │
             ┌─────────────────┴─────────────────┐
             │                                   │
        FOUNDATIONS                         POWER BI CORE
             │                                   │
      ┌──────┴──────┐                    ┌───────┴────────┐
      │             │                    │                │
    Excel          SQL              Desktop          Visualization
      │             │                    │                │
      └──────┬──────┘                    │                │
             │                           │                │
             └──────────────┬────────────┘                │
                            │                             │
                     POWER QUERY                         │
                            │                             │
                       Data Cleaning                      │
                            │                             │
                            ▼                             │
                    DATA MODELING ◄──────────────────────┘
                            │
                       Star Schema
                            │
                            ▼
                          DAX
                            │
              ┌─────────────┼─────────────┐
              │             │             │
            Basic        Advanced      Time Intelligence
              │             │             │
              └─────────────┼─────────────┘
                            │
                            ▼
                    ADVANCED POWER BI
                            │
          ┌─────────────────┼──────────────────┐
          │                 │                  │
         RLS            Performance        Advanced UX
          │             Optimization            │
          │                 │                  │
          └─────────────────┼──────────────────┘
                            │
                            ▼
                     POWER BI SERVICE
                            │
             ┌──────────────┼──────────────┐
             │              │              │
          Workspaces      Refresh       Deployment
             │              │              │
             └──────────────┼──────────────┘
                            │
                            ▼
                     REAL-WORLD PROJECTS
                            │
                            ▼
                    PROFESSIONAL / JOB READY
```

---

# 📚 Curriculum

## 🟢 Phase 01 — Data & BI Foundations

### Topics

- What is Business Intelligence?
- What is Data Analytics?
- OLTP vs OLAP
- Databases
- Tables and relationships
- Primary keys
- Foreign keys
- Dimensions and measures
- Structured vs unstructured data
- Data types
- Aggregation
- Basic descriptive statistics

### Excel Foundations

- Excel Tables
- PivotTables
- PivotCharts
- XLOOKUP
- IF / IFS
- SUMIF / SUMIFS
- COUNTIF / COUNTIFS
- Basic data cleaning
- Basic visualization

### SQL Foundations

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- JOIN
- CASE
- Aggregate functions
- Subqueries
- CTEs
- Window functions

---

# 🔵 Phase 02 — Power BI Fundamentals

### Power BI Ecosystem

- Power BI Desktop
- Power BI Service
- Power BI Mobile
- Power BI Report Builder
- Workspaces
- Reports
- Dashboards
- Semantic models
- Apps

Power BI Desktop is the primary authoring environment for creating reports and semantic models, while Power BI Service provides cloud-based publishing, sharing, workspaces, and administration capabilities.

### Core Skills

- Installing Power BI Desktop
- Importing data
- Connecting to Excel
- Connecting to CSV
- Connecting to SQL Server
- Connecting to web sources
- Understanding the interface
- Creating reports
- Creating pages
- Adding visuals
- Filters
- Slicers
- Drill-down
- Drill-through
- Bookmarks
- Buttons
- Report navigation

---

# 🟡 Phase 03 — Power Query

Power Query is a core component of the data preparation workflow. It is designed to connect, transform, combine, and load data before analysis. Its transformation logic is expressed using the **Power Query M language**.

### Beginner

- Connect to data
- Remove columns
- Rename columns
- Change data types
- Filter rows
- Remove duplicates
- Handle null values
- Replace values
- Split columns
- Merge columns

### Intermediate

- Merge Queries
- Append Queries
- Group By
- Pivot
- Unpivot
- Conditional Columns
- Custom Columns
- Parameters
- Query Dependencies

### Advanced

- M language
- Functions
- Variables
- `let ... in`
- Custom functions
- Error handling
- Dynamic transformations
- Query folding
- Performance-aware transformations

### Core Workflow

```text
SOURCE
  │
  ▼
CONNECT
  │
  ▼
TRANSFORM
  │
  ▼
CLEAN
  │
  ▼
COMBINE
  │
  ▼
LOAD
  │
  ▼
SEMANTIC MODEL
```

---

# 🟠 Phase 04 — Data Modeling

A strong semantic model is one of the most important foundations of professional Power BI development.

### Topics

- Fact tables
- Dimension tables
- Star schema
- Snowflake schema
- Relationships
- One-to-many
- One-to-one
- Many-to-many
- Cardinality
- Cross-filter direction
- Active relationships
- Inactive relationships
- Role-playing dimensions
- Date tables
- Hierarchies
- Granularity

### Target Architecture

```text
                   ┌─────────────┐
                   │ Date Dim    │
                   └──────┬──────┘
                          │
                          │
┌─────────────┐     ┌─────▼──────┐     ┌─────────────┐
│ Product Dim │────►│ Sales Fact │◄────│ Customer Dim│
└─────────────┘     └─────┬──────┘     └─────────────┘
                          │
                          │
                   ┌──────▼──────┐
                   │ Store Dim   │
                   └─────────────┘
```

### Key Principle

> **Build the model correctly before trying to fix the report with DAX.**

---

# 🔴 Phase 05 — DAX

**DAX — Data Analysis Expressions** — is the formula language used for calculations in Power BI and tabular models. It supports measures, calculated columns, calculated tables, and security expressions.

## Level 1 — DAX Fundamentals

```DAX
Total Sales =
SUM(Sales[SalesAmount])
```

Learn:

- `SUM`
- `AVERAGE`
- `COUNT`
- `COUNTROWS`
- `DISTINCTCOUNT`
- `MIN`
- `MAX`
- `DIVIDE`
- `IF`
- `SWITCH`

---

## Level 2 — Intermediate DAX

Learn:

- `CALCULATE`
- `FILTER`
- `ALL`
- `REMOVEFILTERS`
- `ALLEXCEPT`
- `VALUES`
- `SELECTEDVALUE`
- `HASONEVALUE`
- `ISFILTERED`

Example:

```DAX
Total Sales =
SUM(Sales[SalesAmount])

Total Profit =
SUM(Sales[SalesAmount])
    - SUM(Sales[Cost])

Profit Margin =
DIVIDE(
    [Total Profit],
    [Total Sales]
)
```

---

## Level 3 — DAX Context

Master:

### Row Context

Understanding the current row during evaluation.

### Filter Context

Understanding how filters from visuals, slicers, relationships, and DAX expressions affect calculations.

### Context Transition

Understanding how `CALCULATE` changes evaluation context.

These concepts are essential for writing reliable advanced DAX.

---

## Level 4 — Iterators

Learn:

- `SUMX`
- `AVERAGEX`
- `MINX`
- `MAXX`
- `COUNTX`
- `RANKX`

Example:

```DAX
Revenue =
SUMX(
    Sales,
    Sales[Quantity] * Sales[UnitPrice]
)
```

---

# 📅 Phase 06 — Time Intelligence

Master:

- Year-over-Year
- Month-over-Month
- Quarter-over-Quarter
- YTD
- MTD
- QTD
- Previous Year
- Previous Month
- Rolling averages
- Running totals

Important functions:

```text
DATEADD
DATESYTD
DATESMTD
DATESQTD
TOTALYTD
TOTALMTD
TOTALQTD
SAMEPERIODLASTYEAR
PREVIOUSMONTH
PREVIOUSYEAR
```

---

# 🎨 Phase 07 — Report & Dashboard Design

### Visualization

Learn how to select the appropriate visual for the analytical question.

### Visual Types

- Cards
- KPI
- Tables
- Matrix
- Bar charts
- Column charts
- Line charts
- Area charts
- Scatter plots
- Maps
- Treemaps
- Waterfall
- Funnel
- Decomposition Tree
- Key Influencers

### UX

- Visual hierarchy
- Consistent spacing
- Typography
- Color theory
- Accessibility
- Navigation
- Tooltips
- Drill-through
- Bookmarks
- Dynamic titles
- Conditional formatting
- Mobile layouts

### Design Principle

> **A dashboard should answer business questions, not simply display charts.**

---

# 🟣 Phase 08 — Advanced Analytics

Topics:

- What-if parameters
- Field parameters
- Dynamic measures
- Dynamic titles
- Dynamic formatting
- Scenario analysis
- Segmentation
- Pareto analysis
- ABC analysis
- Ranking
- Statistical analysis
- Forecasting
- Anomaly detection
- Decomposition analysis

---

# 🔐 Phase 09 — Security

## Row-Level Security

Learn:

- Static RLS
- Dynamic RLS
- Roles
- Security filters
- `USERPRINCIPALNAME()`
- `USERNAME()`
- Security tables

Example concept:

```text
                    USERS
                      │
                      ▼
              SECURITY TABLE
                      │
                      ▼
                 DATA MODEL
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
      Region A                 Region B
```

RLS can use DAX expressions to restrict which rows are accessible to different users.

---

# ⚡ Phase 10 — Performance Optimization

### Model Optimization

- Remove unnecessary columns
- Reduce cardinality
- Use appropriate data types
- Prefer star schema
- Optimize relationships
- Reduce model size

### DAX Optimization

- Avoid unnecessary iterators
- Optimize `CALCULATE`
- Use variables
- Reduce expensive virtual tables
- Understand filter propagation

### Tools

- Power BI Performance Analyzer
- DAX Studio
- Tabular Editor
- VertiPaq Analyzer

### Advanced Concepts

- Storage Engine
- Formula Engine
- VertiPaq
- Query plans
- Server timings
- xmSQL
- Query folding

---

# ☁️ Phase 11 — Power BI Service

Learn:

- Publishing
- Workspaces
- Apps
- Semantic models
- Reports
- Dashboards
- Permissions
- Sharing
- Scheduled refresh
- Data gateways
- Deployment pipelines
- Dataflows
- Lineage
- Endorsement
- Workspace governance

### Production Workflow

```text
              DEVELOPMENT
                   │
                   ▼
              VALIDATION
                   │
                   ▼
                  TEST
                   │
                   ▼
              PRODUCTION
                   │
                   ▼
               MONITOR
```

---

# 🏗️ Phase 12 — Enterprise Power BI

Advanced topics:

- Enterprise semantic models
- Composite models
- Import mode
- DirectQuery
- Direct Lake
- Incremental refresh
- Large semantic models
- Deployment pipelines
- Governance
- Workspace architecture
- Data lineage
- Gateway architecture
- Fabric integration
- Power BI Embedded
- APIs
- XMLA endpoints
- Tabular modeling

Power BI currently supports multiple storage/connectivity approaches, including Import, DirectQuery, and Direct Lake scenarios depending on the underlying architecture and data source.

---

# 🧪 Practical Projects

## Project 01 — Sales Analytics Dashboard

**Difficulty:** ⭐

### Objectives

- Import sales data
- Clean data
- Create relationships
- Build basic measures
- Create dashboard

### KPIs

- Revenue
- Orders
- Customers
- Profit
- Profit Margin

---

## Project 02 — Financial Performance Dashboard

**Difficulty:** ⭐⭐

### KPIs

- Revenue
- Expenses
- EBITDA
- Net Profit
- Gross Margin
- YoY Growth
- Budget vs Actual

### Skills

- DAX
- Time intelligence
- Variance analysis
- Dynamic KPIs

---

## Project 03 — HR Analytics

**Difficulty:** ⭐⭐

### Analysis

- Headcount
- Attrition
- Department
- Gender
- Job role
- Tenure
- Hiring trends

### Skills

- Data modeling
- DAX
- Slicers
- Drill-through
- HR metrics

---

## Project 04 — E-Commerce Analytics

**Difficulty:** ⭐⭐⭐

### Analysis

- Orders
- Revenue
- Profit
- Customers
- Products
- Categories
- Customer segmentation
- Repeat purchases

### Advanced Features

- RFM analysis
- Pareto analysis
- Dynamic rankings
- Time intelligence

---

## Project 05 — Executive Business Intelligence Platform

**Difficulty:** ⭐⭐⭐⭐⭐

This will be the flagship portfolio project.

### Features

- Executive dashboard
- Sales analytics
- Financial analytics
- Customer analytics
- Product analytics
- Advanced DAX
- Dynamic metrics
- Drill-through
- Bookmarks
- Tooltips
- RLS
- Scheduled refresh
- Performance optimization
- Power BI Service deployment

---

# 📊 Skills Matrix

| Skill             | Beginner | Intermediate | Advanced |
| ----------------- | :------: | :----------: | :------: |
| Power BI Desktop  |    ✅    |      ✅      |    ✅    |
| Power Query       |    ✅    |      ✅      |    ✅    |
| M Language        |          |      ✅      |    ✅    |
| Data Modeling     |    ✅    |      ✅      |    ✅    |
| Star Schema       |          |      ✅      |    ✅    |
| DAX               |    ✅    |      ✅      |    🔥    |
| Time Intelligence |          |      ✅      |    🔥    |
| Visualization     |    ✅    |      ✅      |    🔥    |
| RLS               |          |      ✅      |    🔥    |
| Power BI Service  |          |      ✅      |    🔥    |
| Performance       |          |              |    🔥    |
| DAX Studio        |          |              |    🔥    |
| Tabular Editor    |          |              |    🔥    |
| Enterprise BI     |          |              |    🔥    |

---

# 📈 Progress Tracker

## Foundations

- [ ] Business Intelligence fundamentals
- [ ] Data analytics fundamentals
- [ ] Excel fundamentals
- [ ] SQL fundamentals

## Power BI

- [ ] Power BI Desktop
- [ ] Data sources
- [ ] Basic visuals
- [ ] Filters
- [ ] Slicers
- [ ] Drill-through
- [ ] Bookmarks

## Power Query

- [ ] Data cleaning
- [ ] Merge
- [ ] Append
- [ ] Group By
- [ ] Pivot / Unpivot
- [ ] Parameters
- [ ] M language
- [ ] Query folding

## Data Modeling

- [ ] Fact tables
- [ ] Dimension tables
- [ ] Star schema
- [ ] Relationships
- [ ] Date tables
- [ ] Many-to-many
- [ ] Role-playing dimensions

## DAX

- [ ] Basic measures
- [ ] CALCULATE
- [ ] FILTER
- [ ] Iterators
- [ ] Variables
- [ ] Context
- [ ] Time intelligence
- [ ] Virtual tables
- [ ] Advanced DAX

## Advanced Power BI

- [ ] Dynamic measures
- [ ] Field parameters
- [ ] What-if parameters
- [ ] RLS
- [ ] Performance Analyzer
- [ ] DAX Studio
- [ ] Tabular Editor
- [ ] Incremental refresh

## Power BI Service

- [ ] Workspaces
- [ ] Publishing
- [ ] Refresh
- [ ] Gateway
- [ ] Apps
- [ ] Deployment pipelines
- [ ] Governance

---

# 🗂️ Repository Structure

```text
power-bi-mastery/
│
├── README.md
│
├── 01-foundations/
│   ├── business-intelligence/
│   ├── excel/
│   └── sql/
│
├── 02-power-bi-basics/
│   ├── getting-started/
│   ├── data-sources/
│   └── visualization/
│
├── 03-power-query/
│   ├── transformations/
│   ├── merging/
│   ├── appending/
│   └── m-language/
│
├── 04-data-modeling/
│   ├── star-schema/
│   ├── relationships/
│   └── date-tables/
│
├── 05-dax/
│   ├── fundamentals/
│   ├── intermediate/
│   ├── advanced/
│   └── time-intelligence/
│
├── 06-report-design/
│   ├── dashboards/
│   ├── ux/
│   └── visualization/
│
├── 07-advanced-power-bi/
│   ├── rls/
│   ├── performance/
│   └── optimization/
│
├── 08-power-bi-service/
│   ├── workspaces/
│   ├── refresh/
│   └── deployment/
│
├── projects/
│   ├── 01-sales-dashboard/
│   ├── 02-finance-dashboard/
│   ├── 03-hr-dashboard/
│   ├── 04-ecommerce-dashboard/
│   └── 05-executive-bi-platform/
│
├── datasets/
│
├── dax-snippets/
│
├── power-query-snippets/
│
├── notes/
│
└── resources/
```

---

# 🧠 Learning Methodology

This repository follows a **Learn → Practice → Build → Analyze → Optimize** methodology.

```text
        LEARN
          ↓
       PRACTICE
          ↓
        BUILD
          ↓
       ANALYZE
          ↓
       OPTIMIZE
          ↓
       DOCUMENT
          ↓
        REPEAT
```

The emphasis is on building reports from raw datasets rather than only modifying existing dashboards.

---

# 📚 Recommended Resources

### Official Microsoft Documentation

- [Power BI Documentation](https://learn.microsoft.com/en-us/power-bi/)
- [Power BI Data Transformation & Modeling](https://learn.microsoft.com/en-us/power-bi/transform-model/)
- [DAX Documentation](https://learn.microsoft.com/en-us/dax/)
- [Power Query M Documentation](https://learn.microsoft.com/en-us/powerquery-m/)
- [Microsoft Power BI Learning](https://learn.microsoft.com/en-us/training/powerplatform/power-bi/)
- [PL-300 Learning Resources](https://learn.microsoft.com/en-us/credentials/certifications/data-analyst-associate/)

Microsoft's official PL-300 learning material covers data acquisition, transformation, semantic models, DAX, report design, analytics, security, dashboards, and Power BI Service workflows.

### Recommended Books

- _The Definitive Guide to DAX_
- _Analyzing Data with Microsoft Power BI_
- _Microsoft Power BI Cookbook_

---

# 🏆 Target Certification

## Microsoft Certified: Power BI Data Analyst Associate

Target certification:

**PL-300 — Microsoft Power BI Data Analyst**

The certification aligns well with this roadmap because its learning objectives cover preparing data, modeling data, visualizing/analyzing data, and managing/securing Power BI assets.

---

# 🔬 Research & Academic Perspective

This repository treats Business Intelligence as more than dashboard creation.

The learning process focuses on:

### Data Engineering

```text
Data Sources
     ↓
Data Preparation
     ↓
Data Transformation
```

### Data Modeling

```text
Dimensions
     ↓
Relationships
     ↓
Semantic Model
```

### Analytical Computing

```text
DAX
 ↓
Measures
 ↓
Business Metrics
 ↓
Insights
```

### Decision Support

```text
Raw Data
   ↓
Information
   ↓
Analysis
   ↓
Insight
   ↓
Decision
   ↓
Action
```

The ultimate objective is to understand **how data becomes actionable business intelligence**.

---

# 📌 Key Principles

> ### 1. Model before you visualize.

A beautiful report built on a poor model will eventually become difficult to maintain.

> ### 2. Transform data before writing unnecessary DAX.

Use Power Query for data preparation whenever appropriate.

> ### 3. Prefer measures for analytical calculations.

Measures respond dynamically to report context.

> ### 4. Learn the concepts behind DAX.

Do not memorize formulas without understanding context.

> ### 5. Build projects.

Practical implementation is the primary measure of progress.

> ### 6. Optimize after correctness.

First make the model correct. Then make it fast.

---

# 📊 Final Skill Target

By the end of this repository, the goal is to progress through:

```text
                    ┌───────────────┐
                    │   BEGINNER    │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ INTERMEDIATE  │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │    ADVANCED   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ PROFESSIONAL  │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │   PORTFOLIO   │
                    │    READY      │
                    └───────────────┘
```

---

# 🚀 End Goal

The final objective is to become capable of taking a real business problem and independently delivering:

```text
Business Problem
       ↓
Data Sources
       ↓
Data Extraction
       ↓
Power Query
       ↓
Data Modeling
       ↓
DAX
       ↓
Analytics
       ↓
Dashboard
       ↓
Security
       ↓
Performance
       ↓
Power BI Service
       ↓
Business Decision
```

---

# 📌 Repository Status

| Area                     | Status         |
| ------------------------ | -------------- |
| Foundations              | 🟡 In Progress |
| Power BI Fundamentals    | 🟡 In Progress |
| Power Query              | ⬜ Planned     |
| Data Modeling            | ⬜ Planned     |
| DAX                      | ⬜ Planned     |
| Advanced DAX             | ⬜ Planned     |
| Dashboard Design         | ⬜ Planned     |
| RLS                      | ⬜ Planned     |
| Performance Optimization | ⬜ Planned     |
| Power BI Service         | ⬜ Planned     |
| Enterprise BI            | ⬜ Planned     |
| Portfolio Projects       | ⬜ Planned     |

---

# 👨‍💻 Author

**Satinder Singh Sall**

Learning and building in:

`Business Intelligence` · `Data Analytics` · `Power BI` · `DAX` · `SQL` · `Data Modeling`

---

# ⭐ Support

If this learning repository helps you, consider giving it a ⭐ on GitHub.

---

<p align="center">

### 📊 Turning Data Into Decisions

**Learn → Practice → Build → Analyze → Optimize**

</p>

<p align="center">
  <sub>Built as a continuous learning and professional development repository.</sub>
</p>

---

## 📜 License

This repository is licensed under the **MIT License**.

---

## 🔗 References

- Microsoft Power BI Documentation
- Microsoft Learn — Power BI
- Microsoft Learn — DAX
- Microsoft Learn — Power Query M
- Microsoft PL-300 Learning Resources
- Microsoft Power BI Community

---

If you want to go **from complete beginner → job-ready → advanced Power BI**, I’d recommend learning it in a structured way rather than just watching random tutorials.

## 🎯 Your Power BI Roadmap

Think of Power BI as 6 levels:

**Level 1 → Excel & Data Fundamentals**
**Level 2 → Power BI Basics**
**Level 3 → Power Query / Data Cleaning**
**Level 4 → Data Modeling + DAX**
**Level 5 → Advanced Power BI**
**Level 6 → Real-world Projects + Deployment**

---

### 🟢 Level 1 — Foundations

Before Power BI, understand:

- What is data analysis?
- Rows, columns, tables
- Primary keys / foreign keys
- Relational databases
- Basic Excel
- Basic SQL
- Data types
- Aggregations: `SUM`, `COUNT`, `AVERAGE`, etc.
- Basic statistics

**Excel topics worth knowing:**

- Tables
- Pivot Tables
- XLOOKUP
- IF / IFS
- SUMIFS / COUNTIFS
- Basic charts
- Data cleaning

You don't need to become an Excel expert before starting Power BI.

---

### 🔵 Level 2 — Power BI Fundamentals

Learn the Power BI ecosystem:

- Power BI Desktop
- Power BI Service
- Power BI Mobile
- Workspaces
- Reports
- Dashboards
- Semantic models
- Dataflows
- Apps

Then learn how to:

1. Import Excel/CSV data
2. Connect to databases
3. Create visuals
4. Create pages
5. Add slicers
6. Add filters
7. Format reports
8. Create drill-through pages
9. Use bookmarks
10. Publish reports

Your first project could be a **Sales Dashboard**.

---

### 🟡 Level 3 — Power Query

This is extremely important.

Learn **Power Query / M** for transforming raw data.

Topics:

- Remove columns
- Rename columns
- Change data types
- Remove duplicates
- Handle nulls
- Split columns
- Merge columns
- Replace values
- Filter rows
- Group By
- Merge Queries
- Append Queries
- Conditional columns
- Custom columns
- Pivot / Unpivot
- Parameters
- Query dependencies
- Basic M language

The mindset should become:

> **Raw Data → Power Query → Clean Data → Data Model**

---

### 🟠 Level 4 — Data Modeling + DAX

This is where you move from beginner toward professional Power BI.

#### Data Modeling

Learn:

- Fact tables
- Dimension tables
- Star schema ⭐
- Relationships
- Cardinality
- Cross-filter direction
- Date tables
- Role-playing dimensions
- Many-to-many relationships
- Slowly changing dimensions

For example:

```text
             Date
               |
Product — Sales — Customer
               |
             Store
```

Understanding **star schema** is one of the biggest differences between a beginner and a strong Power BI developer.

---

## 🔥 DAX

DAX is one of the most important parts of Power BI.

Start with:

```DAX
Total Sales =
SUM(Sales[SalesAmount])
```

Then learn:

### Basic functions

- SUM
- SUMX
- COUNT
- COUNTROWS
- DISTINCTCOUNT
- AVERAGE
- MIN / MAX

### Filter functions

- CALCULATE ⭐
- FILTER
- ALL
- ALLEXCEPT
- REMOVEFILTERS
- KEEPFILTERS

### Conditional logic

- IF
- SWITCH
- AND
- OR

### Variables

```DAX
VAR
RETURN
```

### Time intelligence

Learn:

- TOTALYTD
- TOTALMTD
- TOTALQTD
- DATEADD
- SAMEPERIODLASTYEAR
- DATESYTD
- PREVIOUSMONTH
- PREVIOUSYEAR

Then move into advanced concepts:

- Row context
- Filter context
- Context transition
- Iterators
- Virtual tables
- CALCULATETABLE
- VALUES
- SELECTEDVALUE
- TREATAS
- RANKX
- TOPN
- ISINSCOPE

**CALCULATE + filter context** should eventually become second nature.

---

# 🔴 Level 5 — Advanced Power BI

Once you're comfortable with DAX and modeling, learn:

### Advanced visuals

- Custom visuals
- Decomposition Tree
- Key Influencers
- Maps
- KPI cards
- Small multiples
- Tooltips
- Dynamic titles
- Dynamic measures

### Advanced interactions

- Bookmarks
- Buttons
- Drill-through
- Page navigation
- Report tooltips
- Field parameters
- What-if parameters

### Dynamic reporting

For example:

> User selects **Sales / Profit / Orders**

and the entire report dynamically changes.

---

## 🔐 Security

Learn:

### Row-Level Security (RLS)

For example:

```text
Admin → sees everything
Manager → sees their region
Employee → sees their own data
```

Learn:

- Static RLS
- Dynamic RLS
- USERNAME()
- USERPRINCIPALNAME()
- Security roles

---

## ⚡ Performance Optimization

This is an **advanced-level skill**.

Learn:

- Performance Analyzer
- DAX Studio
- VertiPaq Analyzer
- Reducing model size
- Star schema optimization
- Reducing unnecessary columns
- Optimizing DAX
- Storage engine vs formula engine
- Query folding
- Incremental refresh

Eventually you should be able to look at a slow report and ask:

> **Is the problem Power Query, the model, DAX, or the visual?**

---

# 🟣 Level 6 — Power BI Service

Don't stop at Power BI Desktop.

Learn how Power BI works in production:

- Workspaces
- Publishing
- Apps
- Semantic models
- Scheduled refresh
- Gateways
- Permissions
- RLS
- Deployment pipelines
- Endorsement
- Lineage
- Dataflows
- On-premises data gateway

Also understand:

**Development → Test → Production**

---

# 💼 Projects You Should Build

Don't just learn Power BI through tutorials.

Build projects.

I'd recommend these in order:

### Project 1 — Sales Dashboard

Learn:

- Power Query
- Basic visuals
- Slicers
- Basic DAX

### Project 2 — Finance Dashboard

Learn:

- P&L
- Revenue
- Expenses
- Profit margins
- Time intelligence

### Project 3 — HR Dashboard

Learn:

- Employee analytics
- Attrition
- Department analysis
- Dynamic filtering

### Project 4 — E-commerce Dashboard

Learn:

- Customers
- Products
- Orders
- Revenue
- Profit
- Customer segmentation

### Project 5 — Advanced Executive Dashboard

Build something with:

- Star schema
- Advanced DAX
- Dynamic measures
- Field parameters
- Drill-through
- Bookmarks
- Tooltips
- RLS
- Performance optimization

This final project can become a **portfolio project for your resume/GitHub/LinkedIn**.

---

# 📚 The Order I'd Personally Recommend

Don't learn everything simultaneously.

Follow this sequence:

```text
Excel Basics
     ↓
SQL Basics
     ↓
Power BI Desktop
     ↓
Power Query
     ↓
Data Modeling
     ↓
Basic DAX
     ↓
Advanced DAX
     ↓
Visualization
     ↓
Power BI Service
     ↓
RLS
     ↓
Performance Optimization
     ↓
Real-world Projects
     ↓
Portfolio / Job Preparation
```

### A realistic progression

| Stage        | Goal                                  |
| ------------ | ------------------------------------- |
| Beginner     | Create basic reports                  |
| Intermediate | Clean data + build models             |
| Advanced     | Write complex DAX                     |
| Professional | Build scalable BI solutions           |
| Job-ready    | Solve business problems independently |

---

## 🚀 How I can teach you

We can actually do this **as a structured Power BI course here**, rather than you having to figure out what to study next.

I can take you through:

**Lesson 1:** What Power BI actually is
↓
**Lesson 2:** Installing and understanding Power BI Desktop
↓
**Lesson 3:** Importing your first dataset
↓
**Lesson 4:** Power Query
↓
**Lesson 5:** Data modeling
↓
**Lesson 6:** Your first DAX measures
↓
**Lesson 7:** Advanced DAX
↓
**Lesson 8:** Advanced dashboards
↓
**Lesson 9:** Power BI Service
↓
**Lesson 10:** RLS & deployment
↓
**Lesson 11:** Performance optimization
↓
**Lesson 12+:** Real-world projects and interview preparation

---

- 📊 Professional header/banner
- 🏆 Badges
- 📚 Structured curriculum
- 🧭 Beginner → Advanced roadmap
- 🧠 Learning objectives
- 🛠️ Tools & technologies
- 📈 Power BI architecture section
- 🧮 DAX / Power Query sections
- 💼 Hands-on projects
- 📝 Exercises & assessments
- 🎯 Skills matrix
- 📊 Progress tracking
- 🔬 Research/academic-style references
- 📸 Visuals/diagrams
- 📂 Suggested repository structure
- 🚀 Portfolio section
- 📜 License
- 👤 Author section
