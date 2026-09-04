<div align="center">

<img src="https://raw.githubusercontent.com/Gomaa1a/Gomaa1a/main/hero.svg" alt="Ahmed Gomaa — Data & AI Engineer" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Segoe+UI&weight=600&size=21&pause=1200&color=38BDF8&center=true&vCenter=true&width=720&height=45&lines=Dashboards+for+operators%2C+not+analysts.;Read-only+pipelines+that+never+touch+live+ERP.;AI+voice+products+that+actually+ship.;Automation+so+nobody+re-types+a+spreadsheet." alt="What I build" />

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

I turn messy ERP exports and spreadsheets into dashboards people actually make decisions with — and build AI products around them.

Based in Egypt. Most of my day-to-day work lives in private client repositories, so what's public here is a representative slice rather than the whole picture.

---

### How the work usually flows

```mermaid
flowchart LR
    A["🗄️ Odoo ERP"] -->|read-only sync| B[("⚡ Supabase")]
    B --> C["🔎 Query engine"]
    C --> D["📈 Sales command center"]
    C --> E["🧊 Frozen capital"]
    C --> F["📦 Product analytics"]
    G["📄 Spreadsheets"] -->|n8n| B

    style A fill:#1e3a5f,stroke:#38bdf8,color:#e2e8f0
    style B fill:#14532d,stroke:#34d399,color:#e2e8f0
    style C fill:#3b1e5f,stroke:#a78bfa,color:#e2e8f0
    style G fill:#4a2a0f,stroke:#fbbf24,color:#e2e8f0
```

Production ERP stays untouched. Everything downstream reads from a copy.

---

### What I do &nbsp;<sub><i>click to open</i></sub>

<details>
<summary><b>🗄️ &nbsp;ERP &amp; data pipelines</b></summary>

<br/>

Read-only query engines over Odoo databases, synced into Supabase, so reporting and dashboards never touch a live ERP. The engine speaks Odoo-shaped queries, so dashboards ask questions in the language the business already uses.

</details>

<details>
<summary><b>📊 &nbsp;Analytics dashboards for operators</b></summary>

<br/>

Built for the person making the call, not for analysts. Frozen capital split into *truly dead* vs *seasonally dormant* stock, aging buckets, per-brand and per-category breakdowns, salesperson performance, and seasonality heatmaps that answer one question: **what do I clear, and when?**

</details>

<details>
<summary><b>🎙️ &nbsp;AI voice &amp; conversational products</b></summary>

<br/>

Live AI interview practice with CV-aware questions, text-to-speech, and scored feedback reports — so every session is measurably better than the last. Built on OpenAI and ElevenLabs, shipped on Supabase Edge Functions.

</details>

<details>
<summary><b>🔗 &nbsp;Workflow automation</b></summary>

<br/>

n8n pipelines connecting CRMs, spreadsheets, and internal tools — column mapping, validation before storage, and no manual re-entry.

</details>

---

### Selected public work

<table>
<tr>
<td width="50%" valign="top">

#### 🧊 [Frozen Capital Dashboard](https://github.com/Gomaa1a/dabboos-frozen-capital)

Splits a distributor's stuck inventory into **truly dead** and **seasonally dormant** capital. Aging buckets, a live idle-threshold slider, and a monthly heatmap flagging what to clear now.

`Bilingual AR/EN` `JavaScript`

</td>
<td width="50%" valign="top">

#### 📈 [Retail Analytics Dashboard](https://github.com/Gomaa1a/E-commerce-Use-case-Data-Analytics-Dashboard-)

A full year of beverage retail sales analysed from raw Excel — net profit, growth trends, best and worst products, salesperson performance.

`Python` `pandas` `Chart.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎙️ [HireReady](https://github.com/Gomaa1a/HireReady)

An AI voice interview coach. Runs a live interview tailored to your CV, then returns an honest, scored performance report.

`React` `Supabase` `OpenAI` `ElevenLabs`

</td>
<td width="50%" valign="top">

#### ⚖️ [Law Firm SaaS](https://github.com/Gomaa1a/LawFirm-SAAS-Model)

A demo SaaS model built for law firms.

`TypeScript` `React`

</td>
</tr>
</table>

---

<div align="center">

### Get in touch

**[ahmed.gomaa.adnan@gmail.com](mailto:ahmed.gomaa.adnan@gmail.com)**

<sub>Open to roles and projects in data engineering, analytics, and applied AI.</sub>

</div>
