---
title: Investment Portfolio Dashboard (BigQuery + Looker)
header_type: hero
header_img: https://coloradowealthgroup.com/media/blog/image/image_33.jpg
tags: [investment, portfolio, stock]
---

I used to track my investments on [spreadsheets](https://www.junyichong.com/projects/investment-portfolio), but as my portfolio grew and I opened more brokerage accounts, maintaining these spreadsheets became increasingly cumbersome. To reduce the hassle and centralize all my investment data, I decided to build an investment portfolio dashboard using Looker and BigQuery. This dashboard now allows me to analyze my investment data from my first stock in 2020 to the latest updates, providing an intuitive way to visualize trends, evaluate asset allocation, and track cumulative performance.

<br/>

##### Using BigQuery for Data Analysis

[Github link](https://github.com/junyichong/investment-portfolio-bigquery)

The foundation of this project was setting up BigQuery to handle all the data analysis. I started by gathering all my previous transaction data and historical stock price data into a Google Sheet, which acted as a central repository for my investment records. BigQuery was then configured to read and analyze this data, enabling me to perform complex calculations and generate meaningful insights.

Using SQL in BigQuery, I built data models to calculate essential metrics such as cumulative costs, realized and unrealized gains, and asset allocation percentages. By leveraging BigQuery’s ability to set up scheduled queries, I automated daily updates, ensuring that my analysis always reflected the latest information. 

<br/>

##### Visualizing Data with Looker

Once the data was ready, I used Looker to create an interactive and visually engaging dashboard (in dark mode of course). Even though the functionality is not as robust as Power BI, Looker’s flexibility allowed me to design dynamic charts and reports tailored to my needs. For instance, I created performance trendlines to track how my portfolio has performed against the S&P 500 index, fees tracker to highlight the importance of less is more, and industry and regional breakdown to visualize diversification.

<br/>

This combination of BigQuery and Looker transformed the way I manage my investments. The dashboard not only saves time but also provides valuable insights that help me make more informed decisions.

<br/>
