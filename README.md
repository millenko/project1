![logo_netflix_blue 7](https://images.ctfassets.net/y2ske730sjqp/1aONibCke6niZhgPxuiilC/2c401b05a07288746ddf3bd3943fbc76/BrandAssets_Logos_01-Wordmark.jpg?w=940)

# Project 1 | Netflix

<br>

## Introduction

Welcome to my first, and hopefully not the last, independent project.
<br>
This project is data analysis of a dataset of choice.<br>
This fact made it a blessing... in heavy disguise.<br>
It was the liberty of having a choice to make, but not knowing how a choice is made.<br>
My motivation for this project was to prove myself as a single contributor to this bootcamp as much as I proved myself to be a teamplayer.<br>
When you're riding solo, all eyes are on you. You can't hide behind others, you're the only one to take all the blames, or credits.<br>

## Data analyst
- Milenko Rosić

## Installation & setup
- Fork this repo
- Clone it to your machine

### Required environment
- see the requirements.txt

## About the dataset
The dataset used in this analysis is [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) created and regularly updated by Shivam Bansal.<br>
Netflix is one of the most popular media and video streaming platforms.<br>
They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally.<br>
This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.<br>
The dataset is under the CC0 licence as Public Domain.<br>
[The original dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) is in .csv file format, loaded into a Jupyter Notebook for analysis in Python.

### Problem statement or hypothesis
There were none. This analysis was purely descriptive and exploratory.


## Understanding the data
I mostly used Pandas built-in functions such as describe, head, info, unique, to familiarize myself with the data.
<br>
Though the dataset initially looked of promising size for a safe and easy analysis, it turned out to be overly simple.
it was a promising number that the dataset is well-fulfilled, the dataset proved to be rather dirty.

### Formatting
I used Pandas built-in functions to format the data, to reach clarity and needs of the analysis.<br>
The biggest stepping stones:
1. monotonous datatype landscape - only 1 value was numerical,
2. the most important columns had big gaps in terms of missing values,
3. and they also had one-to-many relationships.

### Data Description
- "show_id" : a sequence of numbers in ascending order, with prefix "s".
- "type" : content-categories, "Movie" and "TV Show".
- "title" : name of the content.
- "director" : full name of a person who directed the content.
- "cast" : full names of some of the stars of the content.
- "country" : country or countries where the content was produced.
- "date_added" : the date the content was published on Netflix. Original format of the values in the column are "Month DD, YYYY".
- "release_year" : content release year.
- "rating" : content rating for the US market; provides information about the appropriate audience of the content.
- "duration" : timelength of the content, denoted in minute formats or number of seasons.
- "listed_in" : genre/s of the content.
- "description" : content-plot.

### EDA methods
I utilized Python libraries Seaborn and Matplotlib to explore and visually present the statistical findings.
<br>

#### Visualisation:
- Created pie charts to illustrate the distribution between variables, and values within the variables.

## Conclusion
It was surprising to learn that movie content dominates Netflix, and not the tv shows.

### Acknowledgements
- Don Nacho
- Simi
- Pedro (though we're still not sure if that's a real person or AI)
- Shivan Bansal, for having created the dataset
- Alev Yildirim, for having given me the dataset

### Happy end?
