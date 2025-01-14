# Movies Data Analysis

## Overview

This repository focuses on analyzing movie data to uncover trends and insights in the movie streaming industry. Using Python and Tableau, it provides stakeholders with an interactive dashboard to understand content distribution, genre prevalence, and viewer preferences. The insights aim to assist platform curators, filmmakers, and market analysts in making informed decisions.

## Features

- **Geographical Analysis**: Visualize movie production and ratings by country.
- **Director Contributions**: Evaluate top directors and their influence on movie success.
- **Trend Analysis**: Examine historical trends in movie ratings from 1910 to 2020.
- **Platform Insights**: Understand content distribution across major streaming platforms (e.g., Netflix, Hulu, Disney+).
- **Interactive Dashboard**: Explore data using filters, tooltips, and visual drill-downs.

## Tableau Dashboards

This project includes one Tableau dashboard for interactive data exploration:

****

- Analyzes and visualizes global content distribution, rating trends, genre breakdown, and audience preferences across platforms.
- [Dashboard Demo](https://github.com/Eins51/MoiveAnalytics/blob/master/tableau/videos/dashboard.mp4)
- ![Dashboard Preview](https://github.com/Eins51/MoiveAnalytics/blob/master/tableau/videos/dashboard.gif)
- Link: https://public.tableau.com/app/profile/yi.wang4922/viz/Movies_Data_Analysis/Dashboard1

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/Eins51/MovieAnalytics.git
   ```

2. Navigate to the project directory:

   ```
   cd MovieAnalytics
   ```

3. Install required Python packages:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter Notebook for data analysis:

   ```
   jupyter notebook notebooks/movies_data_analysis.ipynb
   ```

2. Explore Tableau dashboards for interactive visualizations.

## Project Structure

```
MovieAnalytics/
├── data/                     # Dataset files
├── notebooks/                # Jupyter Notebook for analysis
│   └── movies_data_analysis.ipynb
├── tableau/                  # Tableau dashboard files
│   ├── dashboards/           # Tableau packaged workbooks (.twb)
│   ├── videos/               # Dashboard demonstration videos
│   └── screenshots/          # Dashboard preview images
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
```

## Key Insights

1. Top Performing Countries:
   - United States and United Kingdom dominate movie production and ratings.
2. Director Contributions:
   - Directors like Steven Spielberg and Robert Stevenson consistently produce high-rating movies.
3. Platform Preferences:
   - Disney+ excels in family and animated content, while Netflix leads in Drama and Action genres.
4. Rating Trends:
   - A notable increase in average movie ratings post-2000s.

## Recommendations

- Focus content acquisition on high-performing regions like the US and UK.
- Diversify genres to include niche categories like Documentaries and Indie Films.
- Leverage historical data to optimize audience engagement strategies for specific seasons.

## Acknowledgments

Special thanks to:

- Tableau for providing robust visualization capabilities.
- Python libraries like Pandas and Matplotlib for enabling data analysis.