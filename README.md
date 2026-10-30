# 📊 FinSight AI – AI-Powered Financial Intelligence Platform

**Turning fragmented financial information into actionable intelligence.**

## 🚀 About the Project

FinSight AI is an AI-powered financial research and stock analysis platform designed to help investors understand a company's current performance, historical events, opportunities, and risks.

Financial information is scattered across news websites, stock exchange announcements, company disclosures, and regulatory sources. Manually collecting and analysing this information can be time-consuming.

FinSight AI solves this problem using autonomous web research and a three-agent AI architecture to generate comprehensive, evidence-based financial intelligence reports.

## 🎯 Problem Statement

Investors often struggle to:
- Collect financial information from multiple sources.
- Identify important company-related news and announcements.
- Understand a company's historical controversies and regulatory actions.
- Verify conflicting financial reports.
- Connect past corporate events with current developments.

Traditional dashboards mainly display stock prices and charts, while generic AI summaries often lack historical context and traceable evidence.

## 💡 Our Solution

FinSight AI automates company-specific financial investigation using three specialized AI agents:

1. **News Agent** – Collects recent company news, earnings updates, NSE/BSE announcements, contracts, management changes, and regulatory events.
2. **History Agent** – Investigates historical controversies, business deals, and regulatory actions to build a company timeline.
3. **Analyst Agent** – Analyses the collected information, compares bullish and bearish factors, and generates an explainable financial signal.

## 🏗️ System Architecture

The project follows a three-agent architecture:

```text
             User Input
                 |
                 v
       Company Name / Symbol
                 |
          +------+------+
          |             |
          v             v
      News Agent   History Agent
          |             |
          v             v
     Recent News   Historical Events
          |             |
          +------+------+
                 |
                 v
           Analyst Agent
                 |
                 v
       Financial Intelligence
               Report
                 |
        +--------+--------+
        |        |        |
       BUY     HOLD     SELL
                 |
               WATCH
```

## 🐟 Role of TinyFish

TinyFish is the core technology powering autonomous web research in FinSight AI.

It helps the research agents:
- Navigate relevant financial websites.
- Collect information from multiple sources.
- Extract company-related news and announcements.
- Gather historical corporate information.
- Return structured findings with source URLs and dates.

This makes the research process more automated, transparent, and evidence-based.

## ✨ Key Features

- **Autonomous Financial Research:** Collects information from multiple online sources.
- **Company-Specific News Discovery:** Identifies important company developments.
- **Historical Context Analysis:** Investigates past controversies, deals, and regulatory actions.
- **Bullish vs Bearish Analysis:** Compares positive opportunities against potential risks.
- **Explainable Signals:** Generates Buy, Hold, Sell, or Watch signals with supporting evidence.
- **Source Verification:** Provides source URLs and dates for findings.
- **Risk Identification:** Highlights conflicting reports, uncertainties, and evidence limitations.

## 📄 Expected Output

For every investigated company, FinSight AI generates a consolidated report containing:

- Company name and stock symbol.
- Recent developments with source links.
- Significant historical events and outcomes.
- Bullish factors and opportunities.
- Bearish factors and risks.
- Explainable Buy / Hold / Sell / Watch signal.
- Supporting evidence and counterarguments.
- Uncertainties, source limitations, and time horizon.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| TinyFish | Autonomous web research |
| LLM API | AI-based financial analysis |
| Python | Backend development |
| FastAPI | Backend API framework |
| React | Frontend development |
| Tailwind CSS | User interface styling |
| SQLite / PostgreSQL | Database management |

## 👥 Target Users

- Retail Investors
- Financial Analysts
- Stock Market Researchers
- Brokers and Traders

## 🌟 What Makes FinSight AI Unique?

Unlike traditional stock market dashboards that mainly display prices, charts, and indicators, FinSight AI investigates both a company's past and present.

It connects historical corporate events with current developments to provide a more complete understanding of investment opportunities and risks.

Its focus is not just on summarizing information but on providing traceable evidence and explainable financial intelligence.

## 🔮 Future Scope

Planned future enhancements include:

- Automated watchlist monitoring and alerts.
- Mapping relationships between companies, suppliers, customers, and sectors.
- Integration with live market prices and financial statements.
- Historical evaluation of generated signals.
- Paper trading functionality.
- Wider coverage of Indian listed companies.

## ⚠️ Responsible Use

FinSight AI provides analytical assessments for research and educational purposes. Its Buy / Hold / Sell / Watch signals are not guaranteed predictions or personalized financial advice.

Final investment decisions must remain with the user. The platform does not perform automated trading.

🎯 Project Goal

Our goal is to transform fragmented financial information into meaningful, transparent, and actionable intelligence through autonomous web research and AI-powered analysis.

