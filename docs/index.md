# Spotify Pop Playlists Analysis

### Introduction
Hello :wave: ! Welcome to my project where I collect data about pop playlists on Spotify in the UK and present my findings. For example, did you know that one artist appears 280 times whereas the second most popular has only 33 appearances on all the pop playlists in the UK? Can you guess who it is?

### About me
I am an Econometrics student in the final year of my Bachelor at the [Erasmus University Rotterdam](https://www.eur.nl/en). I am passionate about predictive models and, since recently, webscraping. I created this project as part of the [LSE Data Engineering](https://www.lse.ac.uk/study-at-lse/summer-schools/summer-school/courses/research-methods/me204) course I followed in July 2024.


### The Data
All the variables I used were collected exclusively from [Spotify's API](https://developer.spotify.com/documentation/web-api). If you would like to replicate my results or make use of the API for your own purposes, you can check out the [instructions page](ADD THE LINK) I made. Make sure to set up your own credentials! After accounting for duplicate and missing values I was left with a list of 48 pop playlists that had 2 846 unique songs in total.

### Key findings
+ Only songs without explicit content become timeless classics
<iframe src="figures/explicit_content_per_year.html" width="100%" height="600px"></iframe>
+ Number of playlists' followers is positively correlated with the average popularity of a song
<iframe src="figures/images_plot.html" width="100%" height="600px"></iframe>
+ Finally, to answer the question from the introduction, Taylor Swift appears on all the pop playlists the most frequently by a huge margin of over 200 appearances.
<iframe src="figures/singers_popularity.html" width="100%" height="600px"></iframe>

In case you would like to know more, please check out [LINK TO OTHER PAGE]


### What's next?
One of the biggest limitations of this project is the restriction to a specific country and playlist category. Theoretical feasibility of a dataset that includes all songs on Spotify is tempting for further projects. Additionally, one could conduct a smiliar study based on [YouTube](https://developers.google.com/youtube/v3) and even go one step further and compare the popularity of the songs on these two different platforms. 

### Interested in expanding the project?
If your answer is 'Yes', feel free to connect and send me a message on [LinkedIn](www.linkedin.com/in/adam-wadolowski). 