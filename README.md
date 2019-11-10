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

In a terminal or command window, navigate to the top-level project directory `WeRateDogs-Data-Wrangling-using-Twitter-API/` (that contains this README) and run one of the following commands:

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
- Used Tweepy to query Twitter's API for data included in the WeRateDogs Twitter archive, assess and clean dataset by pulling dog tweets in order to create interesting and trustworthy analyses and visualizations. 
- Once the twitter data was pulled, I used Data wrangling techniques to gather, assess and clean data, using manual and programmatic assessment. Multiple Python pandas and NumPy libraries and functions were used to complete the data wrangling exercise
- Report on Insights and VIsualizations were extracted after the data cleaning exercise was completed

**Note** - Retweet count and favorite count were omitted using duplicated() function of Python. There wont be any interaction with Twitter accounts. The data will just be pulled to do data wrangling and create visualizations for performing useful insights

