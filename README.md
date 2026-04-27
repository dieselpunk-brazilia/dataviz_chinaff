#China's Development Finance to Uzbekistan

An interactive data visualization project exploring the structure and trends of Chinese development finance flows to Uzbekistan over the past two decades, based on AidData's global dataset.

## Live Demo

**[View the interactive report](https://dieselpunk-brazilia.github.io/dataviz_chinaff/combined.html)**

---

## What's Inside

The report is a Jupyter Notebook exported to HTML with 5 interactive Plotly visualizations:

| # | Visualization | Key Insight |
|---|--------------|-------------|
| 1 | **Funding over time** | China's finance to Uzbekistan grew substantially across two decades |
| 2 | **Central Asia comparison** | Uzbekistan ranks **#2** among Central Asian recipient countries |
| 3 | **Flow type breakdown** | Loans dominate — grants and technical assistance are marginal |
| 4 | **Funding by sector** | Industry, Mining & Construction lead (27%), followed by Energy (18%) |
| 5 | **Project status** | 78.5% of all projects have reached completion |

---

## Tech Stack

- **Python** — data processing and analysis
- **Pandas** — data wrangling and aggregation
- **Plotly** — interactive charts (bar, treemap, line)
- **Jupyter Notebook** — analysis environment
- **nbconvert** — notebook-to-HTML export
- **GitHub Pages** — hosting

---

## Data Source

[AidData's Global Chinese Development Finance Dataset](https://www.aiddata.org/data/aiddatas-global-chinese-development-finance-dataset-version-3-0) — a comprehensive dataset tracking Chinese government-financed projects worldwide.

---

## Key Findings

- A few **exceptionally large loans** drive the overall funding trend
- **Industrial, mining, and construction** sectors receive the largest share of financing
- The **loan instrument dominates** — grants and technical assistance are overshadowed
- The majority of tracked projects have **already reached completion**
- Understanding these flows can help journalists investigate China's role in Uzbekistan's development

---

## Run Locally

```bash
git clone https://github.com/dieselpunk-brazilia/dataviz_chinaff.git
cd dataviz_chinaff
pip install pandas plotly jupyter nbconvert
jupyter notebook
```

Then open `AidData_Uzbekistan.ipynb` and run all cells.

---

## Author

**dieselpunk-brazilia** · [GitHub](https://github.com/dieselpunk-brazilia)
