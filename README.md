# TV Ratings

**IMDb** (Internet Movie Database) is an online database of information related to films, television series, podcasts, home videos, video games, and streaming content online - including cast, production crew and personal biographies, plot summaries, trivia, ratings, and fan and critical reviews.

## About

This project focuses on analyzing and visualizing IMDb ratings of popular TV series and films, aiming to uncover trends and patterns across seasons and episodes. The datasets used for analysis are available at [this link](https://datasets.imdbws.com/).

The project starts by preparing the data, loading information from the downloaded CSV files and filtering out relevant details about the selected TV series. The data visualization step employs two primary methods: trendline plotting, which provides insights on the show's performance over various seasons, and heatmap representations, providing a comprehensive overview of episode ratings across seasons.

## Repository overview

```
├── README.md
├── data
├── figures
└── notebooks
```

**The Walking Dead**

![The-Walking-Dead](/figures/twd_seasons_avg.png)

![The-Walking-Dead](/figures/twd_ratings_coolwarm.png)

![The-Walking-Dead](/figures/twd_ratings_custom1.png)

![The-Walking-Dead](/figures/twd_ratings_custom2.png)

**New Girl**

![New Girl](/figures/ng_seasons_avg.png)

![New Girl](/figures/ng_ratings_coolwarm.png)

![New Girl](/figures/ng_ratings_custom1.png)