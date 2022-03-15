# Public opinions of COVID-19 on Twitter during the outbreak reflect the initial vaccination rates
#### Topic modeling with tweets about COVID-19 using LDA and observe the association of it and vaccination rates using linear regression
### Introduction
Since the end of 2019, the COVID-19 pandemic has caused 5.8 million deaths in the world. To confront such a disease threat, the COVID-19 vaccines were released at the end of 2020. With lots of research about the effectiveness of COVID-19 vaccines[1], vaccines seem to be one of the most important ways of terminating the disease or preventing it from spreading. However, despite all the benefits vaccines provides, there are still differences in initial vaccination rates between states in the United States. Since Vaccines in the United States were sufficient and policy toward vaccines in the first few months since the vaccines were released was mostly similar between states, it implies that residents of different states or counties in the United States might have different attitudes toward vaccines. Social media has been a major way for people to deliver their opinions and share their ideas in recent years, and Twitter is one of the most popular social media in the United States. In 3 months ever since the outbreak, there are already 270 thousand public tweets about COVID-19. With only the Twitter data during the outbreak and interests of the insights of local level attitude at the time, this report plans to study whether the tweets about COVID-19 during the outbreak could anyhow reflect the vaccination rate of each county.
* **Data Resource:** [World Health Organization-Data](https://www.who.int/data), [Centers for Disease Control and Prevention (CDC)](https://covid.cdc.gov/covid-data-tracker/#datatracker-home), [Twitter](https://twitter.com/).
* **Methods:** Latent Dirichlet Allocation (LDA) Topic Modeling, Linear Regression.
### Core Methods
* [LDA Topic Modeling](https://web.archive.org/web/20120207011313/http://jmlr.csail.mit.edu/papers/volume3/blei03a/blei03a.pdf): A machine learning algorithm used to extract latent topics from text data.
* [Linear Regression](https://projecteuclid.org/download/pdf_1/euclid.bsmsp/1200512992): A linear approach for modelling the relationship between the document-topic distribution from LDA topic modeling and the future vaccination rate. 

### Techniques
Areas           | Techniques  |
--------------|:-----|
Data preprocess and topic modeling| [Python](https://www.python.org/)|
Report writing and linear regression model building| [RStudio](https://www.rstudio.com/)|

