# Netflix-Show-Analysis
A repository for analysis of Netflix show reviews based on a dataset obtained. 
--- 

* Dataset : [https://www.kaggle.com/chasewillden/netflix-shows](https://www.kaggle.com/chasewillden/netflix-shows)
* My contribution on data analysis on kaggle : [https://www.kaggle.com/jyotsnasweedle/netflix-show-analysis](https://www.kaggle.com/jyotsnasweedle/netflix-show-analysis)


The given dataset consists of Shows and Movies from the year 1940 to 2017, available on
Netflix, a worldwide popular video-streaming application. Shows rated from “_G_”(General
Audiences) to “_R_”(strong violence, sexual content and adult language) are all included, attracting
a wide-range of audience. Details included about each show are rating, rating description, rating
level, release year, user rating score, user rating score, user rating size.

### Problems found in the dataset
There are several missing values in some of the rows. Few rows are repeated. Details regarding Genre are not
provided making it difficult to categorize the shows according to these values. A couple of
column names are misplaced.

### Solutions implemented
* Basic data cleaning(remove repeating rows).
* Add additional columns(Age restriction, genre)
* Fill in missing values in rows based on most generic values given(missing rating
  description based on most used description for each rating).

### Things to Analyse
* Trending genre for movies each decade based on show genre.
* Trending rating for shows and movies in each decade.
* What is common among high rated shows/movies?
* Do popular shows or movies have mature content?
* Ratio of popularity for general vs Age restricted movies all together. 
