# netflix-colab
Analysis of Netflix titles, revenue, subscribers, and award-nominated movies to explore what kind of shows and films Netflix should produce.

## Contents
- `data/netflix_titles.csv` – Movies and TV shows available on Netflix, including cast, countries, and other metadata.  
- `data/netflix_revenue.csv` – Netflix revenue data collected from the official Investor Relations webpage.  
- `data/netflix_subscribers.csv` – Subscriber growth and regional data from the Investor Relations webpage.  
- `data/academy_award_movies.csv` – Academy Award–nominated movies dataset scraped from Wikipedia.  
- `notebook.ipynb` – Unified analysis notebook that cleans, enriches, and explores all datasets.

## Data Sources
- **Netflix Movies & TV Shows dataset** – Missing metadata (cast, country) extracted using the [OMDb API](https://www.omdbapi.com/).  
- **Revenue & Subscribers** – Taken directly from the [Netflix Investor Relations](https://ir.netflix.net/) website.  
- **Academy Award Movies** – Scraped from [https://en.wikipedia.org/wiki/List_of_Academy_Award%E2%80%93nominated_films]) for nominations and awards data.

## Key Steps
1. **Data Cleaning & Enrichment** – Handling missing values with OMDb API lookups.  
2. **Merging Datasets** – Combining Netflix content with revenue, subscriber, and award data.  
3. **Exploratory Analysis** – Identifying patterns in content type, region, and success metrics.  
4. **Insights** – Recommendations on the type of shows and movies Netflix could prioritize producing.

## Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/netflix-colab.git
   cd netflix-colab
