## Project Summary

#### Initial Project Scope:

Determine if it is possible to predict if a Reddit post can garner above the median number of comments. The median was calculated from the total number of comments scraped on posts from May 29th to June 1st.

#### Secondary Project Scope:

Build a model to predict a posts likelihood to gain a score over 15,000. This would make the post 'Hot' by Reddit standards.

## Project Description

Creating a dataset derived from live web data: [Reddit.com](https://www.reddit.com/)
Utilizing Machine learning along with the Python requests library, multiple models were built and tested to the scopes. A Logistic Regression Model showed that a post could be inferred to meet the target amount of comments with 73% accuracy. This fulfilled the initial scope.

Using the same data, a Logistic Regression model was then used again to model a post score greater than the target. This model was able to reach 95.4% accuracy of predicting a posts score based on the subreddit and title words. This fulfilled the secondary scope.


## Project Resources:
[Reddit Hot](https://www.reddit.com/hot/)

[Plotly](https://plot.ly/python/)
