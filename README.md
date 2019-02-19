# Scraping Twitter Lists Using Google Search and Tweepy
Author: Anthony Baum

Contact email: wxbaum@gmail.com

The primary function of this script is to bulk-identify a set of Twitter users that match given search keywords on Google. 

By using a Google search for user-created Twitter lists, we can quasi-crowdsource a large number of accounts by matching lists to the keywords being searched for. Using Tweepy to access the user objects of each user in the lists, a dataset of users tailored for any application can be generated with relative ease. 

Note that this script will take a few minutes to run to prevent Google or Twitter locking us out for making too many requests in a short time period. 

To utilize the script you will need access to the Twitter API. Set up an account and project with Twitter Development here: https://developer.twitter.com/en/apply-for-access. 

No Google search authentication is required, as the googlesearch Python module it utilized. Module repo and documentation available here: https://github.com/MarioVilas/googlesearch




