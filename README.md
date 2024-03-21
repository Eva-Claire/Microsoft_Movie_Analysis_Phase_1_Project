![film crew](film_crew_icon.jpg)

# MOVIE ANALYSIS FOR MICROSOFT CORPORATION



## OVERVIEW

This project was aimed at helping Microsoft break into the movie industry by obtaining much needed insight into what makes for a great movie. I looked into a wide variety of films produced over the years to see what makes some perform better than others.

From my analysis, the following were the greatest determiners of a movie's success:

* Genre: Different genres appeal to different audiences and certain genres tend to perform better at the box office than others. Genres such as action, adventure, drama and comedies tend to have a wider appeal and thus generate more box office revenue.

* Release Timing: The time of year a movie is released directly impacts its box office performance. Movies released during peak seasons or strategically timed to coincide with holidays or special events tend to perform better.

* Budget: The effectiveness of a movie's production, marketing and promotional campaigns significantly influence its box office success. A larger budget enables the best production methods and teams and wider promotion tours for a movie leading to higher ticket sales.



## BUSINESS UNDERSTANDING

Microsoft is a multinational technology company headquatered in Redmond, Washington,USA. They are well known for their software products and services and are now looking to dive into the movie making scene and compete against industry heavy hitters. Microsoft have decided to create a new movie studio but they lack proper insight as to what makes great movies,GREAT! The goal is to analyse some of the most successful box office movies and advice the head of Microsoft's new movie studio on what they need inorder to produce successful films. 


## DATA UNDERSTANDING

The following were the sources of data I chose for this project:

* ImDb movie database - This is an internet movie database accessible via SQLite3 that contains two tables relevant to my analysis. The first table is the movie basics table that contains the following data: movie id, original and primary movie title, start year, genre, runtime in minutes. The second table is called movie rating and it contains the following data: movie id, average rating and number of votes a movie has garnered.

* Box office mojo (BOM) - BOM is a popular box office data website that analyzes and tracks performance of films in theatres. This dataset contains movie name, domestic and foreign gross, year of production and the studio that produced the movie.

* The Numbers - This website conducts financial analysis of films and tracks box office revenue. This particular dataset contains data on movie production budgets, domestic and worldwide gross revenues and movie release dates. 



## DATA PREPARATION


I carried out both descriptive and quantitative analysis on the data and came up with appropriate illustrations of the same. The goal was to identify factors that determine the performance of successful box office movie and give insightful recommendations to Microsoft.
I began by importing the modules I would require for the entirety of the project. I removed duplicates and null values from the data and did away with unwanted columns and rows. After cleaning all my data I merged into one informative table and proceeded to carry out my analysis.


## DATA ANALYSIS


The focus of my analysis would be on three key factors that I concluded were directly related to a movie's success as I went about cleaning and normalizing the data. These three factors were movie genre, the release time(month and day of the week) and the production budget. 


## RESULTS

### Genre
    
![png](output_97_0.png)
    

Action movies were the most produced genre according to the dataset. Other popular genres were drama, comedy and adventure movies. 


![png](output_103_0.png)
    
Action and adventure films continued to stand out by raking in the highest gross profits compared to production budget. 


### Release day and month

![png](output_107_0.png)
    

Most releases occured in March and December with the lowest release months being July, January and May.


![png](output_109_0.png)
    

Most movies are released on friday because studios aim to take advantage of the weekend box office. This gurantees a larger audience as majority of people have free time from friday evenings all through the weekend to watch new releases.

### Budget


![png](output_114_0.png)
  
  
The heatmap showed a somewhat strong positive correlations between production budget and foreign and domestic gross. Gross profit had a strong positive correlation with domestic and foreign gross unsurprisingly. 


![png](output_116_0.png)
  
  
The stacked bar chart showed that action movies being the most produced genre had highest production budgets and in turn made more money in both domestic and foreign markets. 


![png](output_119_1.png)
   
   
The regression plot showed that lower production budgets translated to lower worldwide gross earnings in most cases and the higher the worldwide gross, the higher the potential return on investment and vice versa.


![png](output_121_0.png)
    

Action and adventure films show alot of promise in terms of how much they gross worldwide.

![png](output_123_0.png)
    

The median production budget of family movies appeared to be the highest followed by animation, action and adventure movies. The boxplot also showed that the family genre had the highest interquartile range. 


![png](output_125_0.png)
    
    
From this plot we can conclude that family movies appear very promising in terms of worldwide gross as they also present a high median value in comparison to the other genres. Action and adventure films follow closely.


![png](output_127_0.png)
    

The box plot with outliers shoowed that action and adventure genres did possess a number of outliers and so did all the other genres except for family, animation and fantasy. 


