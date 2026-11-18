<h1 align="center">Aryan Dhawan</h1>

<p align="center">
  <b>Data & Business Analyst · Analytics & AI Engineering · MSc Business Analytics, University of Manchester · Founder of Known</b>
</p>

<p align="center">
  I find the "why" behind the numbers and turn it into clear decisions, reliable data and products people actually use.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aryan-dhawan7">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white" />
  </a>
  <a href="https://aryan-dhawan7-portfolio.lovable.app/">
    <img src="https://img.shields.io/badge/Portfolio-View-orange" />
  </a>
  <a href="https://known-nine.vercel.app">
    <img src="https://img.shields.io/badge/Known-Live_Product-1a1a1a" />
  </a>
  <a href="mailto:aryandhawan210@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?logo=gmail&logoColor=white" />
  </a>
</p>

---

## How I work

- **Root cause first.** I don't stop at the dashboard. I find what's causing the problem, from frontline NHS interviews to lending data and e-commerce reviews, and recommend the fix.
- **Data people can trust.** Tested pipelines, reconciled numbers and clear definitions, so every figure can be traced back to where it came from.
- **Clear with stakeholders.** I've presented findings to an NHS Associate Director of Pharmacy, a startup founder and consulting clients, in plain English.

---

## Latest: Olist E-commerce Analytics (Snowflake + dbt)

