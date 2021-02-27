# Movie Meta Information EDA :film_strip:
This project is a part of the [Data Blog](https://datares.github.io/#/datablog) at [DataResolutions](https://datares.github.io/#/).  The article published on this project, along with other articles from Data Blog, can be found on [Medium](https://medium.com/@ucladatares).

## Project Motivation/Description :mag:
The purpose of this project is to explore trends from over 40,000 feature films across the world that were released between 1995 to 2017. Our team specifically wanted to use this metainformation on movies to find possible correlations between budget, revenue, production company, and rating, as well as explore trends in location, language, genres, keywords, and cast/crew.

### Technologies Used :floppy_disk:
* Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly.Express)

## Getting Started :bulb:
1. Clone this repository (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here]() within this repo.  
3. Data processing/visualization scripts are being kept [here]()

## Data :page_with_curl:
Our dataset is [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset) from Kaggle. It has over 45,000 entries of metainformation on Movies released before and on July 2017.

## Data Cleaning :broom:
For the data cleaning process, the only csv file that had missing/nonsensical values was the movies_metadata.csv file. To clean the data, we first removed all films that did not have a title and then also removed all film that had a runtime of less than 40 minutes (for the purpose of our EDA we wanted to look at movies that followed the [definiton of being a feature film](https://en.wikipedia.org/wiki/Feature_film)). The notebook where we cleaned the the data can be found (here)[].

## Data Analysis 	:movie_camera:
For our data analysis, we looked at various sections of our data to postulate some questions:
### 1) Location/Language
Where were the movies in the dataset produced?

What languages were the movies filmed in?
### 2) Movie Evolution
Add stuff here... 
### 3) Revenue/Budget
What is the average revenue to budget ratio?

Does having a larger budget lead to more revenue?

Does having a larger budget lead to higher movie ratings?
### 4) Genres
What are the top keywords in some more notable genres?

What are the top keywords in movies overall?
### 5) Cast/Crew
Add stuff here... 

## Contributing DataRes Members :dancing_women:

|Name     | Position | GitHub Handle   | 
|---------|----------|----------------|
|Madison Kohls | Team Lead | [@madisonkohls](https://github.com/madisonkohls) |
|Bonnie Liu | Member | [@bonnieliu2002](https://github.com/bonnieliu2002) |
|Isha Shah | Member | [@ishashah146](https://github.com/ishashah146) |
|Polina Pranovich | Member | [@polinapra](https://github.com/polinapra) |
|Danielle Goldwirth | Member | [@danigold1020](https://github.com/danigold1020) |
