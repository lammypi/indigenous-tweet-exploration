# indigenous-tweet-exploration

This repository holds explorations of tweets regarding Indigenous Americans. These explorations will look at topics and sentiments of the tweets, including:
- Links shared: Details about the site linked.
- Images shared: Number of images and their subjects.
- Hashtags applied
- Cashtags

The work in this repository is a pet project of mine. As a Native woman, I'm curious to learn more about the online interactions within and around the Indigenous community. 

[In-progress Tableau visualization](https://public.tableau.com/views/IndigenousTweetExploration/Dashboard-OverallTweetFeatures?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


## Packages Used

To scrape twitter, I used the twint package. The bulk of the NLP work in this project was done by gensim, spaCy, demoji, and contractions. Visualizations within the linked kaggle notebook were done using plotly for basic charts. To generate the topic modeling visualizations, I used pyLDAvis.
