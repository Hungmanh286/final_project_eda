# Facebook Fanpage Analysis — iVIVU.com

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

Final project for the course *Data Processing with Python* (2023). We collect posts, comments, and reactions from the iVIVU.com travel fanpage on Facebook and explore them with pandas, matplotlib, and seaborn.

## Notebooks

| # | Notebook | What it does |
|---|---|---|
| 1 | [01_crawl_posts.ipynb](01_crawl_posts.ipynb) | Collects posts, comments, and reactions with `facebook-scraper` |
| 2 | [02_post_analysis.ipynb](02_post_analysis.ipynb) | Posting-time patterns, top keywords (word cloud), post sentiment with TextBlob |
| 3 | [03_comment_analysis.ipynb](03_comment_analysis.ipynb) | Comment keywords and frequency analysis |
| 4 | [04_reaction_statistics.ipynb](04_reaction_statistics.ipynb) | Reactions per post, reaction types over time, missing-value handling |

## Data

- `ivivu.xlsx`: crawled posts and their metadata
- `iVIVU.npy`: intermediate array used by the analysis notebooks

## Run

```bash
pip install pandas numpy matplotlib seaborn wordcloud textblob scikit-learn facebook-scraper openpyxl
jupyter notebook
```
