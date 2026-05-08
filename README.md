# IPL Chasing Pressure Analysis

## Project Overview
This project analyzes how match pressure impacts chasing outcomes in IPL matches using ball-by-ball and match-level datasets.

The analysis focuses on:
- Required Run Rate (RRR)
- Wickets Left
- Balls Remaining
- Match Outcome

---
## Dataset Used
- `deliveries.csv` — Ball-by-ball IPL data
- `matches.csv` — Match-level IPL metadata

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Key Steps Performed

### Data Cleaning
- Handled missing values
- Verified datatypes
- Removed duplicates
- Validated match IDs

### Data Transformation
Created new analytical features:
- Current Score
- Balls Left
- Wickets Left
- Runs Remaining
- Required Run Rate

### Visualization & Analysis
Generated plots to analyze:
- Required Run Rate vs Winning
- Wickets Left vs Winning
- Pressure Trend Across Overs
- Correlation Between Match Factors

---

## Key Insights
- Higher required run rate reduces chasing success.
- Teams with more wickets remaining handle pressure better.
- Match pressure increases significantly during later overs.
- Current score alone is not sufficient to determine winning chances.

---

