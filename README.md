# 🎬 IMDB TV Shows EDA Analysis

Explore the trends, insights, and patterns behind the top-rated TV shows on IMDb. This project dives into a detailed exploratory data analysis (EDA) of IMDb TV show data, revealing what makes a series stand out in terms of ratings, popularity, and critical acclaim.
[Interactive Plot](https://github.com/sahil007707/IMDB-TV-Shows-EDA-Analysis/blob/main/Interactive%20Review%20Sentiment%20by%20Rating.png)

---

## 📌 Project Overview

This analysis answers key questions like:

- What genres dominate the top charts?
- How do average ratings vary across years?
- Which countries produce the most highly rated content?
- What runtime and episode counts are typical for successful series?

The project helps uncover **insightful visual stories** about the ever-evolving world of television.

---

## 🔍 Goals

- Understand the distribution of ratings, genres, and popularity.
- Identify trends by release year, runtime, and origin country.
- Visualize the relationship between number of votes and show ratings.
- Provide key data-driven recommendations for content production.

---

## 📊 Exploratory Data Analysis (EDA)

**Key Visualizations & Insights:**

- 📈 **Ratings Distribution:** Histogram of IMDb ratings across shows.
- 🌎 **Country-wise Analysis:** Bar plots showing number of shows per country.
- 🕒 **Runtime Trends:** Box plots and line graphs showing runtime vs. ratings.
- 🎭 **Genre Popularity:** Word clouds, count plots for genre frequency.
- ⭐ **Top Shows:** Tabular summaries of highest-rated shows by genre and year.
- 🔄 **Votes vs Ratings:** Scatter plots for vote count correlation with ratings.

📦 **Libraries Used:**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `wordcloud`

---

## 🗃️ Dataset Snapshot

| Feature         | Description                              |
|----------------|------------------------------------------|
| Title           | Name of the TV show                      |
| Year            | Release year                             |
| Age Rating      | Content rating (e.g. PG, TV-MA, etc.)    |
| IMDb Rating     | Average IMDb rating                      |
| Votes           | Number of user ratings                   |
| Genre           | Genres of the show                       |
| Country         | Country of origin                        |
| Language        | Language(s) spoken                       |
| Runtime         | Average runtime per episode              |

🧪 *Dataset source: IMDb (scraped/simulated for educational purposes).*

---

## 📌 Highlights

- 📊 **USA, UK, and India** are leading in the production of highly rated shows.
- 🎭 **Drama** is the most dominant genre, followed by Crime and Comedy.
- ⏱️ Shows with 40–60 min runtime often have better ratings.
- 🗳️ A positive relationship exists between **number of votes** and **rating credibility**.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sahil007707/imdb-tvshows-eda.git
   cd imdb-tvshows-eda
