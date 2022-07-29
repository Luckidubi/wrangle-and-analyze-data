# WeRateDogs Twitter Archive Analysis by Chidubem Nwodo
 
This project involves wrangling data from WeRateDogs Twitter archive. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The datasets were retrieved from three different sources and file formats. Below are the different sources:

### Enhanced Twitter Archive
This dataset comes in a CSV file sent to Udacity by WeRateDogs to be used in this project. It contains tweet data such as tweet ID, timestamp, text, source, name, etc. The tweets found on this dataset were created on or before August 1st, 2017.

### Twitter API
This dataset contains the retweet_count and favorite_count and was obtained by querying Twitter API using the Python Tweepy library. The tweet ID from the Twitter archive dataset was used to retrieve similar tweet data in JSON format from Twitter API. 

### Image Predictions File
The Image Prediction file comes in TSV file format. It contains tweet ID, image url and top three image predictions of dogs (p1_conf, p2_conf and p3_conf) from the Twitter archive dataset using a neural network that can classify breeds of dogs.

## Insights
The following insights are presented in the act report:
- Dogs breeds with high prediction confidence in p1_conf, p2_conf and p3_conf
- Top 10 Dogs with Most Favorite Count
- Top 5 Dog breeds with highest favorite_count according to the first prediction (p1)
- Relationship between Retweet and Favorite Count
