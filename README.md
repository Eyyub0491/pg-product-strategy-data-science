# P&G Product Strategy: Data Science Case Study

This project was created as part of a business case challenge simulating the role of a Data Scientist at Procter & Gamble. It explores how data can inform strategic decisions, particularly around sustainability, energy pricing, and market resilience.

## 🎯 Objective

Use data science to explore the relationship between:
- P&G stock price and the COVID-19 pandemic
- Consumer behavior and P&G's ESG (Environmental, Social, Governance) efforts
- The limitations of current ESG data granularity

## 🔍 Key Hypotheses

1. **COVID vs Stock Price**: No strong correlation exists between COVID-19 cases and P&G stock price.
2. **ESG & Consumer Behavior**: ESG strategies do not reduce customer satisfaction.
3. **ESG Data Gaps**: Existing data is not granular enough to support regional or product-level targeting.

## 📊 Datasets

- Crude oil, gasoline, and natural gas prices
- Global CO₂, water, and plastic metrics
- COVID-19 U.S. case data
- P&G product details (scraped)
- P&G stock prices (2015–2025)

## 📁 Repository Structure

- data/ - Raw and cleaned data files
- notebooks/ - Jupyter notebook for full analysis
- src/ - Python scripts (modular functions)
- reports/ - Business presentation and PDF report

## 📌 Tools & Technologies

- Python (pandas, seaborn, matplotlib, scipy)
- Jupyter Notebooks
- Selenium, BeautifulSoup (for web scraping)
- Git/GitHub for version control

## 📈 Key Insights

- P&G stock stayed resilient during COVID due to product mix & trust.
- ESG progress had neutral or positive consumer impact.
- More localized ESG data is needed for better strategic alignment.

## 📑 Reports

- [📘 Final Report](reports/Understanding_Business_Report.pdf)
- [📊 Presentation Slides](reports/P&G%20final.pptx)

---

## 🚀 Getting Started

Clone the repo and install the dependencies:

```bash
git clone https://github.com/yourusername/pg-product-strategy-data-science.git
cd pg-product-strategy-data-science
pip install -r requirements.txt
