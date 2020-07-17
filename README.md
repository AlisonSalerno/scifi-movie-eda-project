# Microsoft Sci-fi Project - A&J Analytica

This project aims to analyze the sci-fi movie genre through data analysis to ultimately understand successes within the genre and provide insight as to what type of films should be created to capture the niche.

## The Dataset

Data was compiled from three sources: web scraping the Box Office Mojo and API requests from The Movie DB and OMDB. Our final dataset included only data on movies released in the 2000s and gross revenue in North America, as this was most relevant to the project scenario and the current market.

The 10 sci-fi sub-genres that were analyzed were: Time Travel, Supernatural, Superhero, Space Opera, Robot, Post Apocalypse, Person vs Machine, Future, Alien Invasion and Affliction as provided by one of the data sources.

Our final dataset ended up being a sample size of around 300 films — after cleaning the various datasets that were acquired and merging on title, we only wanted to analyze films for which we had all the data points (no NaN values).

## EDA - Visualizations


<img src="/images/pop.png" width="900">


<img src="/images/rev.png" width="650">


<img src="/images/revdist.png" width="1500">



<img src="/images/revstack.png" width="750">



## Conclusion

As portrayed in our data visualizations and analysis, our EDA concluded that the winning combination for success within the sci-fi movie market is a **Supernatural, PG-13 film!**

However, it must be noted that Marvel films were about 60% of the average total revenue for the supernatural sub-genre. And therefore, what we must explore next is excluding all films associated with Marvel and see how our data analysis might change.

## Contents of this project repository:

1. AJAnalyticaFinal - Final.ipynb - final project notebook visualizations & EDA
2. workingnbs folder - includes TMDB & OMDB API request code & script, Box Office Mojo webscraping scripts
The Movie DB API Request & OMDB API request.ipynb - TMDB & OMDB API request code & script
3. Microsoft Pitch - AJ.pdf - presentation slide deck 
3. data folder - all iterations of data 


      
          
          







