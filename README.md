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

## Sam Builds
![image](https://github.com/maulshreegarg/shortform-content-analysis/assets/98210535/25f297d6-0e85-42ca-862b-d5802661b398)
On analysing the comments on both platforms youtube comments seem to show more growth spurts as well as increment, instagram reel comments generally seem to be the same across the board. Only a very small percentage of people viewing seem to engage further with the content with only a small sub group liking the video and an even smaller subgroup commenting. High number of 1 minute videos this creator seems to focus more on longer short form content. Both instagram and youtube show view spikes as well as like spikes around the same time in Feb and it maybe due to the same video. Instagram seems to work better for this creator on occasion.

## woke karen
![image](https://github.com/maulshreegarg/shortform-content-analysis/assets/98210535/6dfab2eb-e357-4998-926d-55dea2e04880)
There seems to be more likes for the same videos on instagram despite instagram views on average being lesser than youtube views.The average duration seems to be on the longer side with values between 1 minute to 56 seconds again. Youtube seems to generste more comments but there is a noticible spike of comments in both platforms over similar types of videos. Not all the videos are uploaded to instagram leading to the assumption that youtube is this creators primary platoform, but instagram has a more even distribution of likes and comments vs videos.

## nick digiovanni

## Methodology of the project
Steps that are being followed:
1. Scraping short-form content data from YouTube (shorts) and Instagram (reels) for the content creators who post the same content on both platforms for analyzing the performance of their videos.
2. Cleaning the scraped data by removing irrelevant columns as well as null values and changing the data types.
3. Data visualisation on PowerBI to see the trends in the data for each individual creators.
