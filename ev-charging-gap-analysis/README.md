# EV Charging Infrastructure Gap Analysis

## The question

Ontario is adding electric vehicles faster than it is adding places to charge them. Where is that gap widest, and which regions should get the next chargers?

## Approach

1. Profiled and cleaned EV registration and public charging station datasets
2. Joined the sources to a common regional key
3. Built a weighted gap score, 60% vehicle demand and 40% charger supply, to rank regions
4. Fit a growth model on EV adoption, reaching R² = 0.76
5. Prototyped a nearest-station recommender
6. Built a country-level dashboard summarising the results

## Tools

Python, pandas, scikit-learn, Matplotlib, Jupyter


## Files

Add here: the analysis notebook, the cleaned dataset or a link to the source, the process and data flow diagram, and the final slide deck.
