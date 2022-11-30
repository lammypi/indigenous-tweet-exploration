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

## Phase I - 26 Nov 2022

Phase I of this project was a way of getting acquainted with what the available data was like just to see what would possible for future analyses. For Phase I, I attempted a topic analysis which while interesting, would have benefited from double or triple the tweets. One of the main topics identified was associated with the death of Sacheen Littlefeather (accusations by a sibling that she was not Native American), while the other two seemed to be about people with mixed ancestry and Native schools.

Future phases should definitely use more tweets and revisit topic modeling, but also look at sentiment analysis. Also of interest would be a deeper look at the hashtags used, URLs and Quote URLs, and even the types of accounts making the tweets.
