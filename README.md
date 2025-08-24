# COVID-19 Global Data Tracker

A beginner-friendly data analysis notebook that tracks global COVID-19 trends using the **Our World in Data** dataset. 
The project loads, cleans, analyzes, and visualizes cases, deaths, and vaccinations across countries and time.

## 🎯 Objectives
- Import and clean COVID-19 global data (OWID).
- Analyze time trends (cases, deaths, vaccinations).
- Compare metrics across countries/regions.
- Visualize trends with line charts, bar charts, histograms, scatter plots, and an optional choropleth map.
- Communicate findings via clear narrative insights in the notebook.

## 🧰 Tools & Libraries
- Python 3.9+
- Jupyter Notebook (Anaconda, VS Code Jupyter, Google Colab, or similar)
- pandas
- matplotlib
- seaborn
- plotly (optional, for the choropleth map)

## 📁 Repository Structure (example)
```
.
├── data/
│   └── owid-covid-data.csv              # (Optional) Small/sample CSV. Prefer linking to the source for large files.
├── notebook/
│   └── covid_tracker.ipynb              # Main analysis notebook (runs end-to-end)
├── README.md
├── requirements.txt
└── LICENSE
```

> ⚠️ **Note on data files:** The OWID CSV is large and frequently updated. 
> To keep the repo small, you can **link to the official source** instead of committing the full CSV, or include a **small filtered sample** in `data/`.

**OWID dataset source:** https://covid.ourworldindata.org/data/owid-covid-data.csv

## 🚀 How to Run / View
### Option A: Open in Google Colab (no install)
1. Upload `covid_tracker.ipynb` and (optionally) a small CSV sample to Colab.
2. In the first cell, install any missing libraries (if needed):
   ```python
   !pip install pandas matplotlib seaborn plotly
   ```
3. Run the notebook **top to bottom**: `Runtime → Restart and run all`.

### Option B: Run locally (Anaconda / VS Code)
1. Create and activate an environment (optional but recommended).
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook
   ```
4. Run all cells: `Kernel → Restart & Run All`.

## ✍️ Insights (example – replace with your observations)
- The United States recorded the highest total COVID-19 cases compared to Kenya and India.
- India showed a sharp spike in cases during mid‑2021, reflecting the second wave.
- Kenya maintained relatively lower case numbers throughout the period.
- Death trends show the United States with the highest totals; India had notable peaks; Kenya remained comparatively lower.
- Vaccination rollout progressed fastest in the United States, followed by India, while Kenya started later and moved more slowly.

> Add your own insights right under each plot in the notebook using **Markdown cells**.

## ✅ Submission Checklist
- [ ] Notebook runs **start to finish** without errors (use Restart & Run All).
- [ ] All plots render correctly (line, bar, histogram, scatter; optional map).
- [ ] Insights are written beneath each visualization.
- [ ] `README.md` filled with project description and how‑to‑run instructions.
- [ ] Repository is public and link is ready to share.

## 📜 License
MIT — see `LICENSE`.
