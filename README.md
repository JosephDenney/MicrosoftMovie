# Microsoft Movie Market Analysis

<img src="https://cnet4.cbsistatic.com/img/sEhYa6Z6XL7iEcTGkeESiRb5ajI=/1200x675/2020/04/17/9e4fd5eb-524c-4884-88df-b39286c78c21/microsoft-1085.jpg" width = "800"/>

### Outline
* [Purpose](#Purpose)
* [Description of Data](#Description_of_Data)
* [Main Questions](#Main-Questions)
* [Summary Conclusions and Insights](#Summary-Conclusions-and-Insights)
* [Future Work](#Future-Work)
* [Thank you!](#Thank-You!)

## Purpose

#### Microsoft, the client, has tasked our firm with the analysis of film industry data in order to determine trends and provide insights into their movie making ventures. All analysis and subsequent recommendations will be key to their initial efforts at penetrating the market.

## Description of Data

### imdb.title.basics

##### This data table provides basic data from imdb that contains title, year, runtime, and genre. It can be merged with title ratings on a common column called tconst.

### imdb.title.ratings

##### Data table contains average rating as well as the number of votes that go towards those ratings. It can be merged with title basics on a common column called tconst.

### bom.movie_gross

##### A table that contains movie titles and year of release in addition to foreign and domestic box office gross earnings.

### tn.movie_budgets

* imdb.title.basics

##### This data table provides basic data from imdb that contains title, year, runtime, and genre. It can be merged with title ratings on a common column called tconst.

* imdb.title.ratings

##### Data table contains average rating as well as the number of votes that go towards those ratings. It can be merged with title basics on a common column called tconst.

* bom.movie_gross

##### A table that contains movie titles and year of release in addition to foreign and domestic box office gross earnings.

* tn.movie_budgets

##### Reveals information regarding production budgets and another look at domestic and worldwide gross sales for each film.

## Main Questions
* Question 1: Does a longer runtime indicate a lower average rating? Should Microsoft have a target movie length range for their projects? 
* Question 2: What can we learn by looking at the correlation between total gross and the average rating of a movie? Put slightly differently, does a higher quality movie demand more money at the BO?
* Question 3: What genres of films gross the most at the box office? What other insights can we gather from looking into this?
* Question 4: What genres of film provides the highest ROI?

## Summary Conclusions and Insights
* Question 1: There is no readily apparent correlation between total runtime and the average rating of a movie based on the information in the data tables. Microsoft should focus on making movies within 1 standard deviation (+/- 22 minutes) of the mean of 95 minutes and they won't have an issue with viewers thinking movies are too long or too short.

![svg](ntbook1_files/ntbook1_19_0.svg)

* Question 2: As seen in the graph below, there is only a slight correlation between average rating and the total gross of a movie. The higher quality a movie is, the more likely it is to gross more at the box office. 

![svg](ntbook1_files/ntbook1_25_0.svg)

* Question 3: Adventure, Action, Fantasy, and Sci-Fi movies are all heavily featured as the highest grossing films. Microsoft should begin by focusing on some of these more popular genres in an effort to enter the market, even if there is low ROI up front. Creating good cornerstone content now will be a great foundation for creating profits in the future.

![svg](ntbook1_files/ntbook1_35_0.svg)
![svg](ntbook1_files/ntbook1_36_0.svg)
![svg](ntbook1_files/ntbook1_37_0.svg)

* Question 4: There are some extremely high ROI's for certain combinations of genres. After establishing a solid foundation of quality content and a user base supportive of that content, we advise that Microsoft utilize less than the average for production budgets while diversifying content rapidly. A focus on finding material to develop in the Horror, Thriller, Mystery, and Sci-Fi will provide return in investment in the long run. The worst thing Microsoft could do is throw money at projects only to have them underperform without first establishing quality original content.

![svg](ntbook1_files/ntbook1_45_0.svg)

## Future Work
* A larger more complete dataset that provides more datapoints in terms of revenue and also budgets
* Further breaking down individual genres in order to target one specific genre at a time
* Creating a trend over time to spot changes in the movie making market
*

### Thank you!



