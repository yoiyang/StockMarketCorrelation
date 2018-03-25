# Finding Correlation Between Stock Price & News

One Paragraph of project description goes here

## Getting Started

Click on "FindStockCorrelation.ipynb" for results

## Introduction and Background
### Project Overview
* Introduction, background, overview
    * Introduce the background and goals of the project<br>
* Data Loading and Preprocessing
    * Load raw datasets<br>
    * Perform basic cleaning and filtering<br>
* Data Visualization - what do the stock prices look like?
    * Visualize Stock Prices and Sentiment Analysis<br>
* Data Analysis and Results
    * Statistical Analysis of Correlations<br>
* Privacy/Ethics Considerations
* Conclusion and Discussion
    * Implications of results<br>
    * Possible future projects<br>

***
We want to see how positive/negative keywords in news titles correlate with the stock price of that company.

Our hypothesis would be that a positive sentiment in in news titles would correlate with an increase in stock price, while negative sentiment in the news would correlate with a decrease in stock price. We predict that there will be a strong correlation between the two because we believe that the news encompasses many of the factors surrounding a company that then directly affects investors decisions on whether to purchase or sell.

We first looked at correlations between finance news headlines related to the company and company stock price day by day and limited our analysis to two companies: Amazon and Nike.

Next, we also looked at correlations week by week and increased the length of time that we were running our analysis over by gathering 8,000 instead of 2,000 headlines. 

Finally, we broadened the scope of our project by looking at how more general news headlines correlates with the Dow Jones index.  

## Data Description

### Overview

We pulled our data based on two categories: <br\>
1) Data from 2 private companies (Amazon and Nike)<br\>
2) Data from the Dow Jones Index. 

The goal was to get two different data sets for each. The first data set consists of news about the company/DJI and the date the article was published. Basically these data sets consist of tables with two rows: Data and Headlines. The second data set consists of stock price and the date. We found historical data for each of the companies mentioned above and the Dow Jones Index from Yahoo Finance. For the private companies we pulled data for the last 2 years (6 years for DJI). WE did not have to scrape the data from their website since we were able to download the cvs file.

We ended up with six different tables, two for each company/index(stock price and news headlines).

### Process

We started by importing packages that will help us get/visualize data. The packages we used are pretty much the ones that were taught to us on the assignments. Among the packages we used is BeautifulSoup to be able to scrape the web, Matplotlib and Seaborn for visualization, and Pandas to store our data. 

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors:

Yang Liu, Gustavo Carbone, Alec Flowers, Andy Kong, Christopher Chen, Christopher Yoon

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Sentiment Neuron API: https://modeldepot.io/afowler/sentiment-neuron/overview
* Raddit, Financial Contents
* etc

