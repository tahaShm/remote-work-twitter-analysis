# Remote Work Twitter Analysis
This is a data analysis project using ML/NLP techniques concerning tweets relevant to remote work.

## Data
To conduct the analysis of Persian tweets related to remote work during the COVID-19 pandemic, we employed the **Twitter API** to fetch Persian Twitter data. A dataset comprising **45,359** remote work-related tweets was extracted using specific Farsi and English query phrases.

We focused on selecting tweets relevant to remote work from the collected Persian tweets. We designed a comprehensive query using the Elasticsearch Query DSL to target specific words and phrases associated with remote work in Persian. The query included a range of terms such as *"کار از منزل" (work from home)*, *"کار در خانه" (work at home)*, *"کار از راه دور" (remote work)*, and various other related terms. By utilizing this query, we ensured that our data collection process focused on tweets that explicitly mentioned or discussed remote work. This allowed us to gather a relevant and representative dataset for our analysis. We excluded certain fields such as thumbnails, photos, and videos to focus solely on the textual content of the tweets, enabling us to examine the discourse surrounding remote work during the pandemic more comprehensively.

<p align="center">
  <br/>
  <a href="https://www.linkpicture.com/view.php?img=LPic65252a921aaad611372850">
    <img src="https://www.linkpicture.com/q/TweetCounts.png" height="300" />
  </a>
  <br/>
  <em>Tweet Counts</em>
</p>

## Preprocessing

We removed duplicate **chars** and **emojis** (available in *emojies.txt*), **stop-words** (available in the *stopwords* folder), **Unicode errors**, **URLs**, **phone numbers**, **emails**, **currency symbols**, and useless punctuations and chars. Also, **normalization** and **lemmatization** were applied using tools like `Hazm` and `NLTK`.

<p align="center" style="display: inline-block; text-align: center;">
    <a href="https://www.linkpicture.com/view.php?img=LPic65251f49c343a464832547">
      <img src="https://www.linkpicture.com/q/wordcloud.png" height="250" />
    </a>
    <a href="https://www.linkpicture.com/view.php?img=LPic65252149d2621979188254">
      <img src="https://www.linkpicture.com/q/wordcloud_translated.png" height="250" />
    </a>
    <br/>
    <em align="center">&emsp;&emsp;&emsp;Wordcloud (Persian)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Wordcloud (Translated)&emsp;&emsp;</em>
  <br/>
</p>

