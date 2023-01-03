# Hotel Review Analysis

<p align="center">
<img src="https://github.com/ianjeffries/text-sentiment-analysis/blob/master/images/header_wordcloud.PNG" alt="alt text" width="790" height="570">
</p>

## Index 
1. [Summary](https://github.com/imverma/-Hotel-Review-Analysis#summary)
2. [File Directory](https://github.com/imverma/-Hotel-Review-Analysis#file-directory)
3. [Language and Packages Used](https://github.com/imverma/-Hotel-Review-Analysis#language-and-packages-used)


## Summary 
The following project utilizes R to mine sentiment from over 21,000 hotel reviews on resorts located across globle.

## File Directory

1. data - contains the three files used in analysis:
         a. maldives_hotel_reviews.csv - Hotel reviews of resorts in the Republic of Maldives.
         b. negative-lexicon.txt - Negative lexicon used to locate "negative" words.
         c. positive-lexicon.txt - Positive lexicon used to locate "positive" words.

2. images - contains vizualizations:
         a. body_wordcloud.png - Wordcloud showing commonly occuring words in the review body.
         b. header_wordcloud.PNG - Wordcloud showing commonly occuring words in the review header.
         c. monthly_sentiment.png - Overall sentiment by month for all hotels in the Republic of Maldives.
         d. reviews_by_year.png - Count of reviews by year.
         e. sentiment_comparison.png - Comparision of negative and positive wordcounts.
         f. top_12_hotels.png - Top 12 resorts sentiment comparison.

3. text_mining.Rmd - R Markdown detailing the text mining process.

4. text_mining.pdf - PDF that shows R code and the outputted results, for easy viewing.

5. results.pdf - A full write-up comparing text mining in R vs SAS.

## Language and Packages Used

R is used for all model building.


