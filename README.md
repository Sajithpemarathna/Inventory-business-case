## Inventory Management Business Case

**Stack:** Python (Google Colab), SQL (DuckDB), Tableau Public  
**Goal:** Analyze inventory performance, build KPIs, and propose pricing & stock actions.

## Live Links
- **Colab Notebook:** (to be added)
- **Tableau Dashboard:** (to be added)

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