![png](output_130_0.png)
 
 
The line plot showed the top 5 action movies between 2015 and 2019 by world gross.


![png](output_131_0.png)
    

The line plot showed the top 5 adventure movies between 2015 and 2019 by world gross.


![png](output_132_0.png)

    
The line plot showed the top 5 drama movies between 2015 and 2019 by world gross.

## CONCLUSIONS

Microsoft stands a great chance at breaking into the movie industry by taking into consideration these three factors:

* Genre - The top 5 most produced genres in the movie industry are acttion, drama, comedy, adventure and biographies. These depict genres that have been tried and tested as being popular with a wide variety of masses. If microsoft focuses its attention on these genres they are guaranteed to successfully attract audiences the world over and break into the movie scene in an earth-shattering way.

* Release day - Microsoft should aim to release their movies on fridays for maximum success. Friday being the end of the week makes it the most ideal period for moviegoers to visit theatres and watch new movie releases. Many movie studios strategically choose Fridays for releases to maximize box office earnings. This is because movies have more time to attract larger audiences and generate higher revenue. By creating buzz in the days before the day of release, a movie is guaranteed great success.

* Release month - The period between March to June is very popular with movie releases and according to research, many critically acclaimed films that win at the Oscars are released in March and April. This can be a contributing factor to Microsoft's success. May to August also witnesses a rise in movie releases as movie studios count on the summer months to take advantage of the larger audience and school vacations. Summer break also means that families have more opportunities to go out for entertainment. Family films have a better opportunity when released from late November to December as this is the period of holidays such as Thanksgiving, Christmas, and New Year. The festive spirit means that families have a higher likelihood of going to movies together thus making it a good time for family-oriented films.

* Budget - My analysis has shown that the more money that is put into producing a film, the more money there stands to be made in terms of domestic and foreign revenue. Less investment into producing a film will mean that production quality will be compromised. A higher budget will enable a movie studio to enlist top-tier actors, invest in high-quality special effects and CGI, create elaborate sets and producee captivating cinematography for its audience. This will have the domino effect of attracting more viewers. A larger budget will also enable effective marketing and promotional campaigns creating buzz and generating anticipation among audiences leading to higher ticket sales across multiple theaters both domestically and internationally. 

## RECOMMENDATIONS

I would recommend that Microsoft do the following:
* Produce an action film preferably a superhero movie seeing as three of the five top grossing action films worldwide between 2015 and 2019 are superhero movies. They should aim for a production budget of between 150 to 300 million dollars and aim to release the movie between March and June. This is the best time period for a demographic that enjoys superhero action films. Microsoft should also enlist a top-grossing superhero movie director for their premier film. As worlwide gross income numbers are to go by, they should work with the Russo brothers (Anthony and Joseph Russo) who are the directors of the movie Avengers: Infinity War.

* Microsoft should also aim to produce an adventure movie going by budget to worldwide gross income ratio. The top three adventure movies between 2015 and 2019 are animation comedy adventure films that appeal to younger and older audiences. This movie should be released between May and July during school summer breaks guaranteeing a massive audience of kids and parents alike. The production budget should be set around the median which is between 70 to 100 million dollars. Microsoft should also aim to enlist top animation producers such as Pierre Coffin who has directed both Minions and Despicable Me, Kyle Balda from Minions or Andrew Stanton from Finding Dory. 

* Microsoft can also produce a romantic drama going by 3 of the top 5 drama movies in the 2015 to 2019 time period. Two of these are the Fifty Shades franchise so Microsooft can enlist top directors proficient in the genre. Some of them are James Foley from Fifty Shades Freed and Morten TTyldum from the movie Passengers. The production budget should be between 50 and 100 million dollars.


## NEXT STEPS

* Invest in the best producers, screenwriters, actors and cinematographers per genre in the recommendations.
* Get the best suited sound, design, costumes and art crew for each movie.
* Invest in the highest quality sound, music, visual and special effects software and hardware in the market to ensure the best quality of production.
* Enlist the best PR and marketing firms to boost advertising, marketing and distribution of their upcoming films.
* Research on the feasibility and viability of producing a family film.


## REFERENCES

<a href="https://www.freepik.com/free-vector/film-crew-movie-production-studio-staff_29314759.htm#fromView=search&page=1&position=8&uuid=1c379553-fabc-44ff-a8ab-f4c3d5519362">Image by upklyak on Freepik</a>


### info

Detailed version can be found in my github repo:
[github](https://github.com/Eva-Claire/Microsoft_Movie_Analysis_Phase_1_Project)
[email](evaclaire.wamitu@student.moringaschool.com) or 
[email](evamunyika@gmail.com)
