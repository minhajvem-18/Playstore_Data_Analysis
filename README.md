# Google Play Store Data Analysis

This project analyzes Google Play Store data to find out what makes an app successful. It covers data cleaning, exploration, and visualization using Python.

## Dataset
Around 10,354 apps across 33 categories and 119 genres.
Source: [Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

## Tools Used
Python, pandas, numpy, matplotlib, seaborn

## What Was Done
The raw data was cleaned by fixing column types, handling missing values, and standardizing formats. The cleaned data was then explored and visualized using bar charts, scatter plots, pie charts, heatmaps, and more.

## Key Findings
- More reviews = more installs. This is the strongest pattern in the data.
- Ratings do not predict installs. Both low and high rated apps can go viral.
- 93% of apps are free.
- Family, Game, and Tools are the top categories.
- App size has no effect on ratings or installs.
- Apps updated regularly tend to have more installs.
- Higher priced apps get fewer installs.

## How to Run
Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn
```
Then open `Playstoredata.ipynb` in Jupyter Notebook.
