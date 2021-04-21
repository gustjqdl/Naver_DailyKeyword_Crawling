# Naver_DailyKeyword_Crawling

## * Update : 2 Depth keyword lists -> We updated the list of related keyword and similar keyword to the next related keyword which is from the first realated keyword. 
##          : Review and Inspection -> We made the process that could find the error keyword.
## Goal
### The purpose of this analysis is to identify the characteristics of changing users by identifying the daily search volume of Naver keywords.

## Crawling 
1. Naver Trend API 
2. Naver search AD Admin API 
   * sourced by PowerNad Module 
3. Google API 

## Process
1. Selenium extracts associated search terms for keyword_list 

2. Using Naver Trend API, trend index data is extracted.

3. Using Powernad module, recently month data is extraced.

4. Get daily data.

5. Upload to the Google Spread Sheet using Google API

6. It is automated through schedule module.
