# (Investigate TMDb Movies)
## by (Khaled Yaseen)


## Dataset

> I investigated TMDb movies Dataset which cleaned from original data on Kaggle to analyze This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user vote counts, user rating for each movie , budgets and revenues, cast and dierctor and other atrractive information to be explored.


## After loading data from CSV file of tmdb-movies Dataset, i started assessing data visually and programatically to be cleaned and I found some limitations i need to handle it before starting analysis , for instance : 

- There are movies without names mentioned in cast or director columns but i decided to deal with it because when i searched google i found alot of them animation and documentary movies without cast , and for the rest i considered it missed data from the TMDb database and these movies have orginal titles names so why not dealing with it.
- In the columns of budget , revenue , budget_adj and revenue_adj , the are many 0 values and wierd values so i decided to convert 0 values and values less than 1000 to NAN so it will not be taken in statistcis and analysis.
- I found movies with run time more than 3 hours ! and that is unlogic for movies , but after searching google by thier orginal names i found out these are not movies but series so i dealed with it.
- I found duplicated orginal names , after searching online it is normal to get more one movie by the same name or may be it another part of the same movie in another year.
- I found one duplicated row and dropped it .


## After cleaning the data i started to pose questions and analyze data , here are some results and findings :

Finding 1 : movie success don't depend only on budget but there are many other factors .

Finding 2 : Vote counts depends on movie revenues with positive correlation .

Finding 3 : Drama has the highest genres count in a single year which happened in 2014 .

Finding 4 : Avatar is the all time highest movie in revenues which produced in 2009 .

Finding 5 : Paramount Pictures is the most company produced movies with 156 movies .

Finding 6 : Movies directed by Mark Cousins is the highest in vote average .

Finding 7 : Woody Allen is the most director had movies in TMDb with 45 movies .

Finding 8 : 2014 is the most year has movies in TMDb with 700 movies .

Finding 9 : Dram is the top genre in 2014.

Finding 10 : the viewers prefer movies with time range from 50 up to 150 minutes to watch .