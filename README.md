# TMDB-movies-analysis


## Introduction
I chose the TMDB-movies to do an analysis on it. I wrote this summary after I have finished the analysis part. I really enjoyed doing this project and I hope I did well!.

Through the analysis step, starting with loading the data and discovering the dataset features and datatypes thinking about the most important part in data analysis (What can we conclude or benefit from this data) and I came up with several questions and I picked two questions.

I removed many unuseful columns in my case or the columns that not related to the two questions I have picked. Also, these columns lack a lot of rows so getting rid of them was a good idea.

The features that I used are:
budget

`release_yea`

`vote_average`

I have 5 questions but I'll pick 2

The questions are:

1. Are movies with larger budget receive better ratings?
2. Are the cast effects on the popularity of the movie?
3. Which genre makes more revenue?
4. Which decade had the best movies ratings?
5. Is the director play important role in the quality of the movie?

These questions that I'm going to answer:

**1. Are movies with larger budget receive better ratings?**

**4. Which decade had the best movies ratings?**







All the impementions and analysis exist on **TMDB-movies-Talal-Q.ipynb** file


## 
In conclusion, I have examined several features, their properties. in the first section, I decided which features I need to use and which features must be dropped. Then, I made some quick exploring between the features and visualize the results.

In the next steps and In preparing the data for the analysis I found that the budget's feature has unreasonable budget values for movies. I decided to remove any budget value under 5000. After that, I split the data into 2 datasets one for the data that greater or equal than the budget's mean and the other for the data below the budget's mean.

Finally, I concluded the project by plotting the results for the two questions and put appropriate comments for each.

### Findings
For **Q1**
1) Large budget movies don't mean necessarily the movie will have high rates.

For **Q2**
1) Old movies have a higher average rate than current movies.

2) With every decade the movies ratings decreases.\

3) In the next decade, the average rating is expected to reach 5.5

## limitations
The first thing I have encountered the missing data are huge in some columns. There Are questions that I wanted to work on but unfortunately, the data didn't help and if I worked on them mostly I'll end with inaccurate analysis. After analysing and exploring the data features I picked those two questions.

In the second question, it seems the movies not good as before, this is because in the current decade the number of films shown is much more than in previous decades and they show regardless of quality.
