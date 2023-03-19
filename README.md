# Nike-Vs-Adidas
Comparing the Most &amp; Least Popular Nike &amp; Adidas Shoes of 2020

## Context
1. Background
2. Business Question
3. Data Cleaning
4. Data Analysis
5. Key Findings
6. Limitations
7. References/Software

### Background
This project has a self reporting analyzation based on data downloaded on the highest rating and reviewed Adidas and Nike shoe. Through Kaggle: the data was downloaded describing 2020 results of all of the shoe models released. The data does not include where the population came from, but the sample reviewed and rated the shoes from a 1 to 5 scale (no description of how the rating was concluded is included. As a business standpoint, this allows each company to see which shoe was the most and least liked in 2020. This is also interesting to the fact that 2020 was the first year of the pandemic, and also a time where people had more availability to shop (due to shutdowns). As a shoe business, it is important to keep track on what shoes are the most and least liked to keep track of continual model releases and collaborations.

### Business Question
With the background kept in mind, a business question was obtained: 
What are the most and least favorited shoe of 2020 from Nike and Adidas?

### Data Cleaning
The first process starts with data cleaning. The data retrieved as a csv file is downloaded onto Google Sheets. There we can look at these step-by-step cleaning process:
1. Average Ratings
* Average number of the reviews were calculated to gather more specifics and reduce the number of rows. To do this, the average function was used to find Nike's average number of reviews was 42, and Adidas was 70. Anything below was deleted.
2. Nulls & 0's
* Null's and 0's were looked over to be deleted. The only column to not delete 0's was the ratings column. Null's and 0's were found using the filter column.
3. Duplicates
* Duplicates were checked with the duplicates function. No duplicates were found.
4. Conditional Formatting
* Conditional Formatting is also another way to find any Null's, blank spaces, or incorrect data. They boxes were highlighted if there was an error or blank space. There ended up being no highlighted boxes.
5. Spelling/Grammer
* Spelling and Grammer were checked with the spelling check and the shoe names were changed to capitalizing like a title throught the ChangeSpace tool.

### Data Analysis
