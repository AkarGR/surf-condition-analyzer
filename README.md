# Surf Condition Analyzer 🌊

Data analysis project classifying surf conditions using 2.5 years of real wave buoy 
data from Mooloolaba, Australia (2017-2019).

## Key Findings
- 54.4% of days have Good or Epic surf conditions at Mooloolaba
- Primary surf season runs February to June (Southern Hemisphere autumn/winter swells)
- Secondary wave peak in October (spring swell)
- Maximum recorded wave height: 7.91m
- Average peak wave period: 9 seconds

## The "Surf or Skip?" Classifier
Built a custom condition rating system based on real surfer criteria:
- Wave height (Hs) thresholds for size
- Peak period (Tp) to measure swell quality — short period = choppy, long period = clean
- Combined scoring to classify: Epic / Good / Average / Choppy / Flat / Dangerous

## KPIs Analyzed
- 43,643 wave readings across 2.5 years
- Surf condition distribution across all readings
- Best months for surfing by good/epic day count
- Average wave height trends by month

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
Coastal Data System — Waves (Mooloolaba) January 2017 to June 2019
Source: Kaggle

## Background
Built by a surfer and logistics analyst combining domain knowledge with Python 
data analysis. The classifier uses real surfing criteria — not just wave height, 
but swell period quality — to give meaningful condition ratings that a surfer 
would actually trust.
