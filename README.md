# IMDB-descriptor VS. Gross-earnings
CSE6242 Data Visual&amp;Analytics Project

## Note: This project involves:
Part 1: getting data ready for analysis and doing some preliminary investigations. 
Part 2:  modeling and predictions on the same dataset, and will be released at a later date. 

## Data
In this project, I explored a dataset that contains information about movies, including ratings, budget, gross revenue 
and other attributes.
The file movies_merged contains a dataframe with the same name that has 40K rows and 39 columns. 
Each row represents a movie title and each column represents a descriptor such as Title, Actors, and Budget. 
I collected the data by querying IMDb API (see https://www.omdbapi.com) and joining it with a separate dataset of movie budgets 
and gross earnings (most unknown). The join key was the movie title. 
This data is available for personal use, but IMDb terms of service do not allow it to be used for commercial purposes or 
for creating a competing repository.

## Objective
The goal is to investigate the relationship between the movie descriptors and the box office success of movies, 
as represented by the variable Gross. This task is extremely important as it can help a studio decide which titles 
to fund for production, how much to bid on produced movies, when to release a title, how much to invest in marketing and PR, etc. 
This information is most useful before a title is released, but it is still very valuable after the movie is already released 
to the public (for example it can affect additional marketing spend or how much a studio should negotiate with on-demand 
streaming companies for second window round streaming rights).
