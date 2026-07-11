# 📊 Google Workspace Analytics

<p align="center">
  A data analysis project exploring <b>Google Workspace</b> — product adoption, pricing,
  competitive market share, and growth trends — built from public 2026 statistics.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-2.x-150458?logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/matplotlib-visualization-11557C?logo=plotly&logoColor=white" alt="matplotlib">
  <img src="https://img.shields.io/badge/seaborn-charts-4C72B0" alt="seaborn">
  <img src="https://img.shields.io/badge/license-Educational-green" alt="license">
  <img src="https://img.shields.io/badge/status-active-brightgreen" alt="status">
</p>

<p align="center">
  <a href="#-project-overview">Overview</a> •
  <a href="#-repository-structure">Structure</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-visualizations">Visualizations</a> •
  <a href="#-key-findings">Key Findings</a> •
  <a href="#-data-sources">Data Sources</a>
</p>

---

Part of a broader analytics project series covering **Google, Facebook, Twitter, Railways,
Airport, and AI tools**.

**Author:** Harsh Sharma

## 📌 Project Overview

This project analyzes:

| Area | What it covers |
|---|---|
| 👥 **Product usage** | Monthly Active Users (MAU) across Gmail, Drive, Docs, Sheets, Slides, Meet, Chat, and Gemini |
| 💰 **Pricing** | Business Starter / Standard / Plus / Enterprise tiers |
| 🏆 **Market share** | Google Workspace vs Microsoft 365 vs other productivity suites |
| 📈 **Growth trends** | Workspace paying customers and Google Cloud revenue over recent quarters |
| 🏢 **Company overview** | Alphabet/Google revenue, net income, and Cloud segment performance |

## 🗂️ Repository Structure

```
google-workspace-analytics/
├── data/                      # Raw datasets (CSV)
│   ├── workspace_usage.csv
│   ├── pricing_plans.csv
│   ├── market_share.csv
│   ├── growth_trends.csv
│   └── company_overview.csv
├── scripts/
│   └── visualize.py           # Generates all charts from the CSVs
├── visuals/                   # Generated chart images (PNG)
│   ├── workspace_mau_bar.png
│   ├── pricing_comparison.png
│   ├── market_share_pie.png
│   ├── growth_trends.png
│   └── dashboard.png
├── notebooks/
│   └── analysis.ipynb         # Exploratory analysis notebook
├── requirements.txt
├── .gitignore
└── README.md
```

## 🚀 Getting Started

**1. Clone the repo and install dependencies**
```bash
git clone https://github.com/HarshSharma9789/google-workspace-analytics.git
cd google-workspace-analytics
pip install -r requirements.txt
```

**2. Generate visualizations**
```bash
python scripts/visualize.py
```
Charts are written to the `visuals/` folder.

**3. (Optional) Explore interactively**
```bash
jupyter notebook notebooks/analysis.ipynb
```

## 📈 Visualizations

<table>
  <tr>
    <td width="50%">
      <b>Workspace Product Usage</b><br>
      <img src="visuals/workspace_mau_bar.png" alt="Workspace MAU bar chart" width="100%">
    </td>
    <td width="50%">
      <b>Market Share</b><br>
      <img src="visuals/market_share_pie.png" alt="Market share pie chart" width="100%">
    </td>
  </tr>
  <tr>
    <td width="50%">
      <b>Pricing Comparison</b><br>
      <img src="visuals/pricing_comparison.png" alt="Pricing comparison bar chart" width="100%">
    </td>
    <td width="50%">
      <b>Growth Trends</b><br>
      <img src="visuals/growth_trends.png" alt="Growth trends chart" width="100%">
    </td>
  </tr>
</table>

<p align="center">
  <b>Combined Dashboard</b><br>
  <img src="visuals/dashboard.png" alt="Full dashboard" width="85%">
</p>

> Images render automatically once this repo is on GitHub — no extra setup needed, as long as the `visuals/` folder is pushed alongside this README.

## 🔑 Key Findings

- Google Workspace serves **3B+ monthly users** with **11M+ paying customers**, up from 8M in early 2025
- Gmail leads all products at **1.5B+ MAU**; Gemini AI crossed **750M MAU** after being bundled free into paid plans
- Google Workspace holds an estimated **~50% share** of the productivity software market, narrowly ahead of Microsoft 365
- Google Cloud revenue crossed **$20B in a single quarter for the first time** in Q1 2026, growing 63% YoY

## 🛠️ Tech Stack

- **Python 3** — core language
- **pandas** — data handling and transformation
- **matplotlib / seaborn** — chart generation
- **Jupyter** — exploratory notebook

## 🧾 Data Sources

Figures are compiled from public 2026 disclosures and third-party statistics aggregators:
- Alphabet quarterly earnings releases (Q4 2025, Q1 2026)
- Google Workspace official pricing page (workspace.google.com/pricing)
- SQ Magazine, AboutChromebooks, Bayelsa Watch — 2026 Workspace usage statistics
- Vendr & PricePulse — 2026 pricing benchmarks

> ⚠️ **Note:** Market share and MAU figures vary across sources depending on methodology.
> Numbers here should be treated as directional estimates rather than precise figures —
> see the notes column in each CSV for caveats.

## 📄 License

This project is for educational/portfolio purposes. Data is aggregated from publicly
available sources cited above.

---

<p align="center">Built by <b>Harsh Sharma</b> — part of an ongoing analytics project series.</p>
