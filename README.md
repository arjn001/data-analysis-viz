# Data Analysis & Visualization

**Author:** Arjun Gyawali
**Course:** CS4379G Data Analysis & Visualization

This repository contains the assignment for CS4379G. The first assignment explores the Netflix Movies and TV Shows dataset to analyze how content additions have changed over time and how ratings differ between Movies and TV Shows. 

## Assignment 1: Netflix Data Analysis

### Research Questions
1. How has the number of titles added to Netflix changed over time?
2. Do Movies and TV Shows differ in their ratings distribution?

### Key Findings
- Netflix content additions peaked around 2019 with ~2,000 titles, followed by a decline through 2021.
- Movies consistently outnumber TV Shows on the platform.
- TV-MA is the most common rating for both content types, but Movies have a wider spread across rating categories.

### Project Structure
```
data-analysis-viz/
├── README.md
├── .gitignore
├── data/
│   └── netflix/
│       └── netflix_titles.csv
└── notebooks/
    ├── analysis.ipynb
    └── analysis.html
```

### How to Run
1. Clone the repository: `git clone https://github.com/arjn001/data-analysis-viz.git`
2. Install dependencies: `pip install pandas matplotlib`
3. Open the notebook: `jupyter notebook notebooks/analysis.ipynb`
4. Alternatively, open `notebooks/analysis.html` in a browser to view the completed analysis.