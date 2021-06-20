## Quantitative Trading
Learn the basics of quantitative analysis, including data processing, trading signal generation, and portfolio management. Use Python to work with historical stock data, develop trading strategies, and construct a multi-factor model with optimization.<br>

### Topics
In this first part of the nanodegree we cover the following topics:

- **Basic Quantitative Trading**: Learn about market mechanics and how to generate signals with stock data. Work on developing a momentum-trading strategy in your first project.

- **Advanced Quantitative Trading**: Learn the quant workflow for signal generation, and apply advanced quantitative methods commonly used in trading.

- **Stocks, Indices, and ETFs**: Learn about portfolio optimization, and financial securities formed by stocks, including market indices, vanilla ETFs, and Smart Beta ETFs.

- **Factor Investing and Alpha Research**: Learn about alpha and risk factors, and construct a portfolio with advanced optimization techniques.

- **Sentiment Analysis with Natural Language Processing:** Learn the fundamentals of text processing, and analyze corporate filings to generate sentiment-based trading signals.

- **Advanced Natural Language Processing with Deep Learning:** Learn to apply deep learning in quantitative analysis and use recurrent neural networks and long short-term memory to generate trading signals.

- **Combining Multiple Signals:** Learn advanced techniques to select and combine the factors you’ve generated from both traditional and alternative data.

- **Simulating Trades with Historical Data:** Learn to refine trading signals by running rigorous back tests. Track your P&L while your algorithm buys and sells.

### Projects
- **Project 1:** Trading with Momentum
- **Project 2:** Breakout Strategy
- **Project 3:** Smart Beta and Portfolio Optimization
- **Project 4:** Multi-factor Model

#### P1: Trading with Momentum

This post in Udacity's Knowledge Base - https://knowledge.udacity.com/questions/218044 should be helpful.
This article about alpha values and p values - https://www.thoughtco.com/the-difference-between-alpha-and-p-values-3126420 may help you . . .
You could also refer here to learn more: https://towardsdatascience.com/demystifying-confidence-interval-and-margin-of-error-e01c1bc8760b

To learn more about the use of vectorization here - [a key element to high-speed pandas.](https://engineering.upside.com/a-beginners-guide-to-optimizing-pandas-code-for-speed-c09ef2c6a4d6)

#### P2: Breakout Strategy

Implementing the required functions using a Jupyter Notebook. Please find a few links below that will deepen your learning on this topic:

- In [this article](https://www.statisticssolutions.com/kolmogorov-smrinovs-one-sample-test/) you could learn more about the `ks test`.
- In [this](https://www.orbex.com/blog/en/2018/01/trading-strategy-weekly-high-low-break) blog you can find material to understand the `breakout strategy` better.
- [This article](https://medium.com/better-programming/lambda-map-and-filter-in-python-4935f248593) shows how to apply `lambda functions` in Python.
- [This article](http://www.psychwiki.com/wiki/How_do_I_determine_whether_my_data_are_normal%3F) can be used to find out if a `histogram` is normal and how to find if it’s skewed or not.
- [Here](https://tradingstrategyguides.com/best-breakout-trading-strategy/) is some more info on `breakout strategy`

**Following are some good reads:**

- [List of code, papers, and resources for AI/deep learning/machine learning/neural networks applied to algorithmic trading](https://github.com/cbailes/awesome-deep-trading)
- [Machine Trading: Deploying Computer Algorithms to Conquer The Markets](https://github.com/gudbrandtandberg/CPSC540Project/blob/master/Machine Trading: Deploying Computer Algorithms to Conquer The Markets (Ernest Chan 2017).pdf)
- [Quantitative Trading: How to Build Your Own Algorithmic Trading Business](https://www.myquant.cn/uploads/default/original/1X/4c7037365a4bf1623734c1c899baed7855061ace.pdf)



#### P3: Smart Beta and Portfolio Optimization

You may be interested to play around with the concepts you learned in this project with more recent stock data. The Pandas_Datareader library has many stock data providers, but the 'yahoo' provider is **free**. 

Probably don't want to use free data when making actual trading decisions, obtaining free data will allow you continue your learning and make things even more fun! Here's a quick little example of how to read yahoo finance stock data using Pandas Datareader:

You can read [more about Pandas Datareader Here](https://pandas-datareader.readthedocs.io/en/latest/index.html#)

#### P4: Multi-factor Model

