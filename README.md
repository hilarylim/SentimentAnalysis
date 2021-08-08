# Sentiment Analysis on ReviewPro (Hotel) - Mini Project #1 
The codes done by YingKi, QiRui and myself over the span of 2 weeks. 
\
**Hypothesis #1:** Hotel location affects customer satisfaction  
**Hypothesis #2:** 5-star hotels are rated positively on 'rooms' as compared to 3-star hotels
\
**Hypothesis #3:** 3-star hotels are rated negatively on 'value' as compared to 5-star hotels

## Codes and Resources Used 
**Python Version:** 3.8 \
**Packages:** numpy, pandas, matplotlib, seaborn, wordcloud, scipy, statsmodels \
**Dataset:** provided by the school (Institute of Data)

## Data Overview 
Dataset collected in 2013, contains 3 different tabs; namely (i) Sentiment Data, (ii) Sentiment Mentions and (iii) STB Rating.
\
**(i) Sentiment Data:** shows the GRI (Global Review Index) score which computed by a special algorithm of the ratings (ranging from positive, neutral, negative and no review) given for each concept (a total of 9 concepts which affects the GRI score).
\
**(ii) Sentiment Mentions:** shows the total mentions (positive and negative) for each concept (such as room, hotel, location, etc) 
\
**(iii) STB Rating: Hotel star category**
In this repository, we combined the data given in tabs (i) and (iii). Such that we can decide to accept or reject the three hypothesis that were mentioned above. 

## Assumption 
* Customer Satisfaction Score = % of positive reviews - % of negative reviews 

## Takeaways 
From our findings, it shows that: 
* 1. **H0** is rejected, although location has a correlation with customer satisfaction of 0.4. But it is not as impactful as Service, Room or Cleanliness 

<img width="500" alt="cust satisf corr table" src="https://user-images.githubusercontent.com/77626155/128627941-84ce1184-a3e9-421d-96a2-45cf3d0fb781.PNG">

* 2. 5-star hotel customers care about both room satisfaction and value 

<img width="1200" alt="corr2" src="https://user-images.githubusercontent.com/77626155/128628188-01830dce-b2c9-436d-977a-71b1861d5e15.PNG">