**Repo:** [olist-ecommerce-analytics](https://github.com/aryannn7/olist-ecommerce-analytics)

**Question:** where is an online marketplace losing customers it could keep?

An end-to-end ELT pipeline on 100k+ real Brazilian e-commerce orders: raw CSVs loaded into **Snowflake**, cleaned and modelled in **dbt** (raw → staging → star schema), with **43 automated data tests** proving every key. I then turned it into a client-style recommendation.

- **Finding:** late orders averaged 1.7★ against 4.3★ for on-time orders, and only 3% of customers ever bought again.
- **Recommendation:** a controlled win-back test for customers whose orders arrived late, measured against a holdout group.
- **Next step:** using an LLM to classify Portuguese review comments into complaint themes, so the business sees *why* customers are unhappy, not just the score.

**Stack:** Snowflake · dbt · SQL · Git (feature branches + pull requests) · key-pair auth

Snowflake and dbt were new to me when I started. I learned both by building this in a week.

---

## Flagship: Known: Live Personality Analytics Platform

**Live product:** [known-nine.vercel.app](https://known-nine.vercel.app)

A free, scientifically grounded Big Five personality assessment, built and shipped solo in under two weeks. Live in production with real users completing assessments and results persisted per user.

**What it does**

Users complete a 50 item validated assessment (IPIP-50), receive trait scores across the five-factor model with honest, facet-aware interpretations, and can save results ahead of the upcoming AI companion layer.

**What I built**

Full-stack product end to end: landing page with conversion-focused copy, multi step assessment flow with progress state, scoring engine implementing standard reverse-scoring methodology, dynamic trait interpretation engine, email capture with results persistence, a three-theme design system persisted via localStorage, and an SEO layer with Open Graph metadata and sitemap generation.

**Stack:** Next.js · TypeScript · React · Tailwind CSS · Supabase (PostgreSQL, Row Level Security) · Vercel

**Why it matters**

This is not a tutorial project. It has real users, real data, and improvements shipped directly from live user feedback and behaviour, with a roadmap toward an AI reflection companion anchored on each user's trait profile. The repository is private as this is an active commercial product.

---

## Experience

**Operations Analyst (MSc dissertation)** at Lancashire Teaching Hospitals NHS Foundation Trust: mapped the inpatient pharmacy workflow through interviews with pharmacists and technicians, built a Python simulation to test staffing options, and presented recommendations to the Associate Director of Pharmacy for the Trust's staffing review.

**AI Product Engineering** at StrataGease (London): cloud-native architecture on AWS for two production SaaS products, RAG pipelines with LangChain, agentic workflows, a weekly performance dashboard for the founder, and analytics tooling that cut manual operations by 50%.

**Business Strategy & Data Analyst Consultant** at DBIM Limited (Manchester): quantitative market analysis of the UK QHSE compliance sector, with insight reports presented to the client's decision-makers.

**2+ years engineering financial data systems at scale** at Bajaj Finserv: 12+ production pipelines serving millions of records, 99%+ reliability across CI/CD cycles, and reconciliation automation in Python, Scala and SQL that reduced data discrepancies by 85%.

---

## Selected Projects

### Is the Bee Network Working? (in progress)
**Repo:** [bee-network-punctuality](https://github.com/aryannn7/bee-network-punctuality)

An independent analysis of whether bringing Greater Manchester's buses under public control made them more reliable, separating the effect of franchising from seasonality, roadworks and weather. SQL, Python, causal inference.

### JobSnapAI: AI Career Intelligence
**Repo:** [jobSnapAI-career-intelligence](https://github.com/aryannn7/jobsnapai)

Ingests resumes, extracts structured skills using GPT-4 structured outputs, maps them against job requirements and returns prioritised recommendations. Python, LangChain, Streamlit, prompt-engineered rule routing with reproducible JSON outputs.

### FinSight: Fraud Detection Dashboard
**Repo:** [FinSight-Fraud-Analytics](https://github.com/aryannn7/finsight_financial_dashboard)

Real-time anomaly detection on 28,000+ credit card transactions using Isolation Forest, with an interactive analyst dashboard for live flagging and investigation. Python, Scikit-learn, Pandas, Streamlit.

### Ericsson Patent Forecasting: ML Pipeline
**Repo:** [ericsson-patent-forecasting](https://github.com/aryannn7/ericsoon-patent-forecasting)

Forecast annual patent filings across 50 years of data, achieving 10.9% mean error. Chronological train-test splits, leakage prevention, and model selection favouring genuine out-of-sample generalisation (Random Forest over XGBoost). Python, Scikit-learn.

---

## Skills

**Analysis & BI:** SQL · Excel · Power BI · root cause analysis · process mapping · requirements gathering · data storytelling · stakeholder reporting

**Analytics Engineering:** Snowflake · dbt · data modelling (3NF, star schema) · data testing · Git workflows

**Languages:** Python · SQL · TypeScript · Scala · R

**AI/ML:** LangChain · RAG pipelines · GPT-4 & Claude APIs · prompt engineering · Scikit-learn · XGBoost · anomaly detection · forecasting

**Data & Cloud:** AWS · Azure · Databricks · Azure Data Factory · PostgreSQL · Supabase · Cosmos DB · Apache Spark · ETL · CI/CD

**Product:** Next.js · React · Tailwind · Vercel · Streamlit

---

## Always learning

- **Picking up new tools by building with them.** Most recently Snowflake and dbt, from first login to a tested pipeline and a client-style recommendation in a week.
- **Getting better at explaining.** I practise presenting technical work as business decisions: slide decks, client memos and live walkthroughs.
- **Learning in public.** I keep a learning log in my project repos, so you can see how I got from "new to this" to "can explain every line".

---

## What I'm Looking For

Full-time roles in **Data Analysis**, **Business Analysis**, **Analytics Engineering** or **AI Engineering**, based in Manchester or the wider UK (on-site or hybrid).
I'm strongest where data meets decisions: finding the real problem, building data people can trust, and explaining it clearly.

**UK Graduate visa · no sponsorship needed**

---
GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aryannn7&show_icons=true&theme=default&hide_border=true&rank_icon=github" />
</p>

<p align="center">
  <a href="https://github.com/aryannn7"><img src="https://github-readme-streak-stats.herokuapp.com/?user=aryannn7&hide_border=true" alt="GitHub Streak" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aryannn7&layout=compact&hide_border=true" />
</p>

---

## Contact

**Email:** [aryandhawan210@gmail.com](mailto:aryandhawan210@gmail.com) · **LinkedIn:** [aryan-dhawan7](https://www.linkedin.com/in/aryan-dhawan7/) · **Portfolio:** [aryan-dhawan7-portfolio.lovable.app](https://aryan-dhawan7-portfolio.lovable.app/) · **Live product:** [known-nine.vercel.app](https://known-nine.vercel.app)
