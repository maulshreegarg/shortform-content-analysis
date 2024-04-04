# Shortform-Content-Analysis
# Data Collection process 
It is a comparative analysis of short-form content by the same creator uploading the same content on YouTube as well as Instagram. The IO scraper tool as well as Apify are used to manually collect data from YouTube shorts. The data collected is authentic, and detailed, and makes sure that the data being used for analysis is not falsified.
## Recommended scrapper tools 
https://www.scrapingbee.com/blog/web-scraping-tools/
## Tools we used
https://console.apify.com/actors?tab=all
https://www.webscraper.io/tutorials?utm_source=extension&utm_medium=popup
# Data preprocessing 
For data preprocessing we first removed all the irrelevant rows that we scraped like urls and id numbers and other columns that were inconsequential to our analysis.The preprocessed data has been stored in [preprocessed data](url). It contains information about 11 influencers including their date of posting, duration of their videos,number of likes comments, likes and views on youtube shorts as well as instagram reels.


# Exploratory data analysis
## Little Remy food
![image](https://github.com/maulshreegarg/shortform-content-analysis/assets/98210535/465f5554-24a5-4d8f-8e21-72335b3f65ec)
On comparing instagram vs youtube views by time we see that theres a spike on different days for youtube and instagram . On youtube the maximum views obtained are on 11th Febrary while on reels it is on 14th febrary 2024. In both the cases the amount of views go down after a spike but noticibly in Instagram the downfall is way more significant and there is relatively fewer spikes of increment in instagram all over as compared to youtube. 
Maximum number of videos uploaded by this creator are 21 seconds long, which is a pretty short duration reflecting the decrement of attention span of the audience. Instagram has more number of comments for the same video as compared to youtube despite there being a significant difference between views on both platforms.
In general instagram is more random with its virality while youtube is more consistent across the board for this creator and the performance is better on youtube.

## Methodology of the project
Steps that are being followed:
1. Scraping short-form content data from YouTube (shorts) and Instagram (reels) for the content creators who post the same content on both platforms for analyzing the performance of their videos.
2. Cleaning the scraped data by removing irrelevant columns as well as null values and changing the data types.
3. Data visualisation on PowerBI to see the trends in the data for each individual creators.
