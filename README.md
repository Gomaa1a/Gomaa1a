<div align="center">
<img src="https://raw.githubusercontent.com/Gomaa1a/Gomaa1a/main/hero.svg" alt="Ahmed Gomaa — Full-stack engineer: AI products, data systems, automation" width="100%" />
</div>

<br/>

I build AI products end to end — TypeScript and React on the surface, Python data engines and Supabase behind them — and the automation that keeps them fed.

Roughly three quarters of my work is application code: AI platforms, voice interfaces, internal tools. The rest is the data layer those products depend on. Based in Egypt. Most of my day-to-day work lives in private client repositories, so what is public here is a representative slice rather than the whole picture.

<br/>

<div align="center">

<img src="https://img.shields.io/badge/TypeScript-21262d?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
<img src="https://img.shields.io/badge/React-21262d?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Node.js-21262d?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
<img src="https://img.shields.io/badge/Python-21262d?style=flat-square&logo=python&logoColor=4B8BBE" alt="Python" />
<img src="https://img.shields.io/badge/PostgreSQL-21262d?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Supabase-21262d?style=flat-square&logo=supabase&logoColor=3FCF8E" alt="Supabase" />
<img src="https://img.shields.io/badge/OpenAI-21262d?style=flat-square&logo=openai&logoColor=A5B4FC" alt="OpenAI" />
<img src="https://img.shields.io/badge/n8n-21262d?style=flat-square&logo=n8n&logoColor=EA4B71" alt="n8n" />
<img src="https://img.shields.io/badge/Vercel-21262d?style=flat-square&logo=vercel&logoColor=FFFFFF" alt="Vercel" />

</div>

---

## What I work on

<details>
<summary><b>AI products</b> — voice interfaces, conversational apps, LLM-backed tooling</summary>

<br/>

The largest share of my work. Full-stack TypeScript applications with language models and speech at the core: live AI interview practice that adapts its questions to a candidate's CV and returns a scored report, voice conversation interfaces, resume scoring, and a B2B AI platform.

Typically React and Vite on the front, Supabase for auth, storage and Edge Functions, with OpenAI and ElevenLabs behind them. The engineering problem is rarely the model call — it is state, latency, cost, and giving the user something trustworthy when the model is wrong.

</details>

<details>
<summary><b>Data systems &amp; analytics</b> — query engines and dashboards for operators</summary>

<br/>

A read-only HTTP query engine over an Odoo ERP database. Dashboards send a structured request — *total sales per salesperson last month* — and the engine composes it with SQLAlchemy against a copy of the database, never accepting SQL from the caller. Every connection opens with `default_transaction_read_only = on`, so PostgreSQL itself refuses a write.

On top of it sit dashboards built for the person making the decision rather than for an analyst: frozen capital split into truly dead versus seasonally dormant stock, margin leakage, what to buy and what to liquidate, salesperson performance, seasonality.

</details>

<details>
<summary><b>Internal tools &amp; automation</b> — the unglamorous layer that makes the rest work</summary>

<br/>

Spreadsheet importers that let anyone map arbitrary column layouts onto CRM fields and show which rows will actually store before anything is sent. Validators, webhook tooling, and n8n pipelines connecting CRMs, sheets, and internal services.

This work replaces one-off hardcoded migrations with something a non-engineer can run twice.

</details>

---

## How the pieces fit

```mermaid
flowchart LR
    U["Users"] --> APP["React / TypeScript<br/>applications"]
    APP --> SB[("Supabase<br/>auth · data · edge")]
    APP --> AI["LLM &amp; speech<br/>services"]
    SB --> ENG["Read-only<br/>query engine"]
    ERP["Odoo ERP"] -.->|"copy, never live"| ENG
    SHEETS["Spreadsheets<br/>&amp; CRMs"] -->|n8n| SB
    ENG --> DASH["Operator<br/>dashboards"]
```

---

## Selected public work

<table>
<tr>
<td width="50%" valign="top">

**[HireReady](https://github.com/Gomaa1a/HireReady)**

An AI voice interview coach. Runs a live interview tailored to the candidate's CV, then returns an honest, scored performance report so each session is measurably better than the last.

<sub>React · Supabase · OpenAI · ElevenLabs</sub>

</td>
<td width="50%" valign="top">

**[Frozen Capital Dashboard](https://github.com/Gomaa1a/dabboos-frozen-capital)**

Splits a distributor's stuck inventory into truly dead and seasonally dormant capital. Aging buckets, a live idle-threshold slider, and a seasonality heatmap answering what to clear and when. Bilingual Arabic and English.

<sub>JavaScript · Chart.js</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Law Firm SaaS](https://github.com/Gomaa1a/LawFirm-SAAS-Model)**

A demo SaaS model built for law firms.

<sub>TypeScript · React</sub>

</td>
<td width="50%" valign="top">

**[Retail Analytics Dashboard](https://github.com/Gomaa1a/E-commerce-Use-case-Data-Analytics-Dashboard-)**

A year of beverage retail sales analysed from raw Excel — net profit, growth trends, best and worst products, salesperson performance.

<sub>Python · pandas · Chart.js</sub>

</td>
</tr>
</table>

---

<div align="center">

**[ahmed.gomaa.adnan@gmail.com](mailto:ahmed.gomaa.adnan@gmail.com)**

<sub>Open to roles and projects in applied AI, full-stack product engineering, and data.</sub>

</div>
