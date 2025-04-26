'# IMDB Movies Data Exploration (2010-2019)

---

## Overview
This project explores IMDB movie data from 2010 to 2019, focusing on trends in genres, audience voting participation, and average movie ratings.


Using SQL queries, pandas, matplotlib, numpy, and sqlite3 , I analyzed how factors like movie genre and number of votes impact audience ratings.  The project culminates in a set of visualizations, business questions, and data cleaning recommendations.

---

## Files
- `im.db` — SQLite database containing IMDB movie data
- `exploration_notebook.ipynb` — Jupyter notebook containing SQL queries, exploration, and visualizations
- `presentation_slides.pptx` — Summary of findings and business insights
- `README.txt` — This file

---

## Key Insights
- Drama, Comedy, and Action were the most common genres between 2010 and 2019.
- Higher audience voting participation stabilizes movie ratings but does not necessarily lead to higher scores.
- Genres with fewer votes tend to show more extreme (very high or very low) ratings, indicating greater rating volatility.
- Business question: How can studios encourage greater audience voting participation to support stable and favorable public reception?

---

## Future Directions
- Implement a weighted rating system (Bayesian average) to fairly balance movies with different numbers of votes.
- Split multi-genre entries (e.g., "Action,Comedy") into individual genres for more precise genre-level analysis.
- Conduct year-over-year trend analysis to track how movie popularity and ratings evolve over time.
- Explore audience demographics if available in future datasets.

---

## How to Run
1. Clone this repository.
2. Ensure you have the following Python libraries installed:
   - pandas
   - sqlite3
   - matplotlib
   - numpy
3. Open the Jupyter notebook (`SQLSummativeLab.ipynb`) and run all cells.

---
