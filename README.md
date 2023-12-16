# Sentiment Analysis on News Sources Regarding Electric Vehicles

## Research Question
Is there a difference in average sentiment between different news sources regarding the topic of electric vehicles?​

## Methods Used
* Sentiment Analysis (AFINN Lexicon in R)
* Welch's T-test
* Logistic Regression
* Data Visualization

## Project Description
With the emergence of electric vehicles as a pressing business, political, environmental, and consumer topic; our group was interested in reviewing the ways that media distributes relevant information. As a somewhat divisive issue, we wanted to see if different sources are distributing information that is favorable for or against EVs.

## Data Used
There wasn't a readily available dataset that we could use to answer this question. As such, we had to collect our own data. We used this [media bias chart](https://www.allsides.com/media-bias/media-bias-chart) to identify nine news sources, three for each lean (left, center and right). For each news source, we collected data from 10 articles. We copied and pasted each article text into a [csv file](https://github.com/hamza6khan/sentiment-analysis-ev/blob/main/ling_460_project_data.csv) along with their link, news source, lean and more.

## Limitations
Due to time constraints, we weren't able to collect a large amount of data, which could help increase the validity of our results.

## Conclusion
Through comparing average sentiments and utilizing Welch's t-tests, we were able to find statistically significant results that revealed the following results:
* Left-leaning news sources are the most positive regarding electric vehicles
* Right-leaning news sources are the most negative regarding electric vehicles
* Center-leaning news sources vary in sentiment, but are mainly neutral
