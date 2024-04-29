# Movie Lens
### https://app.powerbi.com/groups/51b949dc-83cf-440c-a95e-50da72443c4c/reports/6c40ee63-4e75-4a48-b57b-33efd0fdd145/ReportSection?experience=power-bi
## In order to create the "Movie Lens" edition, the challenge lies in effectively analyzing and presenting a wealth of information about movies from a bygone era. The core issue is understanding the characteristics of these classic movies, user interests, and the relationship between user demographics and movie ratings. Without clear visuals, it's difficult to identify patterns, draw meaningful conclusions, and engage the audience on a deeper level. This report provides a detailed analysis of the classic movies that were released till 2000.

### Steps followed 

1. The three CSV files were loaded into the report, with the first row values treated as headers.
2. To prevent circular relationships, I reviewed and adjusted the relationships between tables in the data model.
3. Data cleaning and transformation were performed to remove redundant columns.
4. Each page in the report was equipped with slicers and navigation actions for easy exploration.
5. The resulting report presents the data effectively, allowing for intuitive interaction and analysis.
  
6. Create a Card visual to show the total number of movies released and another Card visual to display the total number of distinct Genres.

7. Utilize a Card visual to represent the number of users, and a Donut chart to visualize the gender distribution among users, calculated using COUNTROWS.

8. Use an Area chart to highlight average ratings across movie genres, based on gender. Create a new Genre group to combine similar genres, then visualize using this grouping.

9. Develop a Gauge chart to display the average rating. For movie distribution across genre groups, use a Stacked bar chart. Create a DAX measure for the average rating and a Decades group for the Year column.

10. Employ a Clustered column chart to visualize user distribution across age groups based on gender. Utilize a Map chart with bubbles to indicate user locations. Classify users into age groups and impute missing ages.

11. Use a Matrix visual to visualize average ratings across professions and age groups. Include slicers for decade and occupation.

12. Create a Treemap to visualize the Top N Movies and Genres, with Occupation and User Age slicers. Utilize buttons to toggle between the two charts using bookmarks.

13. Develop a Scatterplot between user age group and average rating, with bubble size indicating the number of users. For movie average ratings across years, use a Bar chart with analytics features to show average ratings across genres. Include slicers for decade and genre.

Ensure to include relevant slicers, filters, bookmarks, formatting, and navigation features to enhance the report.
