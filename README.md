# Nike-Vs-Adidas
![image](https://user-images.githubusercontent.com/123437423/226263583-0d70557d-12f5-49f6-95ad-86a8f4eff51c.png)

Comparing the Most &amp; Least Popular Nike &amp; Adidas Shoes of 2020

## Context
1. Background
2. Business Question
3. Data Cleaning
4. Data Analysis
5. Key Findings
6. Recommendations
7. Limitations
8. References/Software

## Background
This project revolves around an extensive analysis of ratings for Adidas and Nike shoes, ranging from the highest to the lowest. Utilizing Kaggle, I acquired the data that describes the shoe models that were released in 2020, accompanied by ratings on a scale of 1 to 5 (with no description provided on how the rating was determined). From a business perspective, this analysis allows Adidas and Nike to identify the shoes that were most and least appreciated by customers in 2020. This is particularly noteworthy given that 2020 marked the onset of the pandemic, providing customers with greater availability to shop during periods of shutdown. For shoe businesses, it is crucial to monitor which models are popular and which are not, in order to consistently release new models and collaborations. To see more of the data, the excel sheet is attached to the project file [here](https://github.com/jo3kim/Nike-Vs-Adidas/blob/main/Adidas%20vs%20Nike.xlsx).

## Business Question
With the background kept in mind, a business question was obtained:

**How should Nike and Adidas decide on which shoes to re-release or promote better ratings?**


## Data Cleaning
The first process starts with data cleaning. The data retrieved as a csv file is downloaded onto Google Sheets. There we can look at these step-by-step cleaning process:
1. Average Ratings
* Average number of the reviews were calculated to gather more specifics and reduce the number of rows. To do this, the average function was used to find Nike's average number of reviews of 42, and Adidas' of 70. Anything below the average numbers were deleted. This allowed 1899 rows to be deleted.
2. Nulls & 0's
* Null's and 0's were looked over to be deleted. The only column to not delete 0's was the ratings column. Null's and 0's were found using the filter column. No rows were found with Nulls.
3. Duplicates
* Duplicates were checked with the duplicates function. No duplicates were found.
4. Conditional Formatting
* Conditional Formatting is also another way to find any Null's, blank spaces, or incorrect data. They boxes were highlighted if there was an error or blank space. There ended up being no highlighted boxes.
5. Spelling/Grammer
* Spelling and Grammer were checked with the spelling check and the shoe names were changed to capitalizing like a title with the ChangeSpace tool.

## Data Analysis
After cleaning the data, the data was separated into two sheets: Nike and Adidas. Because Adidas had so much data, the data needed to be further separated into pivot tables. Two pivot tables were created to show all of the 5 ratings and 0 ratings shoes. Nike did not need a pivot table, as it only had 23 rows of data. Specifically with this data, we are only looking at the ratings and the number of reviews of each shoe. Everything else could help conclude key findings. Here are the results:

* Adidas 0 Ratings Chart
![Adidas 0 Rating](https://user-images.githubusercontent.com/123437423/226259518-6711784c-77a5-4033-bf84-d8ab16d29b88.png)
* Adidas 5 Ratings Chart
![Adidas 5 Rating](https://user-images.githubusercontent.com/123437423/226260120-2060a1de-6d21-4215-9ebf-008e8a829fd3.png)
* Nike Ratings Chart
![Nike](https://user-images.githubusercontent.com/123437423/226259557-47ab3808-1ac8-4f94-a0ca-675b7fbd8cbb.PNG)

(We can see that each shoe is labeled with their Product ID's. It is important to see how many people reviewed each shoe with the ratings)

## Key Findings
Here are the top 3 key findings:
1. There are more participation with Adidas shoes than Nike, showing that Adidas shoes were more popular in 2020. Thus, more sought after than Nike.
2. Across the board, we see that the running shoes and comfort shoes/slides had the top ratings for Nike, as Adidas had multiple various shoes in lowest and highest ratings.
3. The link towards the retail price can be the issue to the ratings as well. For Nike, the basketball shoes are generally more expensive that could range from $130 to $200+. This can be an issue for customers buying the shoes at a high cost and expecting high performance or quality. 
4. For Adidas it looks like a specific model of a shoe to the materials look generally the same for the 5 rating. For example, the silhoutte of the Running Norad shoe looks simliar to all of the other 5 rating shoes. Even with the shoes with the boost or cloud technology.

## Recomendations
1. There should be more releases on the higher rating quality running shoes for each company the following year. The least popular shoes were basketball or the lower quality material shoes for Nike, and various running and outdoor/indoor shoes for Adidas. Having more Nike shoe model releases can also compete with Adidas. Unless, Nike's overall number of shoes released equals Adidas'.
2. For Nike, to increase ratings of the basketball shoes, more promotions or sales should happen to potentially help with the lower expectation of the quality to the price. For Adidas, they should focus on re-releasing their highest rated shoes with different colorways or collaborations.
3. Release similar silhouttes for each brand of the highest rating shoes. Even consider to re-release the lower rating shoes with better technology.

## Limitations
1. Limitations in how the rating system is structured is not outlined. This is hard to see if the customers rated the shoes based off of quality, color, comfort, and/or durability.
2. Limitations on the population size was not discussed or how it was retrieved. The data could possibly include only one state of the United States. Does not even include if the data is from United States.
3. Limitations on which shoe to put on the data was not showcased. There were other Jordan models that were released from Nike. So, knowing why certain models were left out is important. 
4. If each company gave an outline to include shoe models with a certain number of reviews, more shoe models can be inputted into the data.

## References
* Google Sheets/Microsoft Excel
* Kaggle
* Kaggle Data: https://www.kaggle.com/datasets/kaushiksuresh147/adidas-vs-nike
