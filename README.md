# Data-Analytics-MiniProject
Data analysis project exploring football transfer market trends, player valuations, and spending patterns

# Football Transfer Market Data Analysis

![Python]
![Pandas]
![Statsmodels]

##  Project Overview
This data analysis project explores global football transfer market trends, player valuations, and club spending patterns. By analyzing historical transfer logs, the project uncovers key insights into market inflation, positional value premiums, and financial dominance across different football leagues.

## Key Insights & Findings
During the Exploratory Data Analysis (EDA), several notable trends were uncovered:
* **League Dominance:** [e.g., The English Premier League accounts for the highest share of total global transfer expenditures, outspending rival leagues by X%].
* **Positional Premium:** [e.g., Forwards and attacking midfielders command a significantly higher average transfer fee compared to defensive positions].
* **Age vs Value:** [e.g., Peak player valuations are heavily concentrated between the ages of 23 and 27, followed by a sharp statistical decline after age 30].
* **Statistical Modeling:** Using `statsmodels`, a linear regression model demonstrated that [e.g., player age and goals scored are statistically significant predictors of transfer fees].

## Tech Stack & Libraries Used
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Statistical Modeling:** `statsmodels`, `scipy`
* **Data Visualization:** `matplotlib`, `seaborn`

## Repository Structure
```text
├── Football_Transfer_Dataset.csv                  # Raw transfer market data
├── Football_Transfer_Market_Analysis.ipynb        # Jupyter notebook with full analysis & code
├── requirements.txt                               # List of required Python dependencies
└── README.md                                      # Project documentation and summary
```

## Getting Started

### Prerequisites
Ensure you have Python installed. You can install all required libraries at once using the provided requirements file:

```bash
pip install -r requirements.txt
```

### Running the Project
1. Clone this repository or download the files.
2. Open the notebook file `Football_Transfer_Market_Analysis.ipynb` using Google Colab or Jupyter Lab.
3. Place `Football_Transfer_Dataset.csv` in the same directory and execute the cells sequentially.
![Football Transfer Fee](graph.png)
