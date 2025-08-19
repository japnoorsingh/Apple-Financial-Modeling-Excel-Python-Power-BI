# Apple Financial Modeling — Excel + Python + Power BI

Compact project showcasing a 3-statement model (Excel) and a BI dashboard, built from Kaggle historicals.

## Files
- **data/raw/** `Raw Data.xlsx` — source historicals (2016–2019)
- **excel/** `Financial Modelling.xlsx` — 3-statement model & projections (2020–2024)  
- **excel/** `Apple.cxlsx` — assumptions / scenarios
- **python/** `apple_model.ipynb` — light prep/calcs for BI (optional)
- **powerbi/** `APPLE PROJECTIONS.pbix` — interactive dashboard

> Tip: Track `.pbix` with Git LFS if the repo is public.

## How to Use
**Excel**
1) Open `Financial Modelling.xlsx`.  
2) Adjust drivers in `Apple.cxlsx` (growth, margins, WC, CapEx, tax).  
3) Confirm IS/BS/CF balance and review Base/Bull/Bear.

**Python (optional)**
1) Open `apple_model.ipynb`.  
2) Run all cells → export a clean table for BI if needed.

**Power BI**
1) Open `APPLE PROJECTIONS.pbix`.  
2) Fix data source paths to this repo, then **Refresh**.  
3) Pages: Executive Summary, 3-Statement, Actuals vs Projections, KPI Deep-Dive.  
4) For cards/charts: set **Display units = Billions** (where applicable).

## KPIs & Checks
Revenue, Net Income, Gross/Op Margin %, FCF, ROIC; BS balances and CF ties to change in cash; YoY variance visuals.

## CV Summary (use 2–3 bullets)
- Built a driver-based **3-statement model** (FY20–FY24) from FY16–FY19 historicals.  
- Developed a **Power BI dashboard** to visualize KPIs and scenario impacts.  
- Standardized inputs with a **Python notebook** feeding the BI layer.

*Educational project. Not investment advice.*
