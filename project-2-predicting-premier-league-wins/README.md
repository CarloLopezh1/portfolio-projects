# Predicting Premier League Wins Using FIFA Player Ratings

This project explores how well FIFA video game player ratings can predict match outcomes in the English Premier League. By merging player-level FIFA data with Premier League match statistics, we created and tested predictive models with real-world implications — particularly in the context of sports betting.

## Project Overview

**Goal:**  
Evaluate whether differences in FIFA player ratings between opposing teams can predict match outcomes (win vs. not win) for the home team in Premier League matches.

**Why It Matters:**  
If FIFA ratings — though fictional — can serve as a reliable proxy for real-world performance, they could support more informed sports betting, preseason predictions, and fan-driven analysis.

## What We Did

- **Data Merging & Wrangling:** Combined FIFA 20 player data (2015–2020) with Premier League match outcomes (2010–2021).
- **Feature Engineering:** Created position-group aggregates (Attack, Midfield, Defense, Goalkeeper) and calculated rating differentials (home vs. away).
- **Modeling:** Built and evaluated 3 logistic regression models to predict whether the home team wins.
- **Evaluation:** Compared models using accuracy, sensitivity, specificity, and PPV — key metrics for betting decisions.

## Key Results

- **Final model accuracy:** 71.31% at 0.6 cutoff  
- **Most predictive features:**  
  - Difference in maximum attack ratings  
  - Difference in median midfield ratings  
  - Goalkeeper rating differences  
- **Least important feature:** Work rate (except for goalkeeper)

##  Betting Insights

- **Maximize Winnings:** Use the final model with a 0.6 cutoff to prioritize PPV (positive predictive value).
- **Minimize Losses:** Same model/cutoff offers highest specificity, reducing false predictions.

---

## Project Structure

- [`Fifa_Project_Report.pdf`](Fifa_Project_Report.pdf): Full Report and Findings
- [`Fifa_Project_Presentation.pdf`](Fifa_Project_Presentation.pdf): Final presentation slides
- [`Fifa_Project_Rcodes.Rmd`](Fifa_Project_Rcodes.Rmd): Full Project R code
---

## Data Sources

1. **[FIFA 20 Complete Player Dataset](https://www.kaggle.com/datasets/stefanoleone992/fifa-20-complete-player-dataset)**  
   Player ratings and attributes from FIFA 15–20.

2. **[Premier League Matches 2010–2021](https://www.kaggle.com/datasets/pablohfreitas/all-premier-league-matches-20102021)**  
   Results and statistics from 4,000+ EPL matches.

---

## Tools Used

- Data wrangling: Likely R (notebooks/code not included)
- Statistical modeling: Logistic Regression
- Visualization: Charts to show feature importance & prediction distributions
- Evaluation: Confusion matrices, PPV, specificity, sensitivity

---

## Team

- Sam Assaf, Garrett Atkinson, Carlo Lopez Hernandez  
- University of Notre Dame – MSBA Sports Analytics  
- Course: MSSA-60220 Predictive Analytics (Fall 2023)

---

## Reflections

This project demonstrates how structured public datasets and predictive modeling can uncover valuable insights — even from video game ratings. With some creativity, FIFA ratings become a surprisingly useful tool for decision-making in real-world sports contexts.

---



