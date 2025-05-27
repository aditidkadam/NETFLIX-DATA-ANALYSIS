#  Netflix Data Analysis

This project explores Netflix's content catalog to understand trends, patterns, and insights from its global streaming service using a dataset of movies and TV shows.

---

##  Objective

To analyze Netflix data and uncover insights such as:
- Trends over the years
- Popular content types and genres
- Country-wise contributions to Netflix's library

---

##  Data Cleaning Summary

The original dataset had some inconsistencies and missing values. The following steps were taken to clean the data:

- **Duplicates Removed**: Ensured unique records
- **Missing Values Handled**:
  - `country`: Filled with `'Unknown'`
  - `cast` and `director`: Filled with `'Not Available'`
- **Date Format Fixed**: The `date_added` column had leading spaces; they were stripped and then parsed using `pd.to_datetime()` with `errors='coerce'`.

---

##  Key Insights

### 1.  Content Type Distribution

Netflix's library is primarily composed of:

- **Movies**: 6131 titles
- **TV Shows**: 2676 titles

This indicates a strong focus on movie content, although TV shows also represent a significant share.

---

### 2.  Year-wise Content Addition

Netflix aggressively expanded its catalog in the late 2010s, particularly during 2018–2020.

This aligns with:
- Its international growth strategy
- Increased investment in original content
- Rise in competition in the streaming space

---

### 3.  Top Countries by Content Count

The countries with the most content available on Netflix are:

United States 2555
India 923
United Kingdom 397
Canada 177
Japan 174
South Korea 168
France 122
Spain 100
Mexico 99
Turkey 92


The United States dominates the catalog, followed by India and the United Kingdom—highlighting a strong Western and South Asian content base.

---

### 4. 🎬 Most Common Genres

Netflix offers a wide variety of genres. The top 10 most frequent genres are:

Dramas 3889
International Movies 2786
Comedies 2637
Action & Adventure 1328
Documentaries 1219
Children & Family Movies 1087
TV Dramas 773
Romantic Movies 762
Thrillers 727
Crime TV Shows 646


This reflects a diverse audience taste, with drama and international content leading the way.

---

##  Conclusion

Netflix's content strategy emphasizes:

- Quantity: A consistent rise in titles, especially from 2016 to 2020
- Diversity: Global and multilingual content to attract international audiences
- Genre balance: Wide coverage from documentaries to dramas and thrillers

The platform’s data reflects how digital streaming is not just about watching—it's about personalization, variety, and global storytelling.

---

##  Tools & Techniques Used

- **Pandas**: For data manipulation and cleaning
- **Matplotlib & Seaborn**: For visual exploration
- **Python**: For scripting and data handling

---

##  Dataset

- Title: `netflix_titles.csv`
- Source: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/shivamb/netflix-shows)

---




