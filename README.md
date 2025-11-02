## Inventory Management Business Case

**Stack:** Python (Google Colab), SQL (PostgreSQL), Tableau Public  
**Goal:** Analyze inventory performance, build KPIs, and propose pricing & stock actions.

## Live Links
- **Colab Notebook:** (to be added)
- **Tableau Dashboard:**
- Inventory Performance Overview - https://public.tableau.com/authoring/Dashboard1_17619339694780/InventoryPerformanceOverview#3
- Unsold Inventory Risk Overview - https://public.tableau.com/authoring/UnsoldInventoryRiskOverview/UnsoldInventoryRiskOverview#8

## Repo Structure
- `data/raw/` – source CSV  
- `notebooks/` – Colab notebook  
- `sql/` – KPI SQL scripts  
- `outputs/` – exports for Tableau (car_level.csv, kpi_agg.csv)  
- `tableau/` – dashboard link & notes

## How to Reproduce
1. Open Colab and run the notebook (`notebooks/auto1_inventory_case.ipynb`).
2. Data loads from the GitHub Raw URL.
3. Exports are created in Colab and saved back to `outputs/`.

## KPIs
- Sell-through %, Avg/Median Days Online (sold), Avg Gross Margin €,
- Profit Margin %, Price Gap vs Market (€ and %), Aging distribution.

## Notes
- Unsold cars: `days_online` is computed up to “today”.
- Outliers handled by robust stats (medians) in the deck.

## 🧠 Key Insights

- Sell-through rate below 50% → aging stock risk
- Profitability strong but demand constrained
- Jeep & Jaguar overpriced → efficiency issues
- Opel, Mazda & Citroën → best supply scaling opportunities
- 54% of inventory is unsold → slow turnover & high risk 
- Cars remain listed 346+ days → severe aging issue 
- Pricing strategy is competitive → not a price barrier 
- Brands like Volkswagen, BMW, Opel drive most aging stock
- Demand-side actions needed → targeted promotions & faster clearance
