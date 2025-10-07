# Global Tech Layoffs — SQL EDA

Exploratory analysis of layoffs across companies, locations, industries, and time.

## 🔍 Key questions answered
- Which companies had the **largest single-event** layoffs?
- Which companies had the **most total** layoffs?
- Which **locations/countries** were impacted the most?
- How did layoffs evolve **over time**? (monthly + rolling totals)
- Which **industries/stages** were most affected?

## 🧪 Methods
- Aggregations by company, location, country, industry
- Yearly rankings with `DENSE_RANK()`
- Monthly series with a **rolling total**

See queries in `sql/world_layoff_eda.sql`.

## ▶️ How to run
Run after the cleaning step; point queries at `world_layoff.layoffs_staging2`.

## 📁 Files
- `sql/world_layoff_eda.sql`
