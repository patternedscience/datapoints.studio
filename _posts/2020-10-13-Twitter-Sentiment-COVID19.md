---
layout: full-width
title: Sentiment of Twitter users on COVID-19
---

The dataset of the geospatial analytics project includes CSV files that contain IDs and sentiment scores of the tweets related to the COVID-19 pandemic. The model monitors the real-time Twitter feed for coronavirus-related tweets using 90+ different keywords and hashtags that are commonly used while referencing the pandemic.

Only the tweets with *exact geo-location* are considered, with the following color codes for the sentiments of the tweets: Red (Negative), Green (Positive) & Orange (Neutral)

{% fullwidth "assets/img/post-TwitterSentimentCOVID19.png" "A screenshot of the global, interactive map, zoomed into Montreal, Canada" %}

<a href="{{site.baseurl}}/assets/N4_Mapping_Color_Dot.html">Global Interactive Map</a> (29 MB)

Original dataset collection (tweets) and sentiment scoring by [Rabindra Lamsal](https://rlamsal.com.np/), with the dataset published on [IEEE DataPort](https://ieee-dataport.org/open-access/coronavirus-covid-19-geo-tagged-tweets-dataset).

Cen (Ester) Chen is the main developer of this notebook and a contributor to the design and maintenance of this website. Reach out to her via her [website](https://ester-cen-chen.com/) or [LinkedIn profile](https://www.linkedin.com/in/ester-c-chen/). The notebooks containing the full pipeline, leading to the above map, are in Ester's [GitHub repo](https://github.com/E-C-C-NOVEMBER-RAIN/geospatial_analytics).
