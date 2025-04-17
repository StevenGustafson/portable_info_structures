# I3 Assignment Example App That Visualizes Data

## Overview
This assignment is about interacting with structured information for a purpose, either to visualize, analyze, predict, or automate something. Be creative, keep it as simple or make it as complex as you like. Start small to finish the assignment, but have fun and then add something you are interested in learning to it. The information could be structured as JSON, CSV, HTML, or something else. The code below is for making an API call to financial data about the stock market and companies that own those securities (stocks). APIs tend to provide more well structured information.

## Instructions
The repo contains a Python Notebook file that can be opened in Google Colab. Download the file and import into Colab, copy and paste the code, or click the link when you view the file in Github that says 'open in Colab'. The file will pull data from SEC Edgar API and visualize data about Apple. 

## Code Example

```google markdown formatting github```

## Possible ways to extend
There are many things you can do with this code. You can visualize a different data field about Apple. You can aggregate data or integrate data about a company using a different EDGAR endpoint or another API. You can loop through several company CIKs and get data and do something with that. Be mindful of making too many API requests using a for loop, this could cause you to exceed a rate limit by the endpoint and temporarily block access.

## Other ways to use this example
You can find another API to get data and visualize or analyze it in some way. You could use data, like assets over time, to make a simple regression function that models the timeseries to predict future or missing values. You could identify a few different companies, get some data about them and try clustering them. Or, you could create a dataframe of different data about some companies and use an LLM endpoint to chat with the data - basically send the data in your chat request and ask something about it.
