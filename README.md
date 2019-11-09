# Data Wrangling using Python
# WeRateDogs-Data-Wrangling-using-Twitter-API

**Install**
This project requires Python 3.x and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [tweepy](https://www.tweepy.org/)
- [json](https://docs.python.org/3/library/json.html)

You will also need to have software installed to run and execute an iPython Notebook

Install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook wrangle_act.ipynb
```  
or
```bash
jupyter notebook wrangle_act.ipynb
```

This will open the iPython Notebook software and project file in your browser.


**About the repo**
The repo contains a .ipynb file that does the following:
- Use Tweepy to query Twitter's API for data included in the WeRateDogs Twitter archive, assess and clean dataset by pulling dog tweets in order to create interesting and trustworthy analyses and visualizations. 

- Once the twitter data will be pulled, I intend to use Data wrangling techniques to gather, assess and clean data, using manual and programmatic assessment. I will be using multiple Python libraries and functions to do the entire data wrangling exercise

- Retweet count and favorite count will be omitted using duplicated() function of Python. There wont be any interaction with Twitter accounts. The data will just be pulled to do data wrangling and create visualizations for performing useful insights

- Tweets and Twitter content will be saved in text file to create a pandas DataFrame. All the data will be displayed at row level

The repo also contains:
- Wrangling report on how the wrangling effort was undertaken
- Report on Insights and VIsualizations extracted after the data cleaning exercise was completed
