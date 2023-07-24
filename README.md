# Phase 1 Project

* Student name: Abdihakim S Mohamed 
* Student pace: Part Time
* Scheduled project review date/time:
* Instructor name: Maryan Mwikali

## Project Overview

In this project, I will provide recommendations to Microsoft on the types of movies they should produce for the launch of their movie studio. To make these suggestions, I will analyze historical data from IMDB, Box Office Mojo, and The Numbers. Specifically, I will focus on the genre of movies that perform well at the box office and perform well in both Domestic and Foreign market.

Measuring the success of a movie can be done through various metrics, but in this project, I will primarily focus on financial metrics that can be objectively measured, such as movie gross and Genre. By identifying common attributes among the top-grossing movies, we can offer valuable insights on the type of film Microsoft should pursue.

Additionally, I will explore the relationship between genre, ratings, and movie gross.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `zippedData` I used datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

From the data above I used the the data below.

* imdb.title.basics
* imdb.title.ratings
* bom.movie_gross

## Methods

* I loaded the data using Python modules to read the data.

* Merging of the data.

* Reviewed the data to understand inconsistencies.

* I cleaned the data by dropping duplicate columns for ease understanding.
  
* Visualized the data for insights.


### Results
* Bar plot analysis on Domestic gross against genres
![Barplot_Dom](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/133906913/fe60dc4a-b3eb-4b9c-9694-db8dccd07b44)

* Bar plot analysis on Foreign gross against genres
![BarPlot_For](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/133906913/d7c30c4a-e338-4e99-a704-f1ab7ac88f5e)

* Movies released per year
![CountPlot](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/133906913/adfa2be9-b0f0-4655-b868-ec84613afbcb)

* Relationship between ratings and revenue generated
![ScartterPlot](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/133906913/b07f2a93-7d13-4040-b13a-0e9591d56da4)


## Conclusion

* The domestic and foreign gross earnings exhibited different trends, with the foreign gross consistently showing an upward trajectory, while the domestic gross experienced fluctuations.

* The genre analysis highlighted the strong performance of Action, Adventure, and Sci-Fi genres in both domestic and foreign markets, indicating their popularity and profitability. These genres are promising investment options for Microsoft Studio in its movie production ventures.

## Reccomendation

* Genres like Action, Adventure, and Sci-Fi perform in both domestic and international markets, Microsoft Studio should prioritize investments in producing more movies within these genres to optimize revenue generation.
  
* As foreign gross earnings demonstrate a consistent upward trend, Microsoft should continue to target and expand its presence in international markets.

