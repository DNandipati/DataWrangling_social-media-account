# Data Wrangling a Twitter Media Account - "WeRateDogs"
> by Deepak Nandipati

## Project Overview
The purpose of this project is to utilize data wrangling and cleaning skills to sort tweet archive of Twitter page "WeRateDogs" and by username @dog_rates. WeRateDogs is a page that primarily posts cute images of puppies and dogs, they are most famous for their rating system where dogs are given a rating almost always above 10/10. Each dataset I gathered contained over 2000 rows of information, with numerous variables.

![WeRateDogs3](https://user-images.githubusercontent.com/44736627/60307563-2b378d00-9913-11e9-9874-ea9b3428c558.jpg)
![WeRateDogs2](https://user-images.githubusercontent.com/44736627/60307792-10b1e380-9914-11e9-9564-c7d0218988fa.jpg)

## Gathering Data
- **Twitter archive file:** File was provided from Udacity as "twitter_archive_enhanced.csv"
- **Tweet image predictions:** File was hosted on Udacity's servers and was pulled from server using Request function. URL is as follows: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv
- **Twitter API and JSON:** Acquired the consumer key/secret along with access token and secret from Twitter Dev. Using tweepy function, data was extracted to this notebook.

## Technologies Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key findings from analysis
- The top breeds of dogs that are posted in 'WeRateDogs' are Labrador Retrievers, Golden Retrievers, Pembroke, Chihuaha, Eskimo, and toy poodle in that order. 
- Puppers are the most posted in page, followed by doggo, puppo and floofer
- Most common rating for a dog is 12/10, 11/10, 10/10, and 13/10. However nothing greater than 14/10, there are some exceptions for dogs that got less than perfect. 
- Since the beginning of ‘WeRateDogs’ which was of November 15, 2015 it has been shown that the traffic of page increased rapidly. Along with the traffic, it also appears that the ratings of dogs have got better ever since. With the latest data in the archive of July 29, 2017, the graph below shows the slight increase in ratings. 
- Page has been drastically increasing in retweets and favourites over time. Some of the posts have even gone viral such as the post on June 4, 2016 that was of a Siberian husky blowing bubbles under water. This 30-second video grasped the world’s attention and has kick-started the
surge of traffic on page. The original post at time of dataset consisted of 60,989 retweets and 119,787 favourites; here is a screenshot of the post: <br><br>
URL: https://twitter.com/dog_rates/status/739238157791694849?lang=en
![WeRateDogs_Viral](https://user-images.githubusercontent.com/44736627/60310547-6a6cda80-9921-11e9-8426-3b3b41740309.jpg)



## Files Used
wrangle_act.ipynb| tweet_json.txt| twitter-archive-enhanced.csv| image-predictions.tsv| config.py (private)
