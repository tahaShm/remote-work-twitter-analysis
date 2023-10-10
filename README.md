# Remote Work Twitter Analysis
This is a data analysis project using ML/NLP techniques concerning tweets relevant to remote work.

## Data Collection
To conduct the analysis of Persian tweets related to remote work during the COVID-19 pandemic, we employed the Twitter API to fetch Persian Twitter data. A dataset comprising 45,359 remote work-related tweets was extracted using specific Farsi and English query phrases.
From the collected Persian tweets, we focused on selecting tweets that were relevant to remote work. We designed a comprehensive query using the Elasticsearch Query DSL to target specific words and phrases associated with remote work in Persian. The query included a range of phrases such as "کار از منزل" (work from home), "کار در خانه" (work at home), "کار از راه دور" (remote work), and various other related terms. Additionally, we incorporated English terms like "teleworking," "telecommuting," "flexiplace," and "flexiwork" to encompass a broader range of remote-work-related tweets in the analysis, as they may be used in the hashtags. By utilizing this query, we ensured that our data collection process focused on tweets that explicitly mentioned or discussed remote work. This allowed us to gather a relevant and representative dataset for our analysis. We excluded certain fields such as thumbnails, photos, and videos to focus solely on the textual content of the tweets, enabling us to examine the discourse surrounding remote work during the pandemic more comprehensively.

<p align="center">
  <a href="https://www.linkpicture.com/view.php?img=LPic65251f49c343a464832547">
    <img src="https://www.linkpicture.com/q/wordcloud.png" height="300" />
  </a>
  <a href="https://www.linkpicture.com/view.php?img=LPic65252149d2621979188254">
    <img src="https://www.linkpicture.com/q/wordcloud_translated.png" height="300" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkpicture.com/view.php?img=LPic65252255be642495278716">
    <img src="https://www.linkpicture.com/q/tweets.png" height="300" />
  </a>
</p>


