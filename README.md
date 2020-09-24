# Twitter Sentiment Analyzer

The following program is designed to parse desired number of tweets which contains text mentioned in query.txt file and then perform sentiment analysis on them. It also counts a few entities such as likes, retweets, etc and saveall the information in a Pandas Dataframe.

## Usage
 
1. When running the script through console please paste your twitter app credentials in the file named 'credential_file.txt'(every credential should be separated by newline and in order: consumer_key, consumer_secret, access_token, access_token_secret) and the search query for tweets in a file named 'query.txt' in single line.

2. You can use a different file name as well but then you have to pass those file names as arguments while running script as:
```bash
python get_tweets.py --credential_file <your credentials file name> --query <your query file name> --num <number of tweets you want your script to parse>
```
*NOTE : Everytime before running the script, please move the old .json file somewhere other than current working directory, so that any desireable data could be preserved from your last search.

## Links

Tweepy : [Anaconda](https://anaconda.org/conda-forge/tweepy), [Documentation](http://docs.tweepy.org/en/latest/)
