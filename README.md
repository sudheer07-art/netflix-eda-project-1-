# Netflix EDA Project (1)

Hey! This is my Project 1 submission for the Pluto Academy AI & ML Internship.

## What is this project about?

I picked the Netflix Movies & TV Shows dataset from Kaggle and did a full exploratory data
analysis (EDA) on it. Basically I wanted to clean the data, dig through it, answer a few
questions, make some charts, and see what interesting patterns I could find.

**Dataset used:** Netflix Movies and TV Shows
**Dataset source:** https://www.kaggle.com/datasets/shivamb/netflix-shows

## Files in this repo

| File | What it is |
|---|---|
| `Project1_EDA_Netflix.ipynb` | Main notebook - all my code, charts and insights |
| `netflix_titles.csv` | The dataset I used |
| `README.md` | You're reading it :) |

## How to run this

1. Download or clone this repo
2. Open `Project1_EDA_Netflix.ipynb` in Google Colab or Jupyter Notebook
3. Make sure `netflix_titles.csv` is in the same folder as the notebook
4. Click Run All / Runtime → Run all
5. That's it, all the charts and outputs will show up

## Tools I used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## What I did (step by step)

1. **Loaded and inspected the data** - checked shape, column types, missing values, duplicates
2. **Cleaned the data** - removed 8 duplicate rows, fixed extra whitespace in the country column, filled missing values in director/country/rating
3. **Answered 5 questions** using groupby and value_counts, like:
   - How many Movies vs TV Shows are there?
   - Which countries have the most titles?
   - What ratings are most common?
   - How many titles were added each year?
   - What's the average release year for Movies vs TV Shows?
4. **Made 7 charts** - bar chart, horizontal bar chart, line chart, histogram, pie chart, scatter plot, and a heatmap
5. **Wrote 5 insights** based on what I found in the charts

## What surprised me the most

I honestly thought TV Shows would make up more of the catalog since everyone talks about
binge-watching, but Movies were the clear majority. Also didn't expect to see such a big jump
in titles added per year in the mid-to-late 2010s - shows how fast Netflix's library grew.

## Links

- **Colab notebook (view access):** (https://colab.research.google.com/drive/1F349Tc26C6oheoSoCJAUm0rYkrhAac2L?usp=sharing)
- **GitHub repo:** 

---
Made as part of the Pluto Academy AI & ML Internship 🚀
